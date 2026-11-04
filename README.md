# RimDash — Premium Arcade Racing Prototype

RimDash is an original, mobile-first arcade racing prototype with a cinematic dark racing website. This source includes the playable browser build and a basic Android WebView wrapper.

## Implemented in this prototype
- Three-lane traffic racing with progressive speed and traffic spawn pressure
- Nitro reserve, boost control (Shift / Arrow Up / touch N₂O button), and charge-cell pickups
- Near-miss bonus scoring, collision/end-run flow, pause/resume, sound effects, distance, local best score
- Responsive website, game overview, privacy and support pages
- Android WebView starter project with synchronized game assets

## Not implemented / not to be advertised as live
- Online accounts, cloud saves, secure online leaderboards, multiplayer, in-app purchases, real rewards, ads/AppLovin MAX
- Signed production APK/AAB, Play Store listing, store approval, device QA

## Preview locally
Open `index.html` in a modern browser. For best mobile testing, host the folder on a static web server rather than using a file preview app.

## Android
Open the `android` directory in Android Studio and build/run on a physical device. Confirm package ID, app icon, splash screen, permissions, signing, privacy disclosures, and performance before release. The WebView wrapper is a starter, not a release-verified Android app.

## Deployment
Upload the website files to a GitHub Pages repository. Replace the placeholder in `app-ads.txt` only with the exact seller entry supplied by the actual advertising account after setup. Do not claim ads.txt or AppLovin verification until the provider confirms it.
