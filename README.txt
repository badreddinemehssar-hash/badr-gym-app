BADR TRAINING OS — NEW CUSTOM TRACKER
====================================

WHAT'S INCLUDED
- index.html: fully functional app
- manifest.webmanifest, icon-192.png, icon-512.png, sw.js: installable website/PWA files
- Your complete V-taper plan (A/B/C/D) and two flexible CrossFit sessions are preloaded.
- No previous tracker code or sample workout history has been imported.

GETTING STARTED
1. Open the standalone Badr_Training_OS.html file, or upload the contents of this folder to a static HTTPS website.
2. Choose a workout and log weight/reps/RIR. The session autosaves after each change.
3. Press Finish & save to preserve the session in History.
4. Open Settings and download a full JSON backup regularly.

FOR IPHONE AND LONG-TERM STORAGE
The recommended setup is to publish this folder to a stable HTTPS address (Netlify, GitHub Pages, or an equivalent static host). Open that URL in Safari and use Share > Add to Home Screen to install it like an app. YouTube technique links require an internet connection; the rest works offline after the first successful page load on the hosted PWA.

Using a downloaded HTML file also works in many desktop browsers, but browser storage for local files can be restricted or cleared — particularly on iOS. Do NOT rely on local-file browser storage as your only backup. Export the JSON and save to iCloud Drive/Files.

UPDATING THIS SAME APP
- Keep the same website address/origin and the same local-storage key ('badr.training.os.v1').
- Replace index.html (and any other changed assets) at the existing website location.
- The app data lives in browser local storage; replacing HTML/JS does not intentionally clear it.
- ALWAYS download a JSON backup before installing updated versions. If switching domains/browsers/devices, restore that JSON via Settings.
- Updates with a different database schema require migration logic and should preserve workout history.
- There is no cloud account or automatic cross-device synchronization in this version.

WHAT IS TRACKED
- Editable sessions and exercise library, including difficulty, technique cues and YouTube link/search
- Lift-by-lift sets, weights (kg), reps, RIR, rest timer and automatically loaded previous weights
- CrossFit WOD, score, duration, scaling, RPE and notes
- Completed workout history, progress graphs by exercise, weekly training counts
- Bodyweight and waist measurements
- Full JSON backups/restore; CSV workout export

CURRENT PERSONALISATION
Name: Badr
Height: 190 cm
Recent reference weight: ~92 kg (estimate, not a recorded weigh-in)
Protein target: 160 g/day
Preferred schedule: 4 gym sessions + 2 CrossFit classes, with no fixed weekdays
Return-to-gym mode: ON initially, ~65% of prescribed working sets

Privacy: No data is transmitted by this app. External YouTube links open YouTube in your browser.
