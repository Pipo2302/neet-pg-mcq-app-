# NEET-PG MCQ App v3

Premium-style Flutter MCQ practice app using the included offline MCQ bank.

## v3 upgrades
- Four-tab navigation: Home, Subjects, Progress, Settings
- Dark/light mode
- Daily MCQ target with local persistence
- Custom tests: 25 / 50 / 100 questions
- Subject and topic filters for custom tests
- Countdown timer
- Question palette and review/bookmarks
- Search across question, subject, topic and explanation
- Wrong-question revision
- Progress and subject coverage analytics
- Offline-first storage with SharedPreferences

## Build
```bash
flutter pub get
flutter build apk --release
```
APK will be generated at `build/app/outputs/flutter-apk/app-release.apk`.
