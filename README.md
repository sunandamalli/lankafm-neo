# LankaFM 2026 Neo - APK build

## Option A: GitHub (Android Studio ona naha)
1. github.com ekak account eka hadala, aluth repository ekak create karanna (name: lankafm-neo).
2. Me folder eke files tika (www, package.json, capacitor.config.json, .github, .gitignore) upload karanna. Branch eka "main" wenna ona.
3. Repository eke "Actions" tab ekata gihin "Build APK" run wenakan inna (minutes 5-8).
4. Run eka iwara unama passe page eke yata thiyena "Artifacts" eken LankaFM-Neo-APK download karanna. Zip eka ethule app-debug.apk thiyenawa.
5. APK eka phone ekata damma install karanna ("Install unknown apps" allow karanna ona).

## Option B: Computer eke (Node 18+, Android Studio ona)
    npm install
    npx cap add android
    npx cap sync android
    npx cap open android
Android Studio eke Build > Build APK(s) denna.

## Wenas karanna
- App eke UI / stations: www/index.html
- App name / id: capacitor.config.json
