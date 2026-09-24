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

## Latest GitHub Updates

### More ways to request and configure Copilot code reviews

Copilot code review now offers additional personal configurations across an
expanded set of Copilot plans, plus a new enterprise-level default setting.
Teams can enable a dedicated personal review configuration so Copilot code
review behaves consistently for every developer in the organization.

*Source: GitHub Changelog · September 23, 2026*

### Node 20 retired from GitHub Actions runners

Node 20 is no longer available on GitHub Actions runners. JavaScript actions
now run on Node 24, and the temporary
`ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION` opt-out no longer works. Repository
maintainers should update any custom actions that still pin Node 20.

*Source: GitHub Changelog · September 23, 2026*

### Local sandboxing in the GitHub Copilot app

The GitHub Copilot app can now run commands inside a local sandbox that
limits access to files, network resources, and credentials on your machine.
This reduces the potential impact of unintended commands during agentic
coding sessions, and it's configured directly in the Copilot app settings.

*Source: GitHub Changelog · September 23, 2026*

### Security improvements for SSH

GitHub is removing several older SSH algorithms, adding a new algorithm, and
requiring larger RSA SSH keys to improve security. Developers using
older SSH key types or algorithms should rotate their keys ahead of the
removal to avoid losing SSH access.

*Source: GitHub Changelog · September 22, 2026*

### Migrating the GitHub Copilot runtime to Rust, using Copilot

The GitHub Blog shares how the team ported roughly 800,000 lines of the
Copilot agent runtime to Rust with help from Copilot itself, a rewrite that
wasn't affordable before coding agents existed. It's a good read on how
large-scale agentic refactors work in practice.

*Source: GitHub Blog · September 2026*
