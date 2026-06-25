# Holyoke Veterans Burial Ground Memorials — Project Handoff
*Last updated: June 2026*

## Live Maps
| Cemetery | URL | Entries | Repo | Status |
|----------|-----|---------|------|--------|
| Calvary | https://markwot-ops.github.io/calvary-map/ | 375 | calvary-map | Live |
| Elmwood | https://markwot-ops.github.io/elmwood-map/ | 44 | elmwood-map | Live |
| Landing Page | https://markwot-ops.github.io/holyoke-burial-ground-memorials/ | — | holyoke-burial-ground-memorials | Live |
| Forestdale | TBD | 0 | forestdale-map | Template ready |
| St. Jerome | TBD | 0 | — | Not started |
| Rock Valley | TBD | 0 | — | Not started |

## GitHub Account
- Account: markwot-ops
- All repos: https://github.com/markwot-ops

## Repo Structure
- `calvary-map` — main branch: index.html / photo-fix branch: JPG photos (some in main too)
- `elmwood-map` — main branch: index.html + photos
- `holyoke-burial-ground-memorials` — main branch: index.html (landing page)
- `forestdale-map` — main branch: index.html (template, no vets yet)

## Critical Rules — Never Violate
1. Calvary field name: `"story"` — NOT `"bio"`
2. Elmwood field name: `"bio"` — NOT `"story"`
3. Standard close (verbatim): "If you have further information about this veteran, please contact the City of Holyoke Veterans Graves Officer at (413) 322-5630 at 310 Appleton Street, 1st Floor, Holyoke, MA 01040."
4. No birth dates in narratives
5. No "is buried at Calvary Cemetery" line
6. Family connections: "may be related" only — never assert as fact
7. Never add flags (KIA, Purple Heart etc.) without stone or verified record confirmation
8. Search before writing narratives — stone → search → write
9. Always verify photo uploads via HTTP 200 at raw.githubusercontent.com
10. Never trust "I uploaded it" without confirmation

## Name Formatting Standard
- Format: `Last, First M. Jr.` — no second comma before suffix
- Titles after name: `Davitt, William Francis, Rev.` / `Moore, Edwin J.T., MD`
- Pre-formatted names (with comma) sort by first word = last name

## Photo Routing
- Calvary: photos in `main` branch root AND some in `photo-fix` branch
- All photo URLs use: `https://raw.githubusercontent.com/markwot-ops/calvary-map/main/[filename]`
- Elmwood: photos in `main` branch root

## Era Colors
| Era | Color |
|-----|-------|
| Civil War Era | #8B4513 (brown) |
| Spanish-American War | #CD853F (tan) |
| Peacetime Navy (1899–1916) | #2a6496 (steel blue) |
| World War I | #4682B4 (blue) |
| World War II | #2E8B57 (green) |
| Korean War | #9370DB (purple) |
| Vietnam | #DC143C (red) |
| Unknown Era | #666 (grey) |

## Open Calvary Items
- GPS retake needed: Domingo R. Colon, McGuines, Martin Jr., Williamson, Horrigan
- Placeholder GPS (42.1875, -72.6292038): Altenkirch, Allen S. Walker, and others marked ⚠️
- Photos still needed at cemetery: Bugbee, Cassidy, Concannon, Courtney, Davitt, Donoghue, Dowd, Felsentreger ×2, Fitzsimmons ×2, Fulponi, Gorman, Greaney, Gresh
- Baillargeon: no photo field, needs cemetery visit
- Anderstrom: portrait full-display fix pending
- Deduplication past O'Connor: not yet done
- Sidebar luminance highlight for selected vet: not started

## Open Elmwood Items
- RMDay stone: inscription unreadable, needs field revisit
- Unknown veterans: FMO, vetunknown3, vetunknown4, RMDay
- Hupfer: first name unconfirmed
- Josiah Rogers: veteran connection unconfirmed

## Session Backup Protocol
Every session must end with:
1. Final index.html uploaded to GitHub main — confirmed live
2. This HANDOFF.md updated in repo
3. Dated copy saved to permanent folder on local computer (not Downloads)

## Contact
Wayne D. Klinge, City of Holyoke Veterans Graves Officer
(413) 322-5630 | 310 Appleton Street, 1st Floor, Holyoke, MA 01040
mwotton@holyoke.org
