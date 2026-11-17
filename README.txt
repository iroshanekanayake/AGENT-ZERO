AGENT ZERO — FILES ONLY EDITION

Files in this ZIP (all at the same level):
- index.html
- manifest.webmanifest
- sw.js
- README.txt

No folders are included.

This is a standalone Phase 1 UI prototype. It includes:
- Dashboard
- Mission creation and local persistence
- Agent enable/disable controls
- Human approval / rejection demo
- Activity log
- Settings and local data reset
- PWA manifest and service worker

Important:
- This version has no real AI API connection yet.
- Approval changes local demo state only; it does not execute agents.
- For PWA installation, host these files on HTTPS (for example, GitHub Pages).
- Opening index.html directly from a file manager may not enable PWA installation or service worker offline support.
- Browser localStorage is used for prototype data. Clearing browser data may erase missions.
