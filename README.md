# A plural history of AI ethics, 1950–2025

A teaching map of AI ethics across 75 years, in seven tabs (keys 1–7): problems, lecture anchors 1950–2010,
four questions, continuity and change, 2010–2025 (by lineage or by track), all entries, and notes on the pack.
Hover or focus a name for the full reference and reading note.

**Printing.** Tab v has two buttons. *Print handout* gives 8 A4 landscape pages: tabs i–v and a short list of
the 38 entries (date and title). *Print everything* (or the browser's own Print) adds the full entries table and
About, about 19 pages. Add `?print=handout` to the address to open the handout straight in print preview.

**Used in:** Lecture 6, AI Ethics (Critical Perspectives on Data & AI).
**Live:** https://goto4711.github.io/ai-ethics-histories/

## Files
index.html — generated; do not edit by hand.

## Rebuilding
The page is built by `lecture/build_lecture_pack.py` in the ai-ethics-history project from the post-2010 CSV,
`lecture/pre2010_ai_ethics_history.html`, `What_this_timeline_cannot_show.txt`, `data/out/ancestors.json` and
`reading/ancestor_claims.csv`. Run `python3 lecture/build_lecture_pack.py`, then copy
`lecture/ai_ethics_history_1950_2025.html` here as `index.html`. It opens from disk and needs no network.

## Companion: Field Memory in AI Ethics
`field-memory/` holds a companion site, linked from the masthead. It shows which venue groups in AI ethics remember which works of computer ethics (2015–2025), and how four canonical claims travel through later papers.
Live: https://goto4711.github.io/ai-ethics-histories/field-memory/

The site shows aggregates only; no codes for individual papers are published. The counts come from a draft article and may change.

Rebuild with `python3 claimmap/src/build_site.py --public` in the ai-ethics-history project, then copy `claimmap/public/field-memory/` here as `field-memory/`. The page is self-contained apart from `fig1_nissenbaum_routes.png`.
