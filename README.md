# JEE FIGHT — Final Source Build

Private, offline-first Android app for personal JEE preparation.

## Included
- Dark cyberpunk/neon rounded UI.
- 5-second intro and live countdown to the configurable target date.
- NIT / JEE MAINS and IIT / JEE ADVANCED entry cards.
- Mathematics / Physics / Chemistry tracker.
- Chapter and topic hierarchy with persistent completion state.
- Subject-scoped search with partial matching and full hierarchy paths.
- Chapter `+` for custom topic/folder creation.
- Topic pages with notes and notebook-image URI storage.
- Chapter shortnotes and PYQ state.
- Automatic chapter, subject and overall completion percentages.
- CLOCK: stopwatch, persistent study time, local alarm scheduling and stats.
- Calendar with persistent date task/notes.
- Today's Mission hydration and push-up checklists; state is date-specific.
- Progress dashboard.
- Settings: display name, countdown target, optional PIN, backup/export and restore/import.
- Local notification channel and alarm receiver.
- JSON backup format.

## Data safety
Tracker data is serialized as JSON in SharedPreferences. Completion flags, custom topics, notes, folders and topic notes are preserved across app restarts. Export a backup before major changes or reinstalling the app.

## Build
Open this folder in Android Studio and let Gradle sync. Then run the app on an Android 8.0+ device. A release APK can be generated from Android Studio's Build menu.

## Syllabus note
The included seed database is a practical JEE Main 2026 / JEE Advanced 2026 baseline. Official 2027 syllabi should be checked when released and the local database updated if anything changes. The official JEE Main syllabus page is maintained by NTA; JEE Advanced 2026 states its syllabus matched 2025.
