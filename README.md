# Zoho Sign

Zoho Sign is a cloud-based electronic signature platform that provides a REST API for sending documents for signature, managing templates, tracking signing status, and automating signature workflows. The API supports OAuth 2.0 authentication and enables developers to create envelopes, manage recipients, configure signing fields, trigger bulk sends, and retrieve audit trails programmatically. Over 25,000 envelopes are sent daily through Zoho Sign APIs, covering use cases from simple document signing to embedded signing, in-person signing, and enterprise compliance workflows including 21 CFR Part 11 and QES.

- **Website**: https://www.zoho.com/sign/
- **Documentation**: https://www.zoho.com/sign/api/introduction.html
- **Pricing**: https://www.zoho.com/sign/pricing.html
- **Status**: https://status.zoho.com/
- **Blog**: https://www.zoho.com/blog/sign/
- **X**: https://twitter.com/ZohoSign
- **LinkedIn**: https://www.linkedin.com/company/zohosign

## API Details

- **Base URL**: `https://sign.zoho.com/api/v1`
- **Authentication**: OAuth 2.0 (Authorization Code flow)
- **Formats**: JSON request and response bodies
- **Rate Limit**: 50 API calls per minute (general endpoints)

## Plans

| Plan | Price | Envelopes |
|------|-------|-----------|
| Free | $0/user/month | 5/month total |
| Standard | $10/user/month (annual) | 25/user/month |
| Professional | $16/user/month (annual) | Unlimited |
| Enterprise | $22/user/month (annual) | Unlimited + 50 API credits/user/month |
| API Plan | Per envelope | Unlimited (pay-as-you-go) |

## Repository Contents

- `apis.yml` — APIs.json 0.19 provider profile
- `plans/zoho-sign-plans-pricing.yml` — Detailed plan and pricing information
- `rate-limits/zoho-sign-rate-limits.yml` — API rate limits and document constraints
- `finops/zoho-sign-finops.yml` — FinOps guidance for cost management
