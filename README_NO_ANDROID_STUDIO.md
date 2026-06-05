# Wellington Info App - Android Studio ছাড়া APK বানানোর নিয়ম

এই project সরাসরি Android Studio ছাড়াই GitHub Actions দিয়ে APK build করতে পারবে।

## নিয়ম

1. GitHub.com এ login করুন
2. New repository তৈরি করুন, যেমন: `WellingtonInfoApp`
3. এই ZIP unzip করে সব file repository-তে upload করুন
4. GitHub repository-তে **Actions** tab খুলুন
5. **Build Android APK** workflow select করুন
6. **Run workflow** চাপুন
7. Build শেষ হলে নিচে **Artifacts** থেকে `WellingtonInfoApp-debug-apk` download করুন
8. ZIP unzip করলে `app-debug.apk` পাবেন

## App info

- Website URL: https://wellington-info.com/
- App Name: Wellington Info
- Package: com.wellington.info
- WebView login/session supported
- File upload supported
- WhatsApp, phone, email links external app-এ open হবে

## Note

Debug APK ফোনে install করা যায়, তবে Play Store upload করার জন্য signed release APK/AAB লাগবে।
