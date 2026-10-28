# CrewScheduler product pages

Standalone bilingual static pages copied by Hugo without the blog theme, subscription form, comments, or analytics templates:

- `/crewscheduler/` — product overview; synthetic roster screenshot
- `/crewscheduler/support/` — support instructions and contact email
- `/crewscheduler/privacy/` — full policy, version 1.1, October 28, 2026

Shared CSS and screenshot are hosted locally. No scripts, upload forms, remote fonts, or App Store download links are included. The policy applies to these product pages and the app, not unrelated blog/newsletter services. Support suggestions may inform feature planning; diagnostic attachments remain limited to troubleshooting. Hosting/network providers may process connection logs.

## Validation

Built with Hugo 0.145.0 and the existing pinned Stack v3.30.0 module. A recursive comparison against the unmodified baseline build showed only the added `crewscheduler` directory. All three HTML pages have English sections and their local asset/navigation targets exist. The product page was visually inspected in a local browser.

## Release

Review and merge the PR when ready. After Netlify publishes, verify all three production URLs and the English anchors over HTTPS before changing App Store Connect or in-app policy/support URLs. This branch does not change DNS, existing blog paths, deployment configuration, or the iOS app. The existing policy/support URLs remain in use until migration is verified.
