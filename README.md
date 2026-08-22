# Hotelbeds (hotelbeds)

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

Hotelbeds (now part of HBX Group) is a global B2B travel bedbank and accommodation wholesaler. Its APItude suite of REST APIs lets travel sellers search, price, and book hotels, activities, and transfers, and pull static content and cached availability, authenticated with an Api-key plus a SHA256 X-Signature of the API key, secret, and request timestamp.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hotelbeds/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hotelbeds/refs/heads/main/apis.yml)

## Tags

- Travel
- Hotels
- Bedbank
- Accommodation
- Booking

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Hotel Booking API

Hotel availability search, real-time rate checking (checkrates), and the full booking lifecycle - confirm, list, detail, modify, and cancel reservations - across the Hotelbeds accommodation bedbank.

- **Human URL:** [https://developer.hotelbeds.com/documentation/hotels/booking-api/](https://developer.hotelbeds.com/documentation/hotels/booking-api/)
- **Base URL:** `https://api.hotelbeds.com/hotel-api/1.0`

#### Tags

- Hotels
- Booking
- Availability
- Rates

#### Properties

- [Documentation](https://developer.hotelbeds.com/documentation/hotels/booking-api/)
- [API Reference](https://developer.hotelbeds.com/documentation/hotels/booking-api/workflow/)
- [OpenAPI](openapi/hotelbeds-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hotelbeds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hotelbeds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hotel Content API

All static information needed to operate the Booking API - hotels, countries, destinations, accommodations, boards, categories, chains, facilities, segments, and currencies - served over fast REST GET endpoints.

- **Human URL:** [https://developer.hotelbeds.com/documentation/hotels/content-api/](https://developer.hotelbeds.com/documentation/hotels/content-api/)
- **Base URL:** `https://api.hotelbeds.com/hotel-content-api/1.0`

#### Tags

- Hotels
- Content
- Static Data

#### Properties

- [Documentation](https://developer.hotelbeds.com/documentation/hotels/content-api/)
- [API Reference](https://developer.hotelbeds.com/documentation/hotels/content-api/how-use-content-api/)
- [OpenAPI](openapi/hotelbeds-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hotelbeds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hotelbeds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cache Rates API

Bulk cached price and availability snapshots for high-volume search, letting integrators index inventory locally and reduce live availability calls before rechecking up-to-date rates through the Booking API.

- **Human URL:** [https://developer.hotelbeds.com/documentation/hotels/cache-api/](https://developer.hotelbeds.com/documentation/hotels/cache-api/)
- **Base URL:** `https://api.hotelbeds.com/cache-api/1.0`

#### Tags

- Hotels
- Cache
- Rates

#### Properties

- [Documentation](https://developer.hotelbeds.com/documentation/hotels/cache-api/)
- [OpenAPI](openapi/hotelbeds-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hotelbeds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hotelbeds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Activities API

Real-time availability, rate checking, and booking management for tours and activities, plus activity content and portfolio data such as countries and destinations.

- **Human URL:** [https://developer.hotelbeds.com/documentation/activities/](https://developer.hotelbeds.com/documentation/activities/)
- **Base URL:** `https://api.hotelbeds.com/activity-api/3.0`

#### Tags

- Activities
- Tours
- Booking

#### Properties

- [Documentation](https://developer.hotelbeds.com/documentation/activities/)
- [API Reference](https://developer.hotelbeds.com/documentation/activities/booking-api/overview/)
- [OpenAPI](openapi/hotelbeds-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hotelbeds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hotelbeds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Transfers API

Ground transportation availability and booking by IATA code, GPS coordinates, or Hotelbeds custom codes, covering airport, hotel, and point-to-point transfers, plus transfer content such as routes and vehicle types.

- **Human URL:** [https://developer.hotelbeds.com/documentation/transfers/](https://developer.hotelbeds.com/documentation/transfers/)
- **Base URL:** `https://api.hotelbeds.com/transfer-api/1.0`

#### Tags

- Transfers
- Ground Transport
- Booking

#### Properties

- [Documentation](https://developer.hotelbeds.com/documentation/transfers/)
- [API Reference](https://developer.hotelbeds.com/documentation/transfers/transfer-api/)
- [OpenAPI](openapi/hotelbeds-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hotelbeds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hotelbeds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webhooks

Outbound booking event notifications - confirmations, modifications, and cancellations - pushed to integrator endpoints so partner systems stay in sync without polling. Availability varies by partner agreement.

- **Human URL:** [https://developer.hotelbeds.com/documentation/hotels/booking-api/](https://developer.hotelbeds.com/documentation/hotels/booking-api/)
- **Base URL:** `https://api.hotelbeds.com/hotel-api/1.0`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://developer.hotelbeds.com/documentation/hotels/booking-api/)
- [OpenAPI](openapi/hotelbeds-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/hbxgroup)
- [Website](https://www.hotelbeds.com)
- [Documentation](https://developer.hotelbeds.com/documentation/)
- [Plans](plans/hotelbeds-plans-pricing.yml)
- [Rate Limits](rate-limits/hotelbeds-rate-limits.yml)
- [Fin Ops](finops/hotelbeds-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
