AI App Builder - starter PWA

Files:
- index.html: app UI and Gemini integration
- manifest.webmanifest: installable web app metadata
- sw.js: offline shell cache

Important:
1. This is a starter web app, not yet a published Play Store APK.
2. It requires a Gemini API key entered in Settings. Do not send your key in chat or commit it to a public repository.
3. This prototype calls Gemini from the browser. The key is stored in this browser's local storage and is visible to anyone with access to the device/browser profile. For a production app, move API calls to a secure backend with server-side secrets and authentication.
4. For ChatGPT-based external updates, export/download the project or app HTML, have ChatGPT revise it, then import an updated project backup or replace the app HTML through a deployment workflow. A direct ChatGPT-to-app secure integration is not configured in this starter.
5. Host the folder on HTTPS to install as a PWA. Android Chrome: open the HTTPS site > browser menu > Install app / Add to Home screen.