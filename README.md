# TrackingMore

TrackingMore is a multi-carrier shipment tracking platform offering a unified REST API that integrates with 1,300+ global carriers including USPS, UPS, FedEx, DHL, and regional logistics providers. The API enables real-time parcel tracking, automated carrier detection, webhook notifications, delivery analytics, and branded tracking page customization for D2C merchants, ecommerce platforms, and enterprise logistics operations.

**API Base URL:** `https://api.trackingmore.com/v4`

**Authentication:** API key via `Tracking-Api-Key` request header (up to 4 keys per account)

## Key Resources

- [Website](https://www.trackingmore.com/)
- [API Documentation](https://www.trackingmore.com/docs/trackingmore/)
- [Quick Start Guide](https://www.trackingmore.com/docs/trackingmore/d5ac362fc3cda-api-quick-start-guide)
- [Authentication](https://www.trackingmore.com/docs/trackingmore/zte58cee4mz0v-api-authentication)
- [Rate Limits](https://www.trackingmore.com/docs/trackingmore/ft5s8mr1pyymy-rate-limit)
- [Pricing](https://www.trackingmore.com/pricing)
- [Webhooks](https://www.trackingmore.com/webhook.html)
- [GitHub SDKs](https://github.com/trackingmore-api)
- [Support](https://support.trackingmore.com/)

## SDKs

- [Python](https://github.com/TrackingMore-API/trackingmore-sdk-python)
- [Node.js](https://github.com/TrackingMore-API/trackingmore-sdk-nodejs)
- [PHP](https://github.com/TrackingMore-API/trackingmore-sdk-php)
- [Go](https://github.com/TrackingMore-API/trackingmore-sdk-go)
- [Ruby](https://github.com/TrackingMore-API/trackingmore-sdk-ruby)
- [Java](https://github.com/TrackingMore-API/trackingmore-sdk-java)
- [.NET](https://github.com/TrackingMore-API/trackingmore-sdk-net)

## Pricing Summary

| Plan | Monthly Cost | Shipments | API Access |
|------|-------------|-----------|------------|
| Free | $0 | 50/mo | No |
| Basic | $11 | 200/mo | No |
| Pro | $74 | 2,000/mo | Yes + Webhooks |
| Enterprise | Custom | Custom | Yes + Custom limits |

Overage rate: $0.04 per credit on Basic and Pro plans. Annual billing saves up to 20%.

## Rate Limits

- Create tracking: 3 req/s
- Most other endpoints: 10 req/s
- HTTP 429 on limit exceeded; wait 120 seconds before retry
- Enterprise: negotiable custom limits
