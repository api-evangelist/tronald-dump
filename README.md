# Tronald Dump (tronald-dump)

Tronald Dump is an open community REST API exposing a historical archive of Donald Trump quotes, with sources, authors, tags, and a search interface using HAL (Hypertext Application Language) JSON responses. The project was built by Marcel Wijnker (wickedest) and ran at tronalddump.io until the domain lapsed and the public service went offline; the data model, OpenAPI, and community SDKs survive in third-party repositories.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/tronald-dump/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=opensource-api-evangelist&utm_content=repo)

## Type

- **x-type:** opensource (community)
- **x-tier:** 3 (bulk-registered from public-apis)
- **x-status:** offline — `api.tronalddump.io` no longer resolves (NXDOMAIN as of 2026-05-30); `www.tronalddump.io` has been re-registered by a third party. The API surface here is reconstructed from the historical HAL contract and preserved community SDKs.
- **source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Games & Comics

## Tags

 - Community, Games And Comics, Open Source, Politics, Public APIs, Quotes, Trump

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Tronald Dump Quotes API

REST API returning Donald Trump quotes with metadata, tags, authors, and sources, using HAL JSON responses with `_links` and `_embedded` sections for hypermedia navigation. Includes random quote retrieval, quote-by-id lookup, full text search with pagination, tag browsing, author lookup, and source lookup.

**Human URL:** [https://www.tronalddump.io/](https://www.tronalddump.io/)

**Base URL:** `https://api.tronalddump.io`

#### Tags:

 - Authors, HAL, Hypermedia, Quotes, Search, Sources, Tags

#### Properties

- [Documentation](https://www.tronalddump.io/)
- [OpenAPI](openapi/tronald-dump-quotes-openapi.yml)
- [NaftikoCapability — Quotes](capabilities/quotes-quotes.yaml)
- [NaftikoCapability — Tags](capabilities/quotes-tags.yaml)
- [NaftikoCapability — Authors](capabilities/quotes-authors.yaml)
- [NaftikoCapability — Sources](capabilities/quotes-sources.yaml)

#### Contact

- **Marcel Wijnker** (original author) — [github.com/wickedest](https://github.com/wickedest)

## Common Properties

- [Website](https://www.tronalddump.io/)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [SourceCode — Original Author (Marcel Wijnker)](https://github.com/wickedest)
- [SourceCode — Original Node.js Client (tronalddump-io/client-nodejs)](https://github.com/tronalddump-io/client-nodejs)
- [SDK — TypeScript SDK (voxgig)](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/ts)
- [SDK — Python SDK (voxgig)](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/py)
- [SDK — Go SDK (voxgig)](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/go)
- [SDK — Ruby SDK (voxgig)](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/rb)
- [SDK — PHP SDK (voxgig)](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/php)
- [SDK — Lua SDK (voxgig)](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/lua)
- [CLI — Go CLI (voxgig)](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/go-cli)
- [Tools — MCP Server (voxgig, Go)](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/go-mcp)
- [CodeExamples — Flutter Sample (RicardoBelchior)](https://github.com/RicardoBelchior/TronaldDump)
- [CodeExamples — Android Sample (br00)](https://github.com/br00/TronaldDump)
- [CodeExamples — SwiftUI Sample (simonschuhmacher)](https://github.com/simonschuhmacher/tronald-swiftui)
- [CodeExamples — Mycroft Skill (krisgesling)](https://github.com/krisgesling/tronald-dump-skill)
- [CodeExamples — Alexa Skill (Tonkpils)](https://github.com/Tonkpils/tronalddump-alexa)
- [SpectralRuleset](rules/tronald-dump-spectral-rules.yml)
- [Vocabulary](vocabulary/tronald-dump-vocabulary.yaml)
- [JSONLDContext](json-ld/tronald-dump-context.jsonld)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Tronald Dump Quotes API](openapi/tronald-dump-quotes-openapi.yml) — 10 operations across 4 tags (Quotes, Tags, Authors, Sources), HAL response envelopes, Microcks-compatible inline examples on every operation

### JSON Schema

- [tronald-dump-quote-schema.json](json-schema/tronald-dump-quote-schema.json)
- [tronald-dump-author-schema.json](json-schema/tronald-dump-author-schema.json)
- [tronald-dump-source-schema.json](json-schema/tronald-dump-source-schema.json)
- [tronald-dump-tag-schema.json](json-schema/tronald-dump-tag-schema.json)
- [tronald-dump-quote-search-response-schema.json](json-schema/tronald-dump-quote-search-response-schema.json)
- [tronald-dump-tag-list-response-schema.json](json-schema/tronald-dump-tag-list-response-schema.json)
- [tronald-dump-author-list-response-schema.json](json-schema/tronald-dump-author-list-response-schema.json)
- [tronald-dump-source-list-response-schema.json](json-schema/tronald-dump-source-list-response-schema.json)

### JSON Structure

- [tronald-dump-quote-structure.json](json-structure/tronald-dump-quote-structure.json)
- [tronald-dump-author-structure.json](json-structure/tronald-dump-author-structure.json)
- [tronald-dump-source-structure.json](json-structure/tronald-dump-source-structure.json)
- [tronald-dump-tag-structure.json](json-structure/tronald-dump-tag-structure.json)
- [tronald-dump-quote-search-response-structure.json](json-structure/tronald-dump-quote-search-response-structure.json)
- [tronald-dump-tag-list-response-structure.json](json-structure/tronald-dump-tag-list-response-structure.json)
- [tronald-dump-author-list-response-structure.json](json-structure/tronald-dump-author-list-response-structure.json)
- [tronald-dump-source-list-response-structure.json](json-structure/tronald-dump-source-list-response-structure.json)

### JSON-LD

- [tronald-dump-context.jsonld](json-ld/tronald-dump-context.jsonld) — 15 property terms across the Quote, Author, Source, and Tag types, aligned with schema.org and the `td:` namespace

### Examples

- [tronald-dump-quote-example.json](examples/tronald-dump-quote-example.json)
- [tronald-dump-author-example.json](examples/tronald-dump-author-example.json)
- [tronald-dump-source-example.json](examples/tronald-dump-source-example.json)
- [tronald-dump-tag-example.json](examples/tronald-dump-tag-example.json)
- [tronald-dump-quote-search-response-example.json](examples/tronald-dump-quote-search-response-example.json)
- [tronald-dump-tag-list-response-example.json](examples/tronald-dump-tag-list-response-example.json)
- [tronald-dump-author-list-response-example.json](examples/tronald-dump-author-list-response-example.json)
- [tronald-dump-source-list-response-example.json](examples/tronald-dump-source-list-response-example.json)

## Capabilities

Naftiko capabilities — one self-contained file per OpenAPI tag, each declaring its own `consumes` block plus both REST and MCP exposers.

### Tronald Dump Quotes API

| Capability | Tools | Description |
|------------|-------|-------------|
| [Quotes](capabilities/quotes-quotes.yaml) | 3 | Random quote, quote lookup by ID, and full text search. |
| [Tags](capabilities/quotes-tags.yaml) | 2 | Tag vocabulary listing and tag-filtered quote retrieval. |
| [Authors](capabilities/quotes-authors.yaml) | 2 | Author listing and lookup by identifier. |
| [Sources](capabilities/quotes-sources.yaml) | 2 | Source document listing and lookup by identifier. |

## Vocabulary

- [tronald-dump-vocabulary.yaml](vocabulary/tronald-dump-vocabulary.yaml) — Unified taxonomy mapping 4 resources (Quote, Tag, Author, Source), 3 actions (get/list/search), 4 workflows, and 3 personas across the operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [tronald-dump-spectral-rules.yml](rules/tronald-dump-spectral-rules.yml) — 39 Spectral rules across 11 categories enforcing Tronald Dump conventions (kebab-case paths, snake_case properties, camelCase operationIds, Title Case tags, HAL response envelopes, no-auth public-API security posture).

## Notes

This entry was bulk-registered as part of a public-apis catalog sweep on 2026-05-28 and fully profiled on 2026-05-30 as an `opensource` community API. The original public endpoint at `api.tronalddump.io` is offline; the documented contract is recovered from the historical HAL surface and from community SDKs (notably the multi-language voxgig SDK and the original `tronalddump-io/client-nodejs` library). The Microcks-compatible OpenAPI spec means the surface can still be mocked locally and the capabilities can run against a mock server, which is the supported way to consume this API going forward.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
