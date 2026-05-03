# Taxi - Describe How Your APIs and Data Relate

Taxi is an open-source language (Apache 2.0) for describing APIs, data models, and how data relates across an entire ecosystem. TaxiQL is a declarative query language that lets consumers define the data they want while Taxi handles orchestration across REST APIs, databases, Kafka topics, gRPC services, and S3 buckets — without resolvers or glue code.

**Website:** [https://taxilang.org/](https://taxilang.org/)
**Documentation:** [https://docs.taxilang.org/](https://docs.taxilang.org/)
**GitHub:** [https://github.com/taxilang/taxilang](https://github.com/taxilang/taxilang)
**Playground:** [https://playground.taxilang.org](https://playground.taxilang.org)
**Orbital Platform:** [https://orbitalhq.com](https://orbitalhq.com)

## APIs

### Taxi Language API
Schema compilation, type registry, TaxiQL query execution, and OpenAPI-to-Taxi conversion.
- **Docs:** [https://docs.taxilang.org/](https://docs.taxilang.org/)

### TaxiQL Query API
Declarative federated queries across registered data sources.
- **Docs:** [https://docs.taxilang.org/language-reference/querying-with-taxiql/](https://docs.taxilang.org/language-reference/querying-with-taxiql/)

### Orbital Platform
Schema registry and query execution runtime for Taxi-annotated APIs.
- **URL:** [https://orbitalhq.com](https://orbitalhq.com)

## Artifacts

### OpenAPI Specifications
| API | File |
|-----|------|
| Taxi Language API | [openapi/taxi-language-openapi.yml](openapi/taxi-language-openapi.yml) |

### JSON Schemas
| Schema | File |
|--------|------|
| Taxi Schema Definition | [json-schema/taxi-schema-definition-schema.json](json-schema/taxi-schema-definition-schema.json) |

### JSON Structure
| Structure | File |
|-----------|------|
| Taxi Schema Structure | [json-structure/taxi-schema-structure.json](json-structure/taxi-schema-structure.json) |

### JSON-LD Context
| Context | File |
|---------|------|
| Taxi Context | [json-ld/taxi-context.jsonld](json-ld/taxi-context.jsonld) |

### Spectral Rules
| Ruleset | File |
|---------|------|
| Taxi Rules | [rules/taxi-spectral-rules.yml](rules/taxi-spectral-rules.yml) |

### Naftiko Capabilities
| Capability | File | Description |
|-----------|------|-------------|
| Data Integration | [capabilities/data-integration.yaml](capabilities/data-integration.yaml) | Schema authoring, TaxiQL queries, type discovery, and OpenAPI conversion |

**Shared definitions:**
| Definition | File |
|-----------|------|
| Taxi API | [capabilities/shared/taxi-api.yaml](capabilities/shared/taxi-api.yaml) |

### Examples
| Example | File |
|---------|------|
| Compile Schema | [examples/taxi-compile-schema-example.json](examples/taxi-compile-schema-example.json) |
| Execute TaxiQL Query | [examples/taxi-execute-query-example.json](examples/taxi-execute-query-example.json) |

### Vocabulary
| Vocabulary | File |
|-----------|------|
| Taxi Vocabulary | [vocabulary/taxi-vocabulary.yml](vocabulary/taxi-vocabulary.yml) |

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
