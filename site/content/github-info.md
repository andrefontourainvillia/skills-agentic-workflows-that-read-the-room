# GitHub Info

## Mona's editorial angle

Mona's website focuses on practical GitHub guidance backed by official references from:

- docs.github.com
- github.blog
- github.blog/changelog

## Current homepage themes

- GitHub collaboration basics: repositories, branches, pull requests, and merges.
- GitHub Copilot as an AI coding assistant across the IDE, CLI, and GitHub.
- GitHub Actions as the automation layer behind repository workflows.
- Recent GitHub Blog and Changelog stories worth watching.

## Recent GitHub Blog and Changelog highlights

- **Copilot code review gets personal settings.** Every Copilot plan, including
  Copilot Business, now has a dedicated "code review" settings page for
  automatic review and default review effort, plus an enterprise-wide default
  review effort setting for organization-owned repos. (Source: GitHub
  Changelog, "More ways to request and configure Copilot code reviews," Sep 23,
  2026.)
- **Node 20 has been fully retired from GitHub Actions.** Runners now use Node
  24 for JavaScript actions, and the `ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION`
  opt-out no longer works. If you maintain a JavaScript action, update
  `runs.using` to `node24` and ship a new release. (Source: GitHub Changelog,
  "Node 20 is no longer available in GitHub Actions," Sep 23, 2026.)
- **SSH is getting more secure.** GitHub is removing the SHA-1 `ssh-rsa`
  signature type and the `diffie-hellman-group-exchange-sha256` key exchange,
  requiring new RSA keys to be at least 3072 bits after October 14, 2026, and
  adding the post-quantum `mlkem768x25519-sha256` key exchange. (Source: GitHub
  Changelog, "Security improvements for SSH," Sep 22, 2026.)
- **Proof of presence for high-impact actions (public preview).** Enterprise
  Managed User (EMU) organizations using Microsoft Entra ID as their SSO
  provider can now require a fresh IdP re-authentication or MFA challenge
  before sensitive actions, guarding against stolen sessions and tokens.
  (Source: GitHub Changelog, "Require proof of presence for high-impact
  actions," Sep 24, 2026.)
- **CodeQL 2.27.1 sharpens code scanning.** The release adds new C/C++ and C#
  queries, Kotlin 2.4.20 support, and improved Go standard-library data-flow
  models to help catch more security issues in code scanning. (Source: GitHub
  Changelog, "CodeQL 2.27.1 adds C and C++ query and Kotlin 2.4.20 support,"
  Sep 25, 2026.)
