JCMath v3.3 — Installation & Use (Detailed Guide)

Files inside this ZIP:
- index.html         -> Main app (open this in Safari)
- manifest.json      -> PWA metadata for Add to Home Screen
- service-worker.js  -> Offline caching support
- icon.png           -> App icon used for home screen
- readme.txt         -> This file (detailed instructions)

How to install on an iPhone / iPad (Safari)
1. Save the ZIP to Files:
   - Tap the download link in Safari.
   - If Safari displays the ZIP contents instead of downloading, tap the Share icon (square with arrow) and choose "Save to Files". Pick a location under "On My iPhone" or "iCloud Drive".
2. Open the Files app and locate JCMath.zip in the folder you saved it to.
3. Tap the ZIP file to uncompress it. A new folder named "JCMath" will appear.
4. Inside the JCMath folder, tap the file named "index.html".
   - If iOS asks which app to open it with, choose Safari.
5. The app will open in Safari. To install as a home-screen app:
   - Tap the Share icon (bottom row) in Safari.
   - Choose "Add to Home Screen".
   - Confirm the name "JCMath" and tap "Add".
6. The app appears on your home screen and opens full-screen (standalone) like a normal app. It will work offline after the first load (service worker caching).

Add-to-Home-Screen banner:
- A top-of-screen blue banner will appear the first time you open the site in Safari.
- It instructs: "Press the Share button, then find Add to Home Screen and press it.".
- The banner stays visible until you dismiss it (tap the X); it won’t reappear after dismissal or install.

Troubleshooting & Tips
- For best install behavior, host the files on GitHub Pages (HTTPS) and install from that URL.
- If 'Add to Home Screen' is greyed out, ensure you opened index.html with Safari (not inside another app).
- If the sandbox (Minecraft-like) feels sensitive while panning, try slow drags to pan and short taps to add/remove blocks.
- To update the app later: replace files and re-install if needed.

Enjoy JCMath!