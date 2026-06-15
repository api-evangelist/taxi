# Taxi - Describe How Your APIs and Data Relate (taxi-describe-how-your-apis-and-data-relate)

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
