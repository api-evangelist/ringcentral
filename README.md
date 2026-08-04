# RingCentral (ringcentral)

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

RingCentral provides unified cloud communications for businesses including voice, video, messaging, contact center, and events. The RingCentral API exposes call control, SMS, faxing, voicemail, presence, team messaging, video, and analytics.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ringcentral/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ringcentral/refs/heads/main/apis.yml)

## Tags

- Communications
- UCaaS
- Voice
- Video
- Contact Center
- SMS
- Messaging
- Fax

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-30

## APIs

### RingCentral Voice API

The RingCentral Voice API enables developers to incorporate voice and phone functionality into applications. It supports placing calls (RingOut, WebRTC, URI scheme), call control (active call manipulation, transfer, hold, recording), call routing rules, monitoring, supervision, conferencing, and call log retrieval.

#### Tags

- Voice
- Telephony
- Call Control
- RingOut

#### Properties

- [Documentation](https://developers.ringcentral.com/voice-api)
- [API Reference](https://developers.ringcentral.com/api-reference/Call-Control)
- [OpenAPI](openapi/ringcentral-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ringcentral-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ringcentral-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RingCentral SMS API

The RingCentral SMS API supports targeted and bulk SMS and MMS with deep insights and regulatory compliance built in. It supports sending and receiving messages, A2P 10DLC registration, message status reporting, and message store retrieval.

#### Tags

- SMS
- Messaging
- A2P
- Compliance

#### Properties

- [Documentation](https://developers.ringcentral.com/sms-api)
- [API Reference](https://developers.ringcentral.com/api-reference/SMS)
- [Postman Collection](collections/ringcentral-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ringcentral-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RingCentral Team Messaging API

The RingCentral Team Messaging API enables developers to build chatbots, send notifications, and create add-ins within RingCentral Team Messaging (formerly Glip). It supports posting messages, managing chats, file attachments, persons/groups, events, webhooks, and adaptive cards.

#### Tags

- Team Messaging
- Chat
- Bots
- Add-ins

#### Properties

- [Documentation](https://developers.ringcentral.com/team-messaging-api)
- [API Reference](https://developers.ringcentral.com/api-reference/Team-Messaging)
- [Postman Collection](collections/ringcentral-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ringcentral-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RingCentral Video API

The RingCentral Video API powers high-quality, secure video meetings in the browser without requiring a downloaded app. It exposes endpoints for scheduling meetings, joining/embedding video sessions, managing recordings, and webhook events for meeting lifecycle.

#### Tags

- Video
- Meetings
- Webinars
- Conferencing

#### Properties

- [Documentation](https://developers.ringcentral.com/video-api)
- [API Reference](https://developers.ringcentral.com/api-reference/Video)
- [Postman Collection](collections/ringcentral-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ringcentral-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RingCentral Fax API

The RingCentral Fax API enables developers to add programmable and customizable fax sending and receiving capabilities to applications, including multi-attachment support, scheduled delivery, and inbound fax retrieval.

#### Tags

- Fax
- Documents

#### Properties

- [Documentation](https://developers.ringcentral.com/fax-api)
- [API Reference](https://developers.ringcentral.com/api-reference/Fax)
- [Postman Collection](collections/ringcentral-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ringcentral-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RingCentral Data API

The RingCentral Data API helps customers manage and ensure regulatory compliance with call data, message data, and video recordings, supporting bulk export, archival, and supervisory retrieval workflows.

#### Tags

- Compliance
- Data
- Recordings
- Exports

#### Properties

- [Documentation](https://developers.ringcentral.com/data-api)
- [API Reference](https://developers.ringcentral.com/api-reference/Compliance-Exports)
- [Postman Collection](collections/ringcentral-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ringcentral-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RingCentral Audio and Video AI API

The RingCentral Audio and Video AI API exposes speech-to-text, summarization, and conversational analytics on call and meeting media, enabling developers to extract transcripts, action items, and insights from RingCentral communications.

#### Tags

- AI
- Transcription
- Summarization
- Speech-to-Text

#### Properties

- [Documentation](https://developers.ringcentral.com/ai-api)
- [API Reference](https://developers.ringcentral.com/api-reference/AI)
- [Postman Collection](collections/ringcentral-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ringcentral-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RingCentral Call Log API

The RingCentral Call Log API provides historical call data, recordings, and synchronization endpoints used to power analytics, billing, and compliance retention systems.

#### Tags

- Call Log
- Analytics
- History

#### Properties

- [API Reference](https://developers.ringcentral.com/api-reference/Call-Log)
- [Postman Collection](collections/ringcentral-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ringcentral-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RingCentral Call Analytics API

The RingCentral Call Analytics API exposes aggregated metrics, KPIs, and reporting endpoints for inbound and outbound calling activity at the user, queue, department, and account levels.

#### Tags

- Analytics
- KPIs
- Reporting

#### Properties

- [API Reference](https://developers.ringcentral.com/api-reference/Analytics)
- [Postman Collection](collections/ringcentral-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ringcentral-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RingCentral Presence API

The RingCentral Presence API exposes real-time and historical presence/availability state for users and call queues, including DND, telephony state, and meeting status, with subscription-based change notifications.

#### Tags

- Presence
- Status
- Real-Time

#### Properties

- [API Reference](https://developers.ringcentral.com/api-reference/Presence)
- [Postman Collection](collections/ringcentral-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ringcentral-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RingCentral Voicemail API

The RingCentral Voicemail API enables retrieval, playback, and management of voicemail messages, including transcripts, attachments, and read/unread state.

#### Tags

- Voicemail
- Messaging

#### Properties

- [API Reference](https://developers.ringcentral.com/api-reference/Voicemail)
- [Postman Collection](collections/ringcentral-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ringcentral-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RingCentral Provisioning API

The RingCentral Provisioning API supports account, extension, user, phone-number, device, and role lifecycle operations needed to programmatically onboard, configure, and manage RingCentral tenants.

#### Tags

- Provisioning
- Account
- Extensions
- Phone Numbers

#### Properties

- [API Reference](https://developers.ringcentral.com/api-reference/Account-Provisioning)
- [Postman Collection](collections/ringcentral-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ringcentral-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RingCentral Webhooks and Subscriptions API

The RingCentral Webhooks and Subscriptions API delivers event notifications (telephony, messaging, presence, account, etc.) to subscriber endpoints via webhooks or PubNub channels.

#### Tags

- Webhooks
- Events
- Subscriptions
- PubNub

#### Properties

- [API Reference](https://developers.ringcentral.com/api-reference/Subscriptions)
- [Documentation](https://developers.ringcentral.com/guide/notifications)
- [AsyncAPI](asyncapi/ringcentral-subscriptions-asyncapi.yaml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/ringcentral-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ringcentral-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RingCentral Contact Center API

The RingCentral Contact Center (RingCX) API provides programmatic access to omnichannel contact-center capabilities including agent state, queues, routing, real-time and historical reporting, and skills-based agent assignment.

#### Tags

- Contact Center
- CCaaS
- Agents
- Routing

#### Properties

- [API Reference](https://developers.ringcentral.com/api-reference/Contact-Center)
- [Postman Collection](collections/ringcentral-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ringcentral-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RingCentral Events API

The RingCentral Events API supports the lifecycle of large-scale virtual and hybrid events including event creation, registration, sessions, sponsors, attendees, and reporting.

#### Tags

- Events
- Webinars
- Hub

#### Properties

- [API Reference](https://developers.ringcentral.com/api-reference/Events)
- [Postman Collection](collections/ringcentral-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ringcentral-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/ringcentral)
- [Website](https://www.ringcentral.com/)
- [Developer  Portal](https://developers.ringcentral.com/)
- [Documentation](https://developers.ringcentral.com/api-products)
- [API Reference](https://developers.ringcentral.com/api-reference)
- [Getting Started](https://developers.ringcentral.com/guide/getting-started)
- [Authentication](https://developers.ringcentral.com/guide/authentication)
- [Rate Limits](https://developers.ringcentral.com/guide/basics/rate-limits)
- [Errors](https://developers.ringcentral.com/guide/basics/errors)
- [S D Ks](https://developers.ringcentral.com/sdks-tools)
- [Status Page](https://status.ringcentral.com/)
- [Pricing](https://www.ringcentral.com/office/plansandpricing.html)
- [Sign Up](https://developers.ringcentral.com/login.html#/register)
- [Login](https://developers.ringcentral.com/login.html)
- [GitHub Organization](https://github.com/ringcentral)
- [Blog](https://www.ringcentral.com/blog/)
- [Changelog](https://developers.ringcentral.com/api-reference/release-notes)
- [Webhooks](https://developers.ringcentral.com/api-reference/Subscriptions)
- [Postman  Workspace](https://www.postman.com/ringcentral)
- [X ( Twitter)](https://x.com/RingCentralDevs)
- [YouTube](https://www.youtube.com/@RingCentralDevelopers)
- [Plans](plans/ringcentral-plans-pricing.yml)
- [Rate Limits](rate-limits/ringcentral-rate-limits.yml)
- [Fin Ops](finops/ringcentral-finops.yml)
- [Integrations](https://www.ringcentral.com/apps/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
