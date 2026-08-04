# Predibase (predibase)

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

Predibase is a platform for fine-tuning and serving open-source LLMs. It pairs efficient LoRA / Turbo LoRA supervised and reinforcement (GRPO) fine-tuning with serverless and dedicated inference powered by LoRAX, the open-source multi-LoRA serving stack that packs hundreds of adapters onto a single GPU. Inference is exposed through an OpenAI-compatible API plus native generate endpoints.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/predibase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/predibase/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Fine-Tuning
- Inference
- LoRA

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Predibase Inference (OpenAI-Compatible) API

OpenAI-compatible chat completions and completions served from Predibase serverless and dedicated deployments, with per-request LoRA adapter selection via the model field and SSE streaming when stream is true.

- **Human URL:** [https://docs.predibase.com/user-guide/inference/migrate-openai](https://docs.predibase.com/user-guide/inference/migrate-openai)
- **Base URL:** `https://serving.app.predibase.com/{tenant}/deployments/v2/llms/{model}/v1`

#### Tags

- Chat
- Completions
- LLM
- OpenAI Compatible

#### Properties

- [Documentation](https://docs.predibase.com/user-guide/inference/migrate-openai)
- [API Reference](https://docs.predibase.com/user-guide/inference/rest_api)
- [OpenAPI](openapi/predibase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/predibase-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/predibase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/predibase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Predibase Prompt / Generate API

Native text-generation endpoints (generate and generate_stream) for prompting deployed base models and fine-tuned adapters, with adapter source selection (pbase, hub, or s3) and token-streaming responses.

- **Human URL:** [https://docs.predibase.com/user-guide/inference/rest_api](https://docs.predibase.com/user-guide/inference/rest_api)
- **Base URL:** `https://serving.app.predibase.com/{tenant}/deployments/v2/llms/{model}`

#### Tags

- Prompt
- Generate
- Streaming

#### Properties

- [Documentation](https://docs.predibase.com/user-guide/inference/rest_api)
- [API Reference](https://docs.predibase.com/user-guide/inference/querying-models/text-generation)
- [OpenAPI](openapi/predibase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/predibase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/predibase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Predibase Fine-Tuning API

Create and manage supervised and reinforcement (GRPO) fine-tuning jobs that train efficient LoRA / Turbo LoRA adapters on top of open-source base models, returning adapter versions for serving.

- **Human URL:** [https://docs.predibase.com/user-guide/fine-tuning/overview](https://docs.predibase.com/user-guide/fine-tuning/overview)
- **Base URL:** `https://api.app.predibase.com/v2`

#### Tags

- Fine-Tuning
- LoRA
- GRPO
- Reinforcement Learning

#### Properties

- [Documentation](https://docs.predibase.com/user-guide/fine-tuning/overview)
- [Documentation](https://docs.predibase.com/user-guide/fine-tuning/grpo)
- [OpenAPI](openapi/predibase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/predibase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/predibase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Predibase Adapters API

Manage adapter repositories and the trained adapter versions inside them - the LoRA artifacts produced by fine-tuning jobs that are loaded onto deployments for inference.

- **Human URL:** [https://docs.predibase.com/fine-tuning/adapters](https://docs.predibase.com/fine-tuning/adapters)
- **Base URL:** `https://api.app.predibase.com/v2`

#### Tags

- Adapters
- Repos
- Versions

#### Properties

- [Documentation](https://docs.predibase.com/fine-tuning/adapters)
- [OpenAPI](openapi/predibase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/predibase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/predibase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Predibase Deployments API

Create, read, update, and delete dedicated and private serverless deployments, selecting a base model and GPU accelerator (A10, A100) and enabling LoRA serving for fine-tuned adapters.

- **Human URL:** [https://docs.predibase.com/user-guide/inference/dedicated_deployments](https://docs.predibase.com/user-guide/inference/dedicated_deployments)
- **Base URL:** `https://api.app.predibase.com/v2`

#### Tags

- Deployments
- Dedicated
- Serverless

#### Properties

- [Documentation](https://docs.predibase.com/user-guide/inference/dedicated_deployments)
- [Documentation](https://docs.predibase.com/user-guide/inference/private_deployments)
- [OpenAPI](openapi/predibase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/predibase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/predibase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Predibase Datasets API

Connect and manage datasets used as input to fine-tuning jobs, uploaded from files or referenced from connected storage.

- **Human URL:** [https://docs.predibase.com/user-guide/getting-started/fine-tuning-and-serving](https://docs.predibase.com/user-guide/getting-started/fine-tuning-and-serving)
- **Base URL:** `https://api.app.predibase.com/v2`

#### Tags

- Datasets
- Training Data

#### Properties

- [Documentation](https://docs.predibase.com/user-guide/getting-started/fine-tuning-and-serving)
- [OpenAPI](openapi/predibase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/predibase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/predibase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Predibase Models API

List the open-source base models supported on Predibase for fine-tuning and serving, with metadata used when creating jobs and deployments.

- **Human URL:** [https://docs.predibase.com/user-guide/inference/models](https://docs.predibase.com/user-guide/inference/models)
- **Base URL:** `https://api.app.predibase.com/v2`

#### Tags

- Models
- Catalog
- Base Models

#### Properties

- [Documentation](https://docs.predibase.com/user-guide/inference/models)
- [OpenAPI](openapi/predibase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/predibase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/predibase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Predibase Batch Inference API

Launch asynchronous batch inference jobs against a base model with per-row adapter selection, billed at a flat per-million-token batch rate for non-realtime workloads.

- **Human URL:** [https://docs.predibase.com/user-guide/inference/BatchInference](https://docs.predibase.com/user-guide/inference/BatchInference)
- **Base URL:** `https://api.app.predibase.com/v2`

#### Tags

- Batch
- Async

#### Properties

- [Documentation](https://docs.predibase.com/user-guide/inference/BatchInference)
- [OpenAPI](openapi/predibase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/predibase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/predibase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/predibase)
- [LinkedIn](https://www.linkedin.com/company/predibase)
- [Website](https://predibase.com)
- [Documentation](https://docs.predibase.com)
- [Plans](plans/predibase-plans-pricing.yml)
- [Rate Limits](rate-limits/predibase-rate-limits.yml)
- [Fin Ops](finops/predibase-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
