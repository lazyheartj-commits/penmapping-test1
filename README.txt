PEN WALKER FOR ANDROID

Option A: Install as an app from a web address (no Android Studio)
  1. Upload the contents of the "pwa" folder to any HTTPS host (GitHub Pages, Netlify, Cloudflare Pages).
  2. On the phone open that address in Chrome, allow Location, then menu > Install app (or Add to Home screen).
  GPS needs HTTPS, so it will not work from a file opened off the phone's storage.

Option B: Build an APK
  1. Install Android Studio. Choose File > Open and select the "android" folder.
  2. Let Gradle sync, then Build > Build APK(s). Or plug in the phone with USB debugging and press Run.
  3. The first launch asks for location permission. Exports go to the phone's Downloads folder.
  The app files are bundled inside the APK, so it works with no signal in the field.
