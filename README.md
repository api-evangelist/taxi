# Taxi - Describe How Your APIs and Data Relate (taxi-describe-how-your-apis-and-data-relate)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Taxi is an open-source language (Apache 2.0) for describing APIs, data models, and how data relates across an entire ecosystem. TaxiQL is a declarative query language that lets consumers define the data they want while Taxi handles orchestration across REST APIs, databases, Kafka topics, gRPC services, and S3 buckets. Taxi eliminates manual integration code by using semantic type annotations to automatically discover data paths and adapt to evolving API schemas.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/taxi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/taxi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- API Description
- Data Integration
- Open Source
- Query Language
- Schema
- Semantic

## Timestamps

- **Created:** 2026-01-05
- **Modified:** 2026-05-19

## APIs

### Taxi Language

The core Taxi schema language for defining types, models, API services, and semantic annotations. Used to describe OpenAPI, Protobuf, database schemas, and Kafka topics with rich type semantics that power TaxiQL queries and data orchestration.

- **Human URL:** [https://taxilang.org/](https://taxilang.org/)

#### Tags

- API Description
- Data Modeling
- Open Source
- Schema
- Semantic Types

#### Properties

- [Documentation](https://docs.taxilang.org/)
- [Git Hub](https://github.com/taxilang/taxilang)
- [OpenAPI](openapi/taxi-language-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/taxi-language.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taxi-language.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TaxiQL Query API

TaxiQL is a declarative query language for federated data retrieval across multiple APIs and data sources. Queries specify the desired data structure using semantic types and Taxi automatically discovers the data paths, calls APIs, and assembles results.

- **Human URL:** [https://docs.taxilang.org/language-reference/querying-with-taxiql/](https://docs.taxilang.org/language-reference/querying-with-taxiql/)

#### Tags

- Data Query
- Federated Query
- Open Source
- Query Language

#### Properties

- [Documentation](https://docs.taxilang.org/language-reference/querying-with-taxiql/)
- [Git Hub](https://github.com/taxilang/taxilang)
- [Postman Collection](collections/taxi-language.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taxi-language.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Orbital Platform

Orbital is the companion data platform for Taxi that hosts TaxiQL queries, provides a schema registry, and executes federated data integrations across APIs, databases, and streams using Taxi annotations.

- **Human URL:** [https://orbitalhq.com](https://orbitalhq.com)

#### Tags

- Data Platform
- Federated Query
- Integration
- Schema Registry

#### Properties

- [Documentation](https://orbitalhq.com)
- [Postman Collection](collections/taxi-language.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taxi-language.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Taxi Playground

Interactive web-based editor for writing Taxi schemas and TaxiQL queries with live diagram generation and query execution preview.

- **Human URL:** [https://playground.taxilang.org](https://playground.taxilang.org)

#### Tags

- Developer Tools
- Playground
- Schema Editor

#### Properties

- [Documentation](https://playground.taxilang.org)
- [Postman Collection](collections/taxi-language.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taxi-language.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/taxi)
- [Website](https://taxilang.org/)
- [Documentation](https://docs.taxilang.org/)
- [Git Hub  Org](https://github.com/taxilang)
- [Playground](https://playground.taxilang.org)
- [Slack](https://join.slack.com/t/taxi-lang/shared_invite)
- [OpenAPI](openapi/taxi-language-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/taxi-schema-definition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/taxi-schema-structure.json)
- [JSON-LD](json-ld/taxi-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/taxi-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
