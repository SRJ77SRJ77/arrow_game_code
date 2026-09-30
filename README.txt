ARROW CHAIN - app package

FILES
 index.html          the game
 manifest.webmanifest app name, colors, icons
 sw.js               makes it work offline
 icon-192.png, icon-512.png

STEP 1 - Put it online (free)
 Upload this whole folder to Netlify Drop (app.netlify.com/drop) or GitHub Pages.
 You get a link like https://arrowchain.netlify.app

STEP 2 - Test as an app on your phone
 Open the link in Chrome on Android > menu > "Install app".
 It opens full screen like a real app.

STEP 3 - Make the Play Store file (.aab)
 Go to pwabuilder.com, paste your link, choose Android, and download the package.
 (It makes a Trusted Web Activity, which uses Chrome, so the animal voice keeps working.)

STEP 4 - Publish
 Google Play Console (one-time $25) > create app > upload the .aab
 You also need: app icon, screenshots, short description, and a privacy policy link.
