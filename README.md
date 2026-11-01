# StepFun

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

StepFun (阶跃星辰) is a Shanghai-based AI foundation-model company whose open platform serves the Step model family — multimodal reasoning (step-3.7-flash), fast language reasoning (step-3.5-flash), vision, image generation and editing (step-2x-large, step-image-edit-2), and a deep audio stack spanning TTS, voice cloning, ASR, and end-to-end realtime voice (StepAudio 2.5) — via an OpenAI-compatible REST API at api.stepfun.com, an Anthropic-compatible Messages API, WebSocket realtime channels, and a hosted StepSearch MCP server for agent clients.

**Areas:** Artificial Intelligence · LLM · Multi-Modal · Chat Completions · Audio · Speech · Text-to-Speech · Speech Recognition · Image · Real-Time · Vector Stores · China

## StepFun on APIs.io

Everything profiled for StepFun is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/stepfun/](https://apis.io/providers/stepfun/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [StepFun Chat Completions API](https://apis.io/apis/stepfun/chat-completions-api/) — OpenAI-compatible chat completions for the Step model family (e.g. step-3.7-flash, step-3.5-flash, stepaudio-2.5-chat), with multimodal image/video/audio…
- [StepFun Messages API](https://apis.io/apis/stepfun/messages-api/) — Anthropic Messages API-compatible endpoint (POST /v1/messages) that lets the Anthropic SDK and Claude-style JSON structures run against Step models by…
- [StepFun Responses API](https://apis.io/apis/stepfun/responses-api/) — OpenAI Responses API-style endpoint for generating model responses on the StepFun open platform.
- [StepFun Models API](https://apis.io/apis/stepfun/models-api/) — List available Step models, retrieve a single model, and inspect the model object.
- [StepFun Audio API](https://apis.io/apis/stepfun/audio-api/) — Speech synthesis (TTS), voice cloning with preview, official voice catalog, audio transcription, and file-based / streaming speech recognition (ASR) across…
- [StepFun Realtime API](https://apis.io/apis/stepfun/realtime-api/) — Bidirectional realtime voice over WebSocket (wss://api.stepfun.com/v1/realtime) with OpenAI Realtime-style session, conversation, and response events, plus…
- [StepFun Images API](https://apis.io/apis/stepfun/images-api/) — Image generation, image editing, and image-to-image endpoints for the step-2x-large and step-image-edit-2 models.
- [StepFun Files API](https://apis.io/apis/stepfun/files-api/) — Upload, list, retrieve, delete files and fetch file content for use with Step models and knowledge bases.
- [StepFun Vector Stores API](https://apis.io/apis/stepfun/vector-stores-api/) — Knowledge-base (vector store) management — create/list/retrieve/delete stores and attach or remove files for retrieval-augmented generation.
- [StepFun Web Search API](https://apis.io/apis/stepfun/web-search-api/) — Web search and text-to-image search endpoints (POST /v1/search) billed per call as value-added capabilities.
- [StepFun Token Count API](https://apis.io/apis/stepfun/token-count-api/) — Pre-count prompt tokens for a model request (POST /v1/token/count) to estimate usage and cost.
- [StepFun Accounts API](https://apis.io/apis/stepfun/accounts-api/) — Retrieve account information including balances (GET /v1/accounts).

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [StepFun Realtime Voice & Streaming TTS WebSocket API](https://apis.io/asyncapis/stepfun/stepfun-realtime-asyncapi/)

#### Event channels (2)

Individual events and webhooks the provider emits.

- [/v1/realtime](https://apis.io/channels/stepfun/v1-realtime/)
- [/v1/realtime/audio](https://apis.io/channels/stepfun/v1-realtime-audio/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [stepsearch](https://apis.io/servers/stepfun/stepsearch/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Stepfun Authentication](https://apis.io/security/stepfun/stepfun-authentication/)
- [Stepfun Domain Security](https://apis.io/security/stepfun/stepfun-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Stepfun Plans Pricing](https://apis.io/plans/stepfun/stepfun-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Stepfun Rate Limits](https://apis.io/rate-limits/stepfun/stepfun-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.stepfun.com)
- [Documentation](https://platform.stepfun.com/docs)
- [Getting started](https://platform.stepfun.com/docs/zh/quickstart/overview)
- [API reference](https://platform.stepfun.com/docs/zh/api-reference/chat/chat-completion-create)
- [Pricing](https://platform.stepfun.com/docs/zh/guides/pricing/details)
- [Sign up](https://platform.stepfun.com)
- [Support](https://platform.stepfun.com/docs/zh/guides/contact-us)
- [Blog](https://www.stepfun.com/blog/)
- [Terms of service](https://platform.stepfun.com/docs/zh/agreement/userservice)
- [Privacy policy](https://platform.stepfun.com/docs/zh/agreement/userprivacy)
- [GitHub](https://github.com/stepfun-ai)

## API Evangelist rating

**Kin Score 54.4** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 39.6 |
| Contract governance | 18.2 |
| Operational transparency | 42.1 |
| Developer ergonomics | 64.3 |
| Access clarity | 76.3 |

**Agent readiness 30.6** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
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
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 22.7** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/stepfun/](https://apis.io/providers/stepfun/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for StepFun: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/stepfun/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
