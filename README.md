# Dyte (dyte)

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
