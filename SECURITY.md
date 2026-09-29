# Security

Please report a vulnerability in any SnoutData product or repository privately, not in a public
issue. Either:

- use **Report a vulnerability** on the repository's Security tab, which opens a private advisory
  only we can see, or
- email **security@snoutdata.com**.

Include what you found, where, and the steps to reproduce it. Do not access, change or delete data
that is not yours, and do not test against other people's accounts or projects.

## What happens next

- We acknowledge your report within **3 business days**.
- We send you an assessment and a remediation timeline within **10 business days**.
- We aim to fix by severity: **Critical within 7 days**, **High within 30 days**, **Medium within
  90 days**.
- We tell you when it is fixed, and credit you in the release notes if you would like us to.

Please hold public disclosure until the fix ships or 90 days from your report, whichever is
sooner. We do not run a paid bug bounty.

## Safe harbor

We will not pursue or support legal action against anyone who researches and reports a
vulnerability in good faith under this policy: staying within the scope below, avoiding harm to
our users and their data, and giving us a reasonable time to fix it before disclosure.

## Scope

In scope: SnoutData Desktop, SnoutData Cloud (projects, the dashboard, `*.snoutdata.com`), the
`snoutdata` CLI, `@snoutdata/client`, and `snoutdata.com`. `*.snoutdata.com` includes other
customers' project hostnames: test only against projects and accounts you own.

Out of scope: denial-of-service and volumetric testing, social engineering, and third-party
services we use (report those to their vendor).

How we protect your data: <https://snoutdata.com/security>.
