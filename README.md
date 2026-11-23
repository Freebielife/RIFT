# Rifty Observatory

## О проекте / токене

RIFT powers Rifty Mining on TON: mining rewards, station upgrades and module crafting, with a mintable supply and no fixed maximum.

Самоописание из метаданных токена; заявления проекта не проверены независимо.

Источники (проверены 2026-11-23):

- <https://tonapi.io/v2/jettons/EQBvpKspmZ6Wk6Hc9VZptfHdh2HPoWFVTQi9oZEIcXl3_5kr>

Generated from https://github.com/Freebielife/TON-Observatory-Template.

Run python3 -m scripts.refresh_observatory; python3 build.py; python3 verify.py.
Publish index.html in TON Sites only after independent on-chain verification.
Initial on-chain collection and its per-section status are recorded in data/snapshot.json.
Only native TON swap pairs supported. Locks, staking and custom project NFT badges are configured through project.json and verified against TonAPI.
Configure your GitHub workflow scheduler before launch.

Foundation version: 1.3.0. Holders show 10, expandable to top 20.
`project.json` is the per-project specification. Contract/pool/precision changes require regenerating from the factory; do not reuse another token's snapshot.
Run `python3 build.py` for an atomic bundle and `build/report.json` size report.
No external fonts, scripts or images are needed to render the saved page. Fresh data checks and manual wallet lookups require network access.
Cloudflare dispatch registration and GitHub repository access remain separate deployment steps. No credentials go into HTML.

Branding: owner-supplied image used for both hero logo and section flags, as explicitly requested.
Website: https://rifty.run.place/
Community: https://t.me/riftycommunity
Bot: https://t.me/riftycoinbot
