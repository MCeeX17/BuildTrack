# BuildTrack — a Mo2IT Incorporation production
Construction site management: workers, tools, daily attendance, boss/supervisor approvals. **In development.**

## Setup
1. Firebase console → Authentication → enable **Email/Password**. Make sure the master admin account (UID `1I1chNkjsCf09ysvgJE999HgU4I2`) exists.
2. Firestore Database → create database, then paste `firestore.rules` into Rules and publish.
3. Authentication → Settings → Authorized domains → add `<your-username>.github.io`.
4. Push these files to a GitHub repo → Settings → Pages → deploy from `main` / root.
5. Log in as the admin → Team → add supervisors (they get a password reset email).

Files: index.html, manifest.json, sw.js, logo.png, icon-192.png, icon-512.png, firestore.rules
