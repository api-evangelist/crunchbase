# Crunchbase (crunchbase)

Crunchbase is a business data platform tracking companies, investors, funding rounds, acquisitions, and IPOs across the global startup and private market ecosystem. The Crunchbase v4 REST API provides programmatic access to 600+ endpoints powering customer-facing products, workflow enrichment, and AI training data.

**APIs.yml URL:** https://raw.githubusercontent.com/api-evangelist/crunchbase/refs/heads/main/apis.yml

## Scope

- **Type:** Index
- **Access:** 3rd-Party
- **x-type:** company

## Tags

Business Data, Funding, Investments, Startups, Private Markets, Firmographics

## APIs

### Crunchbase API

The Crunchbase v4 REST API provides programmatic access to Crunchbase's business data covering organizations, people, investors, funding rounds, acquisitions, and IPOs. Supports entity lookups, structured search, autocomplete, and deleted entity feeds.

- Base URL: https://api.crunchbase.com/api/v4
- Documentation: https://data.crunchbase.com/docs
- Authentication: API key in `X-cb-user-key` header
- OpenAPI: [openapi/crunchbase-openapi.yml](openapi/crunchbase-openapi.yml)

## Features

- Entity lookups for organizations, people, funding rounds, acquisitions, and IPOs
- Structured POST-based search with field/operator/value clauses
- Type-ahead autocomplete across collections
- Deleted entity feeds for incremental sync
- Field and card selection for narrow responses
- 600+ endpoints covering round-by-round funding data and firmographics
- API key authentication
- Per-key rate limiting

## Use Cases

- Market intelligence and competitor tracking
- Investor research (VC, PE, family office)
- Sales intelligence and account-based marketing
- Startup and corp-dev discovery
- AI model training and evaluation
- Customer-facing dashboards and signals

## Artifacts

- OpenAPI: [openapi/crunchbase-openapi.yml](openapi/crunchbase-openapi.yml)
- JSON Schema: [json-schema/crunchbase-organization-schema.json](json-schema/crunchbase-organization-schema.json)
- JSON-LD Context: [json-ld/crunchbase-context.jsonld](json-ld/crunchbase-context.jsonld)
- Vocabulary: [vocabulary/crunchbase-vocabulary.yml](vocabulary/crunchbase-vocabulary.yml)
- Spectral Rules: [rules/crunchbase-rules.yml](rules/crunchbase-rules.yml)
- Naftiko Capabilities: [capabilities/](capabilities/)

## Maintainers

- Kin Lane (kin@apievangelist.com)
