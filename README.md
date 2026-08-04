# Yext

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
