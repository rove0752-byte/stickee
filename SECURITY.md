# Security policy

## Report a vulnerability privately

**Do not open a public issue, discussion or pull request for a security problem.**

Report it privately through GitHub:

1. Go to the [Security tab](https://github.com/stickee-aus/stickee/security).
2. Click **Report a vulnerability** (direct link: <https://github.com/stickee-aus/stickee/security/advisories/new>).
3. Describe what you found, how to reproduce it, and what it affects.

<!-- TODO(Jacko): confirm "Private vulnerability reporting" is switched on in repo Settings → Code security. Until it is, the link above will not work. -->
<!-- TODO(Jacko): add a backup security contact email here. -->

## What to expect

- We aim to reply within 7 days.
- We will tell you when it is fixed and credit you if you want.
- Please give us reasonable time to fix it before you share details publicly.

## In scope

- This repository's code (web app, API routes, Supabase migrations and policies).
- Payment and donation flows (Stripe Checkout and webhooks).
- Auth, admin access, and database row-level security.

## Out of scope

- Attacks on Stickee's production site or users. Test only against your own local copy.
- Denial-of-service, spam, or social engineering.
- Issues in third-party services (Stripe, Supabase, Vercel). Report those to the vendor.

## Rules for testers

- Never use real payment details. Use Stripe test mode only.
- Never access or change other people's data.
- Never commit secrets. If you find one in the repo or its history, report it privately here.
