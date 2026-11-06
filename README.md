# Fountain Gate Cricket Club Scorer v2.0

Offline-capable, single-page cricket scoring web app. No backend or login.

## Deploy to GitHub Pages
Upload all files to the ROOT of your existing `ddca-cricket-scorer` repository on the `main` branch. In Settings → Pages, choose Deploy from branch → main → /(root). The URL remains https://vhgajjar87-dev.github.io/ddca-cricket-scorer/ .

## Scoring
Create a match, add two opening batters and a first bowler under Players, then score deliveries. A bowler must be selected after each completed over. Select or add new batters and bowlers during the innings. Use Edit to correct deliveries and Summary to check reconciliation and print.

## Printing
Summary → Preview DDCA-style A4 scorebook / PDF → Print / Save as PDF. Set A4 landscape and check print preview. The sheet is an unofficial DDCA-style transcription layout, not a certified association form or exact reproduction of its preprinted stationery. The layout contains 15 batting/bowling scoring boxes and an over progression table. Longer innings may need print scaling or extra pages.

## Data / privacy
Current match is stored in localStorage only on the device/browser. Finish & clear deletes it. Export PDF before clearing. Clearing website data can erase it. Updates should retain the previous match under the same storage key.

## Known limitations
Not fully validated for unusual cricket dismissals, overthrow/short runs, multi-wicket balls, penalty allocation, rain-adjusted results, or every DDCA playing condition. Manual scorebook reconciliation is still required. The app is provided as a practical club-scoring aid, not an official scorer replacement.
