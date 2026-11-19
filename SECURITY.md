# Security Policy

## Supported versions

This policy covers the live website at <https://bulkwright.com> and the current release of the Bulkwright desktop application distributed to approved beta testers and customers.

| Version | Supported |
| --- | --- |
| Live website (`https://bulkwright.com`) | Yes |
| Current desktop application | Yes |
| Earlier versions or forks | No |

## Reporting a vulnerability

Email **info@bulkwright.com** with `"Security"` in the subject line.

Please include:

- What you found and where (URL, screen, or component),
- Steps to reproduce it,
- Potential impact and any proof-of-concept request, payload, or screenshot.

Do not open a public GitHub issue for a security vulnerability, and please do not disclose it publicly until we have shipped a fix.

### Response targets

| Stage | Target |
| --- | --- |
| Acknowledge your report | 3 business days |
| Initial assessment and severity rating | 7 business days |
| Fix shipped or dated remediation plan | 30 days |

## Scope

In scope:

- The public Bulkwright website at <https://bulkwright.com>,
- The current release of the Bulkwright desktop application,
- Public forms hosted on <https://bulkwright.com>.

Out of scope:

- Third-party services integrated with or linked from the product or website (such as Meta, Stripe, Vercel, and Google), which should be reported directly to those vendors,
- Automated scanner output without a working proof of concept,
- Volumetric denial of service, social engineering, or issues requiring physical access to a device.
