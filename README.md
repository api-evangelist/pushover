# Pushover (pushover)

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

Pushover is a simple push notification service that delivers real-time notifications to phones, tablets, desktops, and watches from servers, scripts, and applications. The Pushover Message API accepts HTTPS POSTs with an application token and user/group key to send formatted messages with priorities, sounds, images, and supplementary URLs. Additional APIs exist for groups, subscriptions, licensing, receipts, and Open Client.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pushover/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pushover/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Notifications
- Push Notifications
- Messaging
- Alerts
- Monitoring

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-30

## APIs

### Pushover Message API

REST API for sending push notifications to Pushover users and groups via HTTPS POSTs to /1/messages.json. Authentication is token-based, requiring an application API token and recipient user/group key with each request; supports priorities, attachments, HTML, and sounds.

- **Human URL:** [https://pushover.net/api](https://pushover.net/api)
- **Base URL:** `https://api.pushover.net/1`

#### Tags

- Notifications
- Messaging
- Push
- Alerts

#### Properties

- [Documentation](https://pushover.net/api)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/pushover/refs/heads/main/openapi/pushover-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Groups  A P I](https://pushover.net/api/groups)
- [Subscriptions](https://pushover.net/api/subscriptions)
- [Receipts](https://pushover.net/api#receipt)
- [Open  Client](https://pushover.net/api/client)
- [Postman Collection](collections/pushover.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pushover.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pushover Open Client API

Real-time client API for Pushover. Combines a WebSocket channel at wss://client.pushover.net/push that streams single-byte control frames (`#` keepalive, `!` new message, `R` reload, `E` permanent error, `A` session closed) with REST channels for user login, device registration, message download, deletion, and emergency-priority acknowledgement.

- **Human URL:** [https://pushover.net/api/client](https://pushover.net/api/client)
- **Base URL:** `https://client.pushover.net`

#### Tags

- Notifications
- Push Notifications
- WebSocket
- Real-Time
- Streaming

#### Properties

- [Documentation](https://pushover.net/api/client)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/pushover/refs/heads/main/openapi/pushover-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/pushover.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pushover.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/pushoverapp)
- [Website](https://pushover.net)
- [Documentation](https://pushover.net/api)
- [Pricing](https://pushover.net/pricing)
- [Sign Up](https://pushover.net/signup)
- [F A Q](https://pushover.net/faq)
- [Support](https://pushover.net/support)
- [Status Page](https://status.pushover.net)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
