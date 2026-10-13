# Deliverability basics

Developer-facing notes on **SPF**, **DKIM**, **DMARC**, and reputation. No fake SLAs or compliance claims.

## Chapters

1. [Why DNS auth matters](./01-why-dns-auth.md)
2. [SPF](./02-spf.md)
3. [DKIM](./03-dkim.md)
4. [DMARC](./04-dmarc.md)
5. [Reputation and warm-up myths](./05-reputation.md)
6. [Shared vs dedicated IPs](./06-shared-vs-dedicated.md)

## Appendix: related open-source tools

Short developer-facing pointers—not a full OSS email catalog. For servers, MTAs, and platforms in depth, use [Mindbaz/awesome-opensource-email](https://github.com/Mindbaz/awesome-opensource-email).

| Tool | Role |
|------|------|
| [Mailpit](https://github.com/axllent/mailpit) | Local SMTP catcher + UI/API for safe testing |
| [MailHog](https://github.com/mailhog/MailHog) | Legacy local SMTP catcher (still widely referenced) |
| [OpenDKIM](http://www.opendkim.org/) | DKIM signing/verification for self-hosted MTAs |
| [Postal](https://github.com/postalserver/postal) | Self-hosted mail delivery platform |

Hosted email APIs (Notify, Resend, Postmark, SES, …) are **not** open-source software—see [awesome-email-apis](https://github.com/email-api/awesome-email-apis).

## Related

- Notify domain verification: https://notify.cx/docs/domain-verification
- Deliverability overview: https://notify.cx/email-api/deliverability
- Email API guide: https://github.com/email-api/email-api-guide
- Awesome email APIs: https://github.com/email-api/awesome-email-apis
