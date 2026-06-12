# Blues (blues-wireless)

Blues (formerly Blues Wireless) is an IoT connectivity platform that provides Notecard hardware modules and the Notehub cloud service for routing device data from edge devices to cloud applications. The Notehub REST API enables developers to manage fleets of cellular, satellite, LoRa, and Wi-Fi connected devices across 130+ countries. Blues follows a consumption-based pricing model with no subscription fees, charging per ingressed event beyond a 5,000-event free monthly allowance bundled with each Notecard hardware purchase.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/blues-wireless/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/blues-wireless/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=blues-wireless-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=blues-wireless-api-evangelist&utm_content=repo)

## Tags

IoT, Cellular, Connectivity, Device Management, Fleet Management, Satellite, LoRa, WiFi, Notecard, Notehub

## APIs

### Notehub API
The Notehub REST API provides programmatic access to Blues Notehub for managing IoT device fleets, routing events, configuring projects, monitoring device health, and handling billing. It covers authorization, billing accounts, devices, events, jobs, monitoring, organizations, projects, routes, and usage reporting.

- Documentation: https://dev.blues.io/api-reference/notehub-api/api-introduction/
- OpenAPI: https://raw.githubusercontent.com/blues/notehub-js/main/openapi.yaml
- Base URL: https://api.notefile.net

### Notecard API
The Notecard API is the firmware-level JSON API for interacting with Blues Notecard hardware modules directly over serial or I2C. It supports card, dfu, env, file, hub, note, ntn, var, and web request categories.

- Documentation: https://dev.blues.io/api-reference/notecard-api/introduction/

## Plans, Rate Limits, and FinOps

### Plans
Blues offers an Essentials (freemium) plan and an Enterprise plan.

- **Essentials**: 5,000 free events/month; $0.000750 per additional event; 7 API req/min (10,200/day) free
- **Enterprise**: Starting at $1,000/month; 50%+ discount off Essentials rate; custom API rate limits; 4-hour support SLA

Full details: [plans/blues-wireless-plans-pricing.yml](plans/blues-wireless-plans-pricing.yml)

### Rate Limits
- Essentials: 7 API requests per minute, 10,200 per day per billing account
- Enterprise: Custom higher limits
- Throttle response code: 429
- Authentication: Personal Access Tokens (recommended), OAuth 2.0 Client Credentials, or legacy session tokens

Full details: [rate-limits/blues-wireless-rate-limits.yml](rate-limits/blues-wireless-rate-limits.yml)

### FinOps
Billing model is consumption-based with no subscription fees. Key meters: events ingressed ($0.000750/event after free allowance), connectivity assurance data top-ups ($10 NA / $15 international per 500MB), and API requests (free up to daily limit).

Full details: [finops/blues-wireless-finops.yml](finops/blues-wireless-finops.yml)

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://blues.com |
| Developer Portal | https://dev.blues.io |
| Documentation | https://dev.blues.io/api-reference/ |
| GitHub Organization | https://github.com/blues |
| Blog | https://dev.blues.io/blog/ |
| Changelog | https://dev.blues.io/blog/whats-new-in-notehub/ |
| Pricing | https://blues.com/pricing/ |
| Status Page | https://status.notehub.io |
| LinkedIn | https://www.linkedin.com/company/buildwithblues |
| X | https://twitter.com/buildwithblues |
| SDKs | https://blues.github.io/opensource/ |

## Maintainers

- Kin Lane / kin@apievangelist.com
