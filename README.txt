My First English Stories — PWA starter package

Included:
- index.html: the interactive book
- manifest.webmanifest: app name, theme, icons
- service-worker.js: basic offline caching
- icons/: app icons

Important:
1. This folder must be uploaded to a web host that serves HTTPS (for example GitHub Pages or Cloudflare Pages). Opening index.html directly from your computer does not enable installation/offline features.
2. This is a public-link prototype. It does not implement user accounts or private access. Do not upload private or paid stories until access control is added.
3. Browser support and install steps vary. On Android, open the URL in Chrome and use Install app / Add to Home screen. On iPhone, open in Safari, tap Share, then Add to Home Screen.
4. The browser's built-in speech synthesis may need internet or installed voices and can vary by device.

Updated version: quiz questions appear one under another; speech rate set to 0.90 (medium, child-friendly pace).

Audio update: default English speech rate is now slower (0.65) for young beginners. Service worker cache version updated to v3-slow.


Very slow audio update: speech synthesis rate is set to 0.45 for beginner children. Replace index.html and service-worker.js in the GitHub repository, then hard-refresh the site.
