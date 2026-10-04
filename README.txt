FORM — Athletic Training PWA

Files: index.html (app), manifest.webmanifest (install metadata), sw.js (offline cache), icon.svg (app icon).

IMPORTANT iPHONE SETUP
PWA installation and service workers require HTTPS (or localhost). Opening index.html directly from Files is not enough for reliable offline installation.
1. Upload the contents of this folder to a static HTTPS host you control.
2. Open the HTTPS URL in Safari while online.
3. Tap Share > Add to Home Screen.
4. Launch the installed app once online so the service worker caches the app shell.
5. Test by enabling Airplane Mode and reopening it.
6. In Settings, export a JSON backup regularly.

DATA
Logs, check-ins and settings use IndexedDB on this device/browser origin. The app code does not upload workout data. Clearing website data, deleting the app, changing the site origin, or losing the device may make records unavailable. Restore JSON backups from Settings.

The app is designed to work offline after the first successful online launch from its HTTPS address. Training guidance is general information; adapt exercises to your ability and stop if you experience sharp pain.
