# Browser Scripts Index

[![Master Index](https://img.shields.io/badge/Master%20Index-All%20Repositories-purple?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Start-Here)

An index of browser **userscripts** I maintain — small JavaScript bits
that run inside [Tampermonkey](https://www.tampermonkey.net/),
[Violentmonkey](https://violentmonkey.github.io/), or
[Greasemonkey](https://www.greasespot.net/) to fix, declutter, or
augment specific websites.

**Last Updated:** October 2026

Each entry below points at the source repo, where you'll find the
script itself, screenshots, and a one-click install link.

## Index

| Script | Site | Purpose | Repo | Direct install (v2) |
|---|---|---|---|---|
| **AliExpress — Hide Combo Deals (with Toggle)** | aliexpress.com | Excludes search results that are only available via "Max Combo" / bundle deals, where the headline price is conditional on buying multiple units. Adds an inline counter and Show/Hide toggle above the grid. | [danielrosehill/AliExpress-No-Combo-Deals](https://github.com/danielrosehill/AliExpress-No-Combo-Deals) | [`aliexpress-no-combo-v2.user.js`](https://raw.githubusercontent.com/danielrosehill/AliExpress-No-Combo-Deals/main/aliexpress-no-combo-v2.user.js) |

## Install (any script)

1. Install a userscript manager — **Tampermonkey** is recommended
   ([Chrome](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) /
   [Firefox](https://addons.mozilla.org/firefox/addon/tampermonkey/)).
2. Click the **Direct install** link in the table above. Tampermonkey
   intercepts `.user.js` URLs and shows an install prompt.
3. Reload the affected site.

All scripts here include `@updateURL` / `@downloadURL` headers, so
Tampermonkey will pull new versions automatically.

## Adding a new script

1. Create a separate public repo for the script (one repo per script —
   keeps issues, screenshots, and version history isolated).
2. Add a row to the table above pointing at the repo and the raw
   `.user.js` URL on `main`.

## Licence

Index content: MIT. Each linked script repo carries its own licence
(typically MIT).
