# Hotelbeds (hotelbeds)

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
