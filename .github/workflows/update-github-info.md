---
name: update-github-info
description: Refresh Mona's GitHub information page from the latest GitHub news and changelog.
on:
  schedule:
    - cron: "0 9 * * *"
  workflow_dispatch:
permissions:
  contents: read
strict: true
network:
  allowed:
    - github.blog
    - github.com
    - api.github.com
tools:
  github:
    mode: local
    toolsets: [repos]
  edit: true
  web-fetch: {}
safe-outputs:
  create-pull-request:
    allowed-files:
      - site/content/github-info.md
---

# Update GitHub Info

Read `notes/mona-notes.md` and use the GitHub repository API tools to read any
repository guidance or relevant reference files. Fetch and review:

- https://github.blog/latest/
- https://github.blog/changelog/

Update `site/content/github-info.md` with accurate, useful GitHub information
for Mona, following the repository guidance and the existing content style.

Use the configured `create-pull-request` safe output to open a pull request for
Mona to review. Do not write directly to the default branch. If the sources do
not provide a substantive, accurate improvement, call `noop` with a short
reason instead.