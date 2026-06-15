# Pushover (pushover)

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
