WATERLINE V61 — interaction/session fix

IMPORTANT: keep the public/ directory. server.js serves public/index.html, public/app.js and public/style.css.

Start:
npm install
npm start

V61 fixes:
- Restores correct public/ deployment structure.
- Adds reconnect/session resume using localStorage.
- Keeps a disconnected room alive for 10 minutes for mobile/browser reconnects.
- Keeps V60 interaction and modal fixes.
