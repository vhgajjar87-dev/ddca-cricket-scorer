DDCA CLUB SCORER — INSTALLATION

This is a static Progressive Web App (PWA), not an App Store application.

TO USE ON IPHONE
1. Upload the contents of this folder (not just the ZIP) to an HTTPS static website host such as GitHub Pages or Netlify.
2. Open the hosted HTTPS URL in Safari on your iPhone.
3. Tap Share > Add to Home Screen > Add.
4. Open DDCA Scorer from your Home Screen. Visit the site once while online to cache files for later offline use.

You can also test index.html in a desktop browser, but iPhone installation and offline caching require HTTPS hosting.

PRIVACY AND RECOVERY
- The current match is saved only to localStorage on the device/browser.
- No analytics, cloud database, account, or external API is included.
- Finish Match permanently removes the local match data.
- Private browsing, clearing Safari website data, or removing the app may also erase it.
- Export/copy your summary before clearing.

IMPORTANT LIMITATIONS (V1)
- This is a practical scoring prototype, not an officially certified DDCA scorer.
- Advanced laws (multiple wickets, no-ball/wide wickets, penalties, retirements, complex run-outs, super overs, declarations, DLS, and scorebook-specific notation) are not comprehensively implemented.
- Editing earlier deliveries recalculates totals, but strike changes and bowling assignments should be checked after edits.
- Only one current match is retained. No history or cloud synchronization.
- Test with a practice innings before relying on it for an official game.
