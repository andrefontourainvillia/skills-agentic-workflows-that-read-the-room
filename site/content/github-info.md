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

### Private saved views for repository issues are now available

Repository issues pages now support private saved views, so developers can create and save personalized filters instead of re-entering the same search every time. The "Relates to" issue relationship also graduated to general availability and now works across the REST API, GraphQL API, webhooks, timeline events, issues search, and projects search.

Source: GitHub Changelog · September 25, 2026

### Copilot code review gets a dedicated personal settings page

Copilot code review now has a personal settings page under Profile → Copilot settings, available on every Copilot plan including Business and Enterprise. From there, developers can turn on automatic reviews for new pull requests, draft pull requests, and new pushes, and set their default review effort. Organizations can also set an enterprise-wide default review effort for repositories they own.

Source: GitHub Changelog · September 23, 2026

### Refreshed repository pull requests page is generally available

The redesigned pull requests page is now generally available to all GitHub users. It adds content-assisted filters, advanced search with AND/OR keywords and nested searches, a collapsible sidebar for common filters, a compact presentation mode, and bulk actions like closing, labeling, and changing milestones across multiple pull requests at once.

Source: GitHub Changelog · September 21, 2026

### Node 20 is no longer available in GitHub Actions

GitHub Actions runners now run JavaScript actions on Node 24 only; the temporary opt-out for Node 20 has been removed. Maintainers of JavaScript actions should update `runs.using` to `node24` and publish a new release, and workflow authors should upgrade to action versions that support Node 24.

Source: GitHub Changelog · September 23, 2026

### Proof of presence adds a stronger check before high-impact actions

GitHub Enterprise Cloud can now require an interactive re-authentication or multi-factor challenge before members take high-impact actions, extending sudo mode for enterprises. This public preview targets Entra ID-backed EMU enterprises and helps guard against stolen session cookies and long-lived tokens used in supply chain attacks.

Source: GitHub Changelog · September 24, 2026

### Canvases give Copilot chat a more tangible workspace

A new post on the GitHub Blog explores why chat isn't always the right interface for AI-assisted work, and introduces canvases as a way to give developers a more visual, persistent workspace for planning and iterating with Copilot instead of scrolling through a conversation.

Source: GitHub Blog · "When chat is the wrong UI"
