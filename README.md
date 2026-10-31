# Predibase

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

Predibase is a platform for fine-tuning and serving open-source LLMs. It pairs efficient LoRA / Turbo LoRA supervised and reinforcement (GRPO) fine-tuning with serverless and dedicated inference powered by LoRAX, the open-source multi-LoRA serving stack that packs hundreds of adapters onto a single GPU. Inference is exposed through an OpenAI-compatible API plus native generate endpoints.

**Areas:** Artificial Intelligence · LLM · Fine-Tuning · Inference · LoRA · Real-Time

## Predibase on APIs.io

Everything profiled for Predibase is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/predibase/](https://apis.io/providers/predibase/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Predibase Adapters API](https://apis.io/apis/predibase/predibase-adapters-api/) — The Adapters API from Predibase — 2 operation(s) for adapters.
- [Predibase Batch Inference API](https://apis.io/apis/predibase/predibase-batch-inference-api/) — The Batch Inference API from Predibase — 2 operation(s) for batch inference.
- [Predibase Datasets API](https://apis.io/apis/predibase/predibase-datasets-api/) — The Datasets API from Predibase — 2 operation(s) for datasets.
- [Predibase Deployments API](https://apis.io/apis/predibase/predibase-deployments-api/) — The Deployments API from Predibase — 2 operation(s) for deployments.
- [Predibase Fine-Tuning API](https://apis.io/apis/predibase/predibase-fine-tuning-api/) — The Fine-Tuning API from Predibase — 3 operation(s) for fine-tuning.
- [Predibase Inference API](https://apis.io/apis/predibase/predibase-inference-api/) — The Inference API from Predibase — 4 operation(s) for inference.
- [Predibase Models API](https://apis.io/apis/predibase/predibase-models-api/) — The Models API from Predibase — 1 operation(s) for models.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Predibase Inference Streaming (HTTP + SSE)](https://apis.io/asyncapis/predibase/predibase-asyncapi/)

#### Event channels (2)

Individual events and webhooks the provider emits.

- [/generate_stream](https://apis.io/channels/predibase/generate-stream/)
- [/v1/chat/completions](https://apis.io/channels/predibase/v1-chat-completions/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Predibase Agentic Access](https://apis.io/agentic-access/predibase/predibase-agentic-access/)

#### Collections (8)

Postman and Open Collection request collections.

- [Predibase API](https://apis.io/collections/predibase/open-predibase/)
- [Predibase Adapters API](https://apis.io/collections/predibase/open-predibase-adapters-api/)
- [Predibase Adapters Batch Inference API](https://apis.io/collections/predibase/open-predibase-batch-inference-api/)
- [Predibase Adapters Datasets API](https://apis.io/collections/predibase/open-predibase-datasets-api/)
- [Predibase Adapters Deployments API](https://apis.io/collections/predibase/open-predibase-deployments-api/)
- [Predibase Adapters Fine-Tuning API](https://apis.io/collections/predibase/open-predibase-fine-tuning-api/)
- [Predibase Adapters Inference API](https://apis.io/collections/predibase/open-predibase-inference-api/)
- [Predibase Adapters Models API](https://apis.io/collections/predibase/open-predibase-models-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Predibase — asyncapi rules](https://apis.io/rules/predibase/predibase-asyncapi-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Predibase Authentication](https://apis.io/security/predibase/predibase-authentication/)
- [Predibase Domain Security](https://apis.io/security/predibase/predibase-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Predibase Plans Pricing](https://apis.io/plans/predibase/predibase-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Predibase Rate Limits](https://apis.io/rate-limits/predibase/predibase-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Predibase Finops](https://apis.io/finops/predibase/predibase-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://predibase.com)
- [Documentation](https://docs.predibase.com)
- [GitHub](https://github.com/predibase)

## API Evangelist rating

**Kin Score 27.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 49.3 |
| Contract governance | 11.4 |
| Operational transparency | 10.5 |
| Developer ergonomics | 29.8 |
| Access clarity | 7.9 |

**Agent readiness 20.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 10.9** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/predibase/](https://apis.io/providers/predibase/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Predibase: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/predibase/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
