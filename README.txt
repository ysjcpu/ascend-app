ASCEND — iPhone Home Screen Web App

CONTENTS
- index.html: the app
- manifest.webmanifest: install/display settings
- service-worker.js: offline caching
- icons/: app icons

INSTALL ON IPHONE
1. Upload the CONTENTS of this folder to a static website host that serves HTTPS.
   The website should open index.html at its root.
2. On your iPhone, open that HTTPS website in Safari.
3. Tap Share (the square with the up arrow).
4. Choose Add to Home Screen.
5. If shown, enable Open as Web App, then tap Add.

IMPORTANT
- iOS requires a secure HTTPS website for service workers and reliable PWA installation.
- Opening index.html directly from Files is useful for a quick preview, but it will not install as a full offline web app.
- Tasks are saved in the browser's local storage on this device. Clearing Safari website data can erase them.
- The app does not require API keys or an account.
