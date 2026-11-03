Mentor AI - app package
=======================
index.html is a complete standalone web app (no build step).

First run: open the menu (☰), paste your Anthropic API key at the bottom, then chat.
Get a key at https://console.anthropic.com

Make an APK (easiest options):
1. Capacitor: npm i @capacitor/core @capacitor/cli @capacitor/android
   npx cap init Mentor com.example.mentor --web-dir=.
   npx cap add android && npx cap open android  (Build > Build APK in Android Studio)
2. Or upload this folder to a no-code "website to APK" builder (e.g. Median, WebIntoApp, AppsGeyser).

Note: the key is stored only on the device. For a public app, route requests through your own server instead of shipping a key.
