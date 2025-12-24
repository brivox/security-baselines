# Secure Headers Baseline (Web)

Recommended baseline for modern web applications.

## Headers
- Content-Security-Policy (CSP)
- Strict-Transport-Security (HSTS)
- X-Content-Type-Options: nosniff
- Referrer-Policy
- Permissions-Policy

## Notes
- CSP must be tailored per app and tested in report-only first.
- HSTS should be enabled after HTTPS is fully enforced.
