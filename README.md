# Vocode (vocode)

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
