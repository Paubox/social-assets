# Paubox social-assets

Public host for social graphics used in Paubox campaigns. Image URLs from this repo are referenced in HubSpot bulk social uploads, LinkedIn/X posts, and other places that need a reachable public image URL.

## Do not rename or delete files after they're referenced

Once an image URL is in a published social post or a scheduled upload, changing or removing the file breaks the post silently. Add new files; don't edit old ones.

## Naming convention

`RPT.<YYYYMM>.<ReportShortName>-<asset-type>-<slug>[-x].png`

- `RPT.202602.EmailSecurity-stat-85-breach.png` — stat graphic (LinkedIn/square)
- `RPT.202602.EmailSecurity-article-s1-dmarc-x.png` — article graphic (X/Twitter crop)

## Raw URL format

```
https://raw.githubusercontent.com/Paubox/social-assets/main/<filename>
```
