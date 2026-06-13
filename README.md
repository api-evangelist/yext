# Yext

Yext is a digital presence platform that enables businesses to manage their listings across 200+ publishers, update location data, manage reviews, and power AI search experiences. The platform's REST APIs provide programmatic access to the Knowledge Graph, Listings, Reviews, Analytics, and Content Delivery capabilities.

## APIs

- **Knowledge API** — Manage entities (locations, events, restaurants, healthcare facilities, hotels, custom types) in the Yext Knowledge Graph
- **Answers API** — AI-powered search experiences with natural language query support
- **Chat API** — Conversational AI chat experiences powered by the Knowledge Graph
- **Events API** — Event-driven workflows and event management
- **Live API** — High-performance Content Delivery API for consumer-facing experiences
- **Admin API** — Account, user, and platform administration
- **Publisher Listings API** — Listing data syndication for publisher partners
- **Publisher ECL API** — Enhanced Content Library for publisher partners
- **Publisher Notify Review API** — Review notification for publisher partners
- **Publisher Tracking Pixel API** — Impression and click tracking for publisher partners
- **Webhooks** — Real-time event notifications for entity, review, and listing changes

## Authentication

All requests use API key authentication via the `api_key` query parameter or `api-key` header. A required `v` parameter specifies the API version in `YYYYMMDD` format.

## Base URLs

| Environment | Management API | Content Delivery API |
|-------------|---------------|----------------------|
| Production | `https://api.yextapis.com/v2` | `https://cdn.yextapis.com/v2` |
| Sandbox | `https://sbx-api.yextapis.com/v2` | `https://sbx-cdn.yextapis.com/v2` |
| US partition | `https://api.us.yextapis.com/v2` | `https://cdn.us.yextapis.com/v2` |
| EU partition | `https://api.eu.yextapis.com/v2` | `https://cdn.eu.yextapis.com/v2` |

## Rate Limits

- Management API: 5,000 requests/hour
- Analytics API: 1,000 requests/hour
- Content Delivery API: 100,000 requests/hour

## Links

- [Website](https://www.yext.com)
- [Developer Portal](https://developer.yext.com)
- [Hitchhikers Docs](https://hitchhikers.yext.com/docs/)
- [GitHub](https://github.com/yext)
- [OpenAPI Specs](https://github.com/yext/openapi)
- [Status Page](https://www.yexttrust.com/)
- [Blog](https://www.yext.com/blog)
- [Developer Blog](https://developer.yext.com/blog/)
