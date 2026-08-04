# Cartesia (cartesia)

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

Cartesia is a real-time multimodal AI platform built around the Sonic family of ultra-low-latency text-to-speech models and the Ink streaming speech-to-text models. Sonic models deliver the first audio byte in as little as 90ms, support more than 40 languages, and can express laughter and emotion, making them well-suited to conversational AI, voice agents, dubbing, and avatar applications. Ink models add streaming transcription with native turn detection optimized for voice agents. Cartesia ships Python, JavaScript, and Go SDKs and exposes REST, server-sent events, and WebSocket interfaces for streaming audio. The platform is SOC 2 Type II, HIPAA, and PCI Level 1 aligned.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cartesia/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cartesia/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Voice
- TTS
- Text to Speech
- STT
- Speech to Text
- Streaming
- WebSocket
- Voice Agents
- Voice Clone
- Sonic
- Ink
- Real-Time

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-29

## APIs

### Cartesia Sonic Text-to-Speech API

The Sonic text-to-speech API converts text into ultra-low-latency, emotive speech with sub-100ms time-to-first-byte. It supports REST, server-sent events, and WebSocket streaming for real-time voice agents and applications.

- **Human URL:** [https://docs.cartesia.ai](https://docs.cartesia.ai)
- **Base URL:** `https://api.cartesia.ai`

#### Tags

- TTS
- Streaming
- SSE
- WebSocket
- Real-Time
- Voice

#### Properties

- [Documentation](https://docs.cartesia.ai)
- [Getting Started](https://docs.cartesia.ai/get-started)
- [Sign Up](https://play.cartesia.ai)
- [API Reference](https://docs.cartesia.ai/api-reference)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/cartesia/refs/heads/main/asyncapi/cartesia-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [SDK](https://github.com/cartesia-ai/cartesia-python)
- [SDK](https://github.com/cartesia-ai/cartesia-js)
- [SDK](https://github.com/cartesia-ai/cartesia-go)
- [GitHub Repository](https://github.com/cartesia-ai)
- [Pricing](https://cartesia.ai/pricing)
- [Authentication](https://docs.cartesia.ai)
- [Postman Collection](collections/cartesia.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cartesia.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cartesia Ink Speech-to-Text API

The Ink streaming speech-to-text API transcribes audio in real time with native turn detection tuned for voice agents and conversational systems.

- **Human URL:** [https://docs.cartesia.ai](https://docs.cartesia.ai)
- **Base URL:** `https://api.cartesia.ai`

#### Tags

- STT
- Streaming
- Turn Detection
- Voice Agents
- WebSocket

#### Properties

- [Documentation](https://docs.cartesia.ai)
- [API Reference](https://docs.cartesia.ai/api-reference)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/cartesia/refs/heads/main/asyncapi/cartesia-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [SDK](https://github.com/cartesia-ai/cartesia-python)
- [SDK](https://github.com/cartesia-ai/cartesia-js)
- [Pricing](https://cartesia.ai/pricing)
- [Postman Collection](collections/cartesia.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cartesia.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://cartesia.ai)
- [Documentation](https://docs.cartesia.ai)
- [Blog](https://cartesia.ai/blog)
- [GitHub Organization](https://github.com/cartesia-ai)
- [Pricing](https://cartesia.ai/pricing)
- [Terms of Service](https://cartesia.ai/legal/terms-of-service)
- [Privacy Policy](https://cartesia.ai/legal/privacy-policy)
- [Discord](https://discord.gg/cartesia)
- [X (Twitter)](https://x.com/cartesia_ai)
- [LinkedIn](https://www.linkedin.com/company/cartesia-ai)
- [L L Ms Txt](https://docs.cartesia.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
