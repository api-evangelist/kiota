# Kiota

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

Kiota is Microsoft's open source (MIT) API client generator: a command line tool that turns any OpenAPI-described API into a strongly-typed, lightweight client in C#, Dart, Go, Java, PHP, Python, Ruby or TypeScript. It exists to remove the need to take a dependency on a different hand-written SDK for every API you call. Kiota generates only the source it needs on top of a small per-language core library, keeps external dependencies minimal, and can target a filtered subset of a large description. Beyond code SDKs it also emits agent-facing plugin packages — apiplugin for Microsoft 365 Copilot declarative agents, openai manifests, and API Manifest permission snapshots. Kiota is a consumer of API descriptions rather than a publisher of an API: there is no Kiota endpoint, base URL, API key or status page. Its surface is a CLI, runtime libraries in eight package registries, a published OpenAPI extension vocabulary, and a nine-rule description validation ruleset it runs before every generation.

**Areas:** Code Generation · Microsoft · OpenAPI · SDK · Developer Tools · API Client · Open Source · CLI · JSON Schema · SDK Generation

## Kiota on APIs.io

Everything profiled for Kiota is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/kiota/](https://apis.io/providers/kiota/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Kiota](https://apis.io/apis/kiota/kiota/) — Kiota generates strongly-typed, lightweight API clients from OpenAPI descriptions in C#, Dart, Go, Java, PHP, Python, Ruby and TypeScript, with minimal…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (1)

The data models the API reads and writes.

- [Kiota Workspace](https://apis.io/schemas/kiota/kiota-workspace/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Kiota Vocabulary](https://apis.io/vocabularies/kiota/kiota-vocabulary/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Kiota — validation rules](https://apis.io/rules/kiota/kiota-validation-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Kiota Authentication](https://apis.io/security/kiota/kiota-authentication/)
- [Kiota Domain Security](https://apis.io/security/kiota/kiota-domain-security/)
- [Kiota Vulnerability Disclosure](https://apis.io/security/kiota/kiota-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Kiota Plans Pricing](https://apis.io/plans/kiota/kiota-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Kiota Rate Limits](https://apis.io/rate-limits/kiota/kiota-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Kiota Finops](https://apis.io/finops/kiota/kiota-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://learn.microsoft.com/en-us/openapi/kiota/)
- [Documentation](https://learn.microsoft.com/en-us/openapi/kiota/overview)
- [Getting started](https://learn.microsoft.com/en-us/openapi/kiota/quickstarts/)
- [API reference](https://learn.microsoft.com/en-us/openapi/kiota/using)
- [Support](https://github.com/microsoft/kiota/issues)
- [Blog](https://devblogs.microsoft.com/microsoft365dev/)
- [Terms of service](https://learn.microsoft.com/en-us/legal/termsofuse)
- [Privacy policy](https://privacy.microsoft.com/en-us/privacystatement)
- [GitHub](https://github.com/microsoft/kiota)

## API Evangelist rating

**Kin Score 45.0** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 0.0 |
| Contract governance | 33.3 |
| Operational transparency | 44.7 |
| Developer ergonomics | 71.4 |
| Access clarity | 28.9 |

**Agent readiness 3.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 30.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/kiota/](https://apis.io/providers/kiota/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Kiota: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/kiota/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
