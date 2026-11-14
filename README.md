# FAC Historical Archive — Homepage Starter

A static, mobile-responsive homepage for the First Alliance Church of Erie Historical Archive, aligned with FAC's 2026 brand guidelines.

## Upload to GitHub Pages

Upload `index.html`, `css/`, `js/`, and `assets/` to the root of your GitHub repository. In Settings → Pages, select Deploy from a branch, `main`, `/ (root)`.

## Before publishing

1. Replace the typographic placeholder in the header with the **approved FAC logo SVG** from FAC's Communications asset library. Do not recreate or distort the official mark.
2. Add your own approved historical images to `assets/images/` with these names: `hero-archive.jpg`, `collection-photographs.jpg`, `collection-documents.jpg`, `collection-publications.jpg`, `featured-logo-history.jpg`.
3. Remove the visible image placeholder labels once each image has been added, and replace the hero's placeholder accessibility label with a real description.
4. Confirm historical dates against primary archival records before presenting the timeline as a complete history. The starter's three milestones are drawn from the FAC 2026 brand guide.
5. Replace 'Collection coming soon' with real collection links once the records and pages exist.
6. Review permissions, privacy, copyright, and especially photos or records involving minors before publishing.

This is a frontend starter; no database, full-text search, or XML/TEI archive is implemented yet. You can add collection pages and structured metadata later.

## Design tokens

FAC Navy `#1C2F4D`; Light Blue `#A2B8E2`; Gray `#D2D5DD`; Dark Neutral `#0F172A`; Light Neutral `#F9FBFF`. Uses Figtree, the brand-approved substitute for Avenir.


## Additional pages
- `history.html` — overview of FAC's history
- `collections.html` — browse collection categories
- `photographs.html`, `documents.html`, `publications.html` — collection landing pages
- `timeline.html` — source-supported milestones
- `stories.html`, `logo-history.html` — features and an introductory exhibit
- `contribute.html` — contribution information
- `record-template.html` — illustrative item detail layout, not a real record

The site uses ordinary HTML pages and relative links, so it works on GitHub Pages without a build process. Replace the text-only logo stand-in with the approved FAC logo asset before publishing. No actual archive items have been published in this starter.
