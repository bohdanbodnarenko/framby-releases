# Framby releases

Signed, notarized builds of [Framby](https://framby.app/), a
native macOS screen-capture app. This repository holds only what installed copies and the
download page need:

- `appcast.xml` — the Sparkle feed, served by GitHub Pages at
  <https://framby.app/appcast.xml>;
- `index.html` — the landing page;
- the DMGs, as assets of this repository's
  [Releases](https://github.com/bohdanbodnarenko/framby-releases/releases).

Framby's source is private. Framby is proprietary software, used under its End User License
Agreement (Help ▸ License Agreement in the app). Copyright © 2026 Bohdan Bodnarenko. All
rights reserved.

<!--
  Maintainer notes (this folder is prepared in the private source repository at
  Distribution/releases-repo/ and pushed here once, docs/12 §9 there):
  - Releases are created as drafts by the private repository's release workflow, with
    `gh release create --repo bohdanbodnarenko/framby-releases --draft`, using a
    fine-grained token scoped to this repository (Contents: read and write).
  - Publish the draft first, then commit the attached appcast.xml to main here. That push
    deploys the feed (.github/workflows/pages.yml).
-->
