SKILLLINK NG — ANDROID APK PREPARATION

Included:
- index.html: your SkillLink NG app, adapted for installable web app use
- manifest.webmanifest: app name, display mode and icons
- service-worker.js: basic offline caching
- icon-192.png and icon-512.png: app icons

IMPORTANT LIMITATIONS:
This is still a frontend prototype. Listings are saved only in the browser/device local storage.
The sign-up screen is a demo profile, not secure online authentication. No shared cloud database,
admin panel, payment system, or real review system is connected. Do not collect real passwords
or sensitive user information with this prototype.

NEXT:
1. Upload the contents of this folder to a static HTTPS host (for example GitHub Pages or Netlify).
2. Open the published HTTPS address on your Android phone and test it.
3. Use PWABuilder (https://www.pwabuilder.com/) to package the hosted PWA for Android.
4. Follow its Android package/signing instructions. Keep the signing key safe; it is needed for
   future app updates.
5. Test the APK on your phone before sharing it.

The APK itself is not included yet because it must be packaged from a hosted HTTPS app and signed.
