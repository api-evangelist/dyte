# Dyte (dyte)

Dyte is a live video and voice developer platform offering client SDKs plus a v2 REST API for programmatically creating meetings, adding participants and issuing their auth tokens, querying completed sessions, and managing recordings, livestreams, and webhooks. Dyte was acquired by Cloudflare in 2025 and is transitioning into Cloudflare RealtimeKit; the Dyte SDKs and APIs are in maintenance mode.

> **Status note:** Dyte was acquired by Cloudflare (announced April 2025) and its products are being folded into **Cloudflare RealtimeKit**. The existing Dyte SDKs and v2 REST API remain documented and operational but are in maintenance mode and no longer receive feature updates. New builds are directed to Cloudflare RealtimeKit. This catalog documents the still-live Dyte v2 REST API as of the modified date.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dyte/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dyte/refs/heads/main/apis.yml)

## Tags

- Video
- Voice
- Real Time
- WebRTC
- SDK
- Communications

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Dyte Meetings API

Create, list, fetch, and update video/voice meeting rooms in an organization via the v2 REST API. A meeting ID is the anchor for adding participants, recordings, and livestreams.

- **Human URL:** [https://docs.dyte.io/api](https://docs.dyte.io/api)
- **Base URL:** `https://api.dyte.io/v2`

#### Tags

- Meetings
- Rooms
- Real Time

#### Properties

- [Documentation](https://docs.dyte.io/guides/rest-apis/quickstart)
- [API Reference](https://docs.dyte.io/api)
- [OpenAPI](openapi/dyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dyte Participants API

Add participants to a meeting and receive the auth token required to initialize the frontend SDKs, plus list, fetch, edit, delete, and regenerate participant tokens against an assigned preset.

- **Human URL:** [https://docs.dyte.io/api](https://docs.dyte.io/api)
- **Base URL:** `https://api.dyte.io/v2`

#### Tags

- Participants
- Auth Tokens
- Presets

#### Properties

- [Documentation](https://docs.dyte.io/guides/rest-apis/quickstart)
- [API Reference](https://docs.dyte.io/api)
- [OpenAPI](openapi/dyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dyte Sessions API

Retrieve information about completed meetings (sessions) across an organization, including participant lists and details, plus active-session lookups for ongoing meetings. Responses are paginated.

- **Human URL:** [https://docs.dyte.io/api](https://docs.dyte.io/api)
- **Base URL:** `https://api.dyte.io/v2`

#### Tags

- Sessions
- Analytics
- History

#### Properties

- [Documentation](https://docs.dyte.io/guides/v2-migration-guide)
- [API Reference](https://docs.dyte.io/api)
- [OpenAPI](openapi/dyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dyte Recordings API

Start, stop, list, and fetch meeting recordings with optional custom (e.g. AWS S3) storage configuration. Recording status updates are delivered asynchronously via webhooks.

- **Human URL:** [https://docs.dyte.io/api](https://docs.dyte.io/api)
- **Base URL:** `https://api.dyte.io/v2`

#### Tags

- Recordings
- Storage
- S3

#### Properties

- [Documentation](https://docs.dyte.io/guides/capabilities/recording/start-recording)
- [API Reference](https://docs.dyte.io/api)
- [OpenAPI](openapi/dyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dyte Livestreams API

Create and manage livestreams for a meeting - start streaming, fetch active-livestream status with ingest/playback details, stop a livestream, and list a meeting's livestreams.

- **Human URL:** [https://docs.dyte.io/guides/rest-apis/livestream-dyte-meeting](https://docs.dyte.io/guides/rest-apis/livestream-dyte-meeting)
- **Base URL:** `https://api.dyte.io/v2`

#### Tags

- Livestreams
- RTMP
- HLS

#### Properties

- [Documentation](https://docs.dyte.io/guides/rest-apis/livestream-dyte-meeting)
- [API Reference](https://docs.dyte.io/api)
- [OpenAPI](openapi/dyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dyte Webhooks API

Register, list, update, and delete webhook subscriptions that push real-time events (participant joined/left, recording completed, and more) to your application endpoint.

- **Human URL:** [https://docs.dyte.io/api](https://docs.dyte.io/api)
- **Base URL:** `https://api.dyte.io/v2`

#### Tags

- Webhooks
- Events
- Callbacks

#### Properties

- [Documentation](https://docs.dyte.io/guides/rest-apis/quickstart)
- [API Reference](https://docs.dyte.io/api)
- [OpenAPI](openapi/dyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/dyte-io)
- [LinkedIn](https://www.linkedin.com/company/dyteio)
- [Website](https://dyte.io/)
- [Documentation](https://docs.dyte.io/)
- [Plans](plans/dyte-plans-pricing.yml)
- [Rate Limits](rate-limits/dyte-rate-limits.yml)
- [Fin Ops](finops/dyte-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
