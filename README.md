# ClientPreviews

Static client-facing preview and approval artifacts. This repository contains presentation files, not the private engagement record or application source.

| Path | Content |
|---|---|
| `approval/` | Approval presentation |
| `seo/` | SEO presentation |
| `arc-d23894c5/` | Named ARC preview snapshot |
| `index.html` | Minimal root entry with a noindex directive |

There is no package manifest or required build step. Open the relevant HTML file locally, or serve this checkout with a local static HTTP server when relative assets require it. Check linked assets and the exact rendered preview before publishing.

Treat every hosted file as potentially public. A noindex directive is not access control: credentials, private correspondence, and PII do not belong here. Keep those in the private owning engagement workspace. A local commit is not proof that a preview is published or approved; verify hosting and obtain authority for any push/publication. Nothing publishes to kidsister.co without Ashley's approval of the exact preview.

Maintain dated/named artifacts deliberately; do not overwrite an approved presentation or change a client-designed asset by assumption. This clone can be inspected without the larger D: workspace; recover engagement context from the authorized project owner only when needed.
