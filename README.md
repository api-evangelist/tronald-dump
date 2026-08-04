# Tronald Dump (tronald-dump)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Tronald Dump is an open community REST API exposing a historical archive of Donald Trump quotes, with sources, authors, tags, and a search interface using HAL (Hypertext Application Language) JSON responses. The project was built by Marcel Wijnker (wickedest) and ran at tronalddump.io until the domain lapsed and the public service went offline; the data model, OpenAPI, and community SDKs survive in third-party repositories.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tronald-dump/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tronald-dump/refs/heads/main/apis.yml)

## Tags

- Community
- Games And Comics
- Open Source
- Politics
- Public APIs
- Quotes
- Trump

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Tronald Dump Quotes API

REST API returning Donald Trump quotes with metadata, tags, authors, and sources, using HAL JSON responses with _links and _embedded sections for hypermedia navigation. Includes random quote retrieval, quote-by-id lookup, full text search with pagination, tag browsing, author lookup, and source lookup.

- **Human URL:** [https://www.tronalddump.io/](https://www.tronalddump.io/)
- **Base URL:** `https://api.tronalddump.io`

#### Tags

- Authors
- HAL
- Hypermedia
- Quotes
- Search
- Sources
- Tags

#### Properties

- [Documentation](https://www.tronalddump.io/)
- [OpenAPI](openapi/tronald-dump-quotes-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tronald-dump-quotes.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tronald-dump-quotes.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.tronalddump.io/)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Source Code](https://github.com/wickedest)
- [Source Code](https://github.com/tronalddump-io/client-nodejs)
- [SDK](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/ts)
- [SDK](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/py)
- [SDK](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/go)
- [SDK](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/rb)
- [SDK](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/php)
- [SDK](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/lua)
- [C L I](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/go-cli)
- [Tools](https://github.com/voxgig-sdk/tronalddump-sdk/tree/main/go-mcp)
- [Code Examples](https://github.com/RicardoBelchior/TronaldDump)
- [Code Examples](https://github.com/br00/TronaldDump)
- [Code Examples](https://github.com/simonschuhmacher/tronald-swiftui)
- [Code Examples](https://github.com/krisgesling/tronald-dump-skill)
- [Code Examples](https://github.com/Tonkpils/tronalddump-alexa)
- [Spectral Ruleset](rules/tronald-dump-spectral-rules.yml)
- [Vocabulary](vocabulary/tronald-dump-vocabulary.yaml)
- [J S O N L D Context](json-ld/tronald-dump-context.jsonld)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
