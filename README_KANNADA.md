# Mails Sorting RMS Android App

ಈ Android App ನಿಮ್ಮ Google Apps Script Web App ಅನ್ನು WebView ಒಳಗೆ ತೆರೆಯುತ್ತದೆ. ಇಂಟರ್ನೆಟ್ ಸಂಪರ್ಕ ಅಗತ್ಯ.

## GitHub ಮೂಲಕ APK Build
1. ಈ project‌ನ ಎಲ್ಲ ಫೈಲ್‌ಗಳನ್ನು `appggkaniyuru/mails-sorting-rms` repositoryಗೆ upload ಮಾಡಿ; `.github/workflows/android.yml` ಫೈಲ್ ಕೂಡ ಸೇರಿರಬೇಕು.
2. `Actions` tab ತೆರೆಯಿರಿ.
3. `Build Mails Sorting RMS APK` workflow ಆಯ್ಕೆಮಾಡಿ.
4. `Run workflow` ಒತ್ತಿ.
5. Build ಮುಗಿದ ನಂತರ workflow run ತೆರೆಯಿರಿ; `Mails-Sorting-RMS-APK` artifact download ಮಾಡಿ.
6. ZIP ತೆರೆದು `app-debug.apk` ಅನ್ನು Android ಮೊಬೈಲ್‌ಗೆ ಕಳುಹಿಸಿ install ಮಾಡಿ.

## ಮುಖ್ಯ
- App ಬಳಸಲು ಇಂಟರ್ನೆಟ್ ಬೇಕು.
- Google Apps Script Web App URL `MainActivity.kt` ಫೈಲ್‌ನಲ್ಲಿ ಇದೆ.
- ಈ repository Public ಆಗಿರುವುದರಿಂದ ಇಲ್ಲಿ PIN, password ಅಥವಾ ಖಾಸಗಿ API key ಸೇರಿಸಬೇಡಿ.
