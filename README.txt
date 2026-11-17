AGENT ZERO — FILES ONLY EDITION (PHASE 1.1)

Files in this ZIP (all at the same level; no folders):
- index.html
- manifest.webmanifest
- sw.js
- README.txt

Included:
- Dashboard and mission creation
- Local mission persistence
- Agent enable/disable controls
- Human approval / rejection workflow
- Required Final Security Audit page
- Seven security checks: code, secrets, data protection, permissions, execution safety, dependencies, authentication
- Mission completion is blocked unless every required check is marked Pass
- Activity log and local reset
- PWA manifest and service worker

Important:
- This is a frontend prototype; it does not perform real vulnerability scans.
- Security check results are entered by the user after review. They are not automatically verified.
- There is no real AI API connection or agent execution yet.
- Approval and completion states are local demo states only.
- For PWA installation, host on HTTPS (for example, GitHub Pages).
- Opening index.html directly from a file manager may not enable service worker/offline/PWA features.
- Data is stored in this browser's localStorage. Clearing browser data may erase it.
- Do not enter real API keys or secrets into this prototype.
