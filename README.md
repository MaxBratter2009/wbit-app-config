# WBIT 95.3 "The Bite" — app config

This repo hosts **`station.json`**, the live content for the WBIT app
(schedule, shows, polls, events, announcements, USN links, and stream info).

**Edit `station.json` here → the app picks it up on next launch. No app update needed.**

Tips:
- It's JSON: keep every value in `"double quotes"`, commas between items, no trailing comma.
- `day`: 0=Sun, 1=Mon, 2=Tue, 3=Wed, 4=Thu, 5=Fri, 6=Sat. Times are 24h `"HH:MM"`.
- Leave something blank with `""` (empty text) or `[]` (empty list).
- After editing, use jsonlint.com or GitHub's own preview to confirm it's still valid.
