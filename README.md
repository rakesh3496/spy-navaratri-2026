# SPY - Sri Pentamamba Youth / Sharan Navaratri Celebration 2026

## Architecture
- Android: package this web app as an APK (Capacitor/TWA).
- iPhone/iPad: use the same GitHub Pages PWA and add it to the Home Screen.
- Data: Firebase Authentication (anonymous) + Cloud Firestore.
- The app does not use localStorage for committee transaction data.

## Firebase
The HTML contains the Firebase web configuration for project `spy-navaratri-2026`.
Enable Firebase Authentication -> Anonymous and use the supplied Firestore rules.

## Committee login
Shared temporary committee password: `spy@2026`
Admin password: `spy@202627`
Change these in `index.html` before distributing if needed.

## Important
The Firestore rules are intentionally simple for this short-lived committee app. Any authenticated anonymous user can read/write the listed collections. This is suitable only for the temporary, low-security use case described by the committee.

## Features
- Unique committee usernames with shared password
- Centralized collections, expenses, feedback, calendar notes and profiles
- Live Firestore synchronization
- Dashboard metrics
- PDF financial report download with date filters
- PWA manifest/service worker
- No target amount feature
