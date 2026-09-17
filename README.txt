VITALE HQ v23 — PWA
Preston North End · Lorenzo Vitale · 2030/31

Changes in v23:
- Aquino added to the squad as a 62 OVR ST/CAM Reserve, designated as the long-term development striker.
- Župan removed from the squad after leaving Preston.
- Lang retained because he remains at the club for now.
- PWA manifest, service worker and Home Screen icons included.
- Existing v22 save backup preserved as Preston_Vitale_2030-31_SAVE_v6.json.

IMPORTANT — INSTALLING ON iPHONE
A PWA must be served from HTTPS; opening index.html directly from the Files app is not enough.

Recommended free route: GitHub Pages.
1. Create a GitHub repository (for example: vitale-hq).
2. Upload the contents of this folder to the repository root: index.html, manifest.json, sw.js, icons/, and the save JSON.
3. In GitHub: Settings → Pages → Deploy from a branch → main → /(root) → Save.
4. Open the generated https://...github.io/... address in Safari on the iPhone.
5. Tap Share → Add to Home Screen → Add.
6. Launch “Vitale HQ” from the Home Screen. It will open in standalone app mode.

SAVE DATA
The dashboard stores live data in the browser's localStorage. Use Export Save regularly. On a new device/browser, open Vitale HQ and use Import Save to restore the JSON backup.
