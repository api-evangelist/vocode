# Vocode (vocode)

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

Vocode is an open-source Python library (vocode-core, MIT licensed) for building real-time, streaming voice AI agents that run over phone calls, plus a hosted REST API at https://api.vocode.dev/v1 (Bearer API key) for placing and managing outbound and inbound phone calls, configuring agents, voices, prompts, actions, phone numbers, and webhooks without operating the streaming infrastructure yourself.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vocode/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vocode/refs/heads/main/apis.yml)

## Tags

- Voice AI
- Voice Agents
- Telephony
- Conversational AI
- Phone Calls

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Vocode Calls API

Create outbound calls, look up a single call, list calls, end an active call, and download call recordings on the hosted Vocode platform, attaching an inline or saved agent to each call.

- **Human URL:** [https://docs.vocode.dev/api-reference/calls/create-call](https://docs.vocode.dev/api-reference/calls/create-call)
- **Base URL:** `https://api.vocode.dev/v1`

#### Tags

- Calls
- Outbound
- Inbound
- Telephony

#### Properties

- [Documentation](https://docs.vocode.dev/api-reference/calls/create-call)
- [API Reference](https://docs.vocode.dev/api-reference/calls/get-call)
- [OpenAPI](openapi/vocode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vocode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vocode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/vocodedev/vocode-core)

### Vocode Agents API

Create, retrieve, list, and update voice agents - each binding a prompt, language, voice, actions, webhook, and conversation behavior (interrupt sensitivity, endpointing, IVR navigation) used to drive a call.

- **Human URL:** [https://docs.vocode.dev/api-reference/agents/create-agent](https://docs.vocode.dev/api-reference/agents/create-agent)
- **Base URL:** `https://api.vocode.dev/v1`

#### Tags

- Agents
- Conversational AI
- LLM

#### Properties

- [Documentation](https://docs.vocode.dev/api-reference/agents/create-agent)
- [API Reference](https://docs.vocode.dev/api-reference/agents/get-agent)
- [OpenAPI](openapi/vocode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vocode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vocode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vocode Phone Numbers API

Buy, get, list, update, cancel, and link phone numbers, including binding an inbound agent to a number or bringing your own Twilio/Vonage number via an account connection.

- **Human URL:** [https://docs.vocode.dev/api-reference/numbers/buy-number](https://docs.vocode.dev/api-reference/numbers/buy-number)
- **Base URL:** `https://api.vocode.dev/v1`

#### Tags

- Phone Numbers
- Telephony
- Provisioning

#### Properties

- [Documentation](https://docs.vocode.dev/api-reference/numbers/buy-number)
- [API Reference](https://docs.vocode.dev/api-reference/numbers/get-number)
- [OpenAPI](openapi/vocode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vocode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vocode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vocode Actions API

Create, get, list, and update actions an agent can take mid-call - transfer call, end conversation, DTMF, set hold, add to conference, and external HTTP actions - triggered by function call or phrase.

- **Human URL:** [https://docs.vocode.dev/api-reference/actions/create-action](https://docs.vocode.dev/api-reference/actions/create-action)
- **Base URL:** `https://api.vocode.dev/v1`

#### Tags

- Actions
- Tools
- Function Calling

#### Properties

- [Documentation](https://docs.vocode.dev/api-reference/actions/create-action)
- [API Reference](https://docs.vocode.dev/api-reference/actions/get-action)
- [OpenAPI](openapi/vocode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vocode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vocode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vocode Voices API

Create, get, list, and update voices that agents speak with, wrapping ElevenLabs, Azure, PlayHt, Rime, and the native Vocode voice synthesizers.

- **Human URL:** [https://docs.vocode.dev/api-reference/voices/create-voice](https://docs.vocode.dev/api-reference/voices/create-voice)
- **Base URL:** `https://api.vocode.dev/v1`

#### Tags

- Voices
- Text to Speech
- Synthesis

#### Properties

- [Documentation](https://docs.vocode.dev/api-reference/voices/create-voice)
- [API Reference](https://docs.vocode.dev/api-reference/voices/get-voice)
- [OpenAPI](openapi/vocode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vocode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vocode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vocode Webhooks API

Create, get, list, and update webhooks that subscribe to call lifecycle events - message, action, call connected/ended, transcript, recording, and human detection - delivered to your endpoint via HTTP POST.

- **Human URL:** [https://docs.vocode.dev/api-reference/webhooks/create-webhook](https://docs.vocode.dev/api-reference/webhooks/create-webhook)
- **Base URL:** `https://api.vocode.dev/v1`

#### Tags

- Webhooks
- Events
- Callbacks

#### Properties

- [Documentation](https://docs.vocode.dev/api-reference/webhooks/create-webhook)
- [API Reference](https://docs.vocode.dev/api-reference/webhooks/get-webhook)
- [OpenAPI](openapi/vocode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vocode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vocode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vocode Realtime Streaming Conversation

Real-time, bidirectional streaming conversation pipeline (StreamingConversation) in the open-source library that wires transcription, agent response, and synthesis together; the hosted platform consumes telephony media-stream WebSockets, but no public client-facing wss conversation endpoint is documented in the hosted REST API.

- **Human URL:** [https://docs.vocode.dev/open-source/how-it-works](https://docs.vocode.dev/open-source/how-it-works)
- **Base URL:** `https://api.vocode.dev/v1`

#### Tags

- Realtime
- Streaming
- WebSocket

#### Properties

- [Documentation](https://docs.vocode.dev/open-source/how-it-works)
- [GitHub](https://github.com/vocodedev/vocode-core/blob/main/vocode/streaming/streaming_conversation.py)
- [Review](review.yml)

### Vocode Open Source Library

vocode-core, the MIT-licensed Python library for building voice-based LLM agents with pluggable STT, LLM, and TTS providers and Twilio/Vonage telephony, self-hosted and free, distinct from the hosted Vocode API.

- **Human URL:** [https://docs.vocode.dev/open-source/what-is-vocode](https://docs.vocode.dev/open-source/what-is-vocode)
- **Base URL:** `https://github.com/vocodedev/vocode-core`

#### Tags

- Open Source
- Python
- Library
- SDK

#### Properties

- [Documentation](https://docs.vocode.dev/open-source/what-is-vocode)
- [GitHub](https://github.com/vocodedev/vocode-core)

## Common Properties

- [GitHub Organization](https://github.com/vocodedev)
- [LinkedIn](https://www.linkedin.com/company/vocode)
- [Website](https://www.vocode.dev)
- [Documentation](https://docs.vocode.dev)
- [Plans](plans/vocode-plans-pricing.yml)
- [Rate Limits](rate-limits/vocode-rate-limits.yml)
- [Fin Ops](finops/vocode-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
