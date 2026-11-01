# Session AI

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

Session AI (formerly ZineOne) is an ecommerce AI platform that uses agentic decisioning to optimize promotions and customer experiences in real time. Its Session Marketing Agent predicts in-session visitor intent and behavior, then delivers personalized offers, nudges, and messages to maximize revenue, conversions, and profit margins for retail, travel and hospitality, and telecom brands. The platform integrates via tag managers (Google Tag Manager, Tealium), a CDN-delivered HTML5/JavaScript SDK, Android and iOS SDKs, server-to-server REST calls, and prebuilt plugins/cartridges, advertising sub-50ms decision latency, no PII in scope, and SOC 2 aligned controls. Session AI publishes a public developer guide and REST API reference under its legacy ZineOne domain covering nine documented operations — send events, retrieve content, call microservices, stream and cube queries, CCPA profile opt-in/opt-out, and profile and activity retrieval — authenticated with an apikey header. It also operates an OAuth-protected remote MCP server at https://sessionai.com/mcp for agent access.

**Areas:** Company · Artificial Intelligence · E-Commerce · Retail · Personalization · Marketing · AI Agents · Decisioning · Customer Data · Event · Real-Time · MCP

## Session AI on APIs.io

Everything profiled for Session AI is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/sessionai/](https://apis.io/providers/sessionai/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [Session AI Platform REST API](https://apis.io/apis/sessionai/session-ai-platform-rest-api/) — Public REST API for the Session AI (ZineOne) platform. Documented operations cover sending events into the platform from any channel, retrieving hosted…
- [Session AI MCP Server](https://apis.io/apis/sessionai/session-ai-mcp-server/) — Remote Model Context Protocol server operated by Session AI at https://sessionai.com/mcp. The endpoint answers with an RFC 9728 OAuth challenge…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Sessionai Webhooks](https://apis.io/asyncapis/sessionai/sessionai-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Session AI](https://apis.io/servers/sessionai/session-ai/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Sessionai Authentication](https://apis.io/security/sessionai/sessionai-authentication/)
- [Sessionai Domain Security](https://apis.io/security/sessionai/sessionai-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Sessionai Scopes](https://apis.io/scopes/sessionai/sessionai-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Sessionai Plans Pricing](https://apis.io/plans/sessionai/sessionai-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Sessionai Rate Limits](https://apis.io/rate-limits/sessionai/sessionai-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://sessionai.com)
- [Documentation](https://docs.zineone.com/)
- [Getting started](https://devguide.zineone.com/docs/introduction-to-html5)
- [API reference](https://devguide.zineone.com/docs/rest-api-reference)
- [Support](https://sessionai.com/contact-us)
- [Blog](https://sessionai.com/blog)
- [Compliance](https://sessionai.com/capabilities/privacy-and-fairness)
- [Terms of service](https://sessionai.com/terms)
- [Privacy policy](https://sessionai.com/privacy-policy)
- [Status](https://status.sessionai.com/)

## API Evangelist rating

**Kin Score 43.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 39.0 |
| Contract governance | 18.2 |
| Operational transparency | 23.7 |
| Developer ergonomics | 52.4 |
| Access clarity | 35.5 |

**Agent readiness 32.2** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 36.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/sessionai/](https://apis.io/providers/sessionai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Session AI: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/sessionai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
