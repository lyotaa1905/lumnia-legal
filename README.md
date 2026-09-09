# Lumnia Legal

Official legal and verification pages for **Lumnia**, a Discord moderation bot built around durable warning records, case history, and reliable moderation logs.

## Pages

| Page | Purpose |
| --- | --- |
| `index.html` | Lumnia legal site landing page |
| `terms.html` | Terms of Service |
| `privacy.html` | Privacy Policy |
| `verify.html` | Discord verification and Linked Roles landing page |

## Deployment

This repository is deployed automatically through Cloudflare Pages.

Commits to the `main` branch trigger a new production deployment.

**Production site:**  
https://lumnia-legal.pages.dev/

## Verification

The verification interface is currently informational.

Discord OAuth2 and Linked Roles verification require a secure server-side implementation and are not provided by the static `verify.html` page alone.

No Discord client secrets or other private credentials should ever be committed to this repository or exposed through client-side JavaScript.

## Repository Scope

This repository contains Lumnia's public-facing legal website.

The Lumnia Discord bot, backend services, infrastructure configuration, credentials, and private application source code are maintained separately and are not part of this repository.

## Legal

The documents in this repository are maintained for Lumnia and may change as the Service, infrastructure, or legal requirements evolve.

The Terms of Service and Privacy Policy published on the deployed website should be treated as the current public versions when they are made available for production use.

## Copyright

Copyright © 2026 Lumnia. All rights reserved.

See [`LICENSE`](LICENSE) for repository licensing information.
