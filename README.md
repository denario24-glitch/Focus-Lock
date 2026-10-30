# FOCUS LOCK Web v0.6 — PWA starter

A responsive, guest-first web app prototype intended to run on modern mobile and desktop browsers.

## Included
- Responsive luxury-dark interface
- Guest-first start
- Focus timer presets (25 / 50 / 90)
- Six focus modes
- Daily goals and completion checkboxes
- Daily completed-session metrics
- Local browser storage
- PWA manifest and service worker for install/offline shell support

## Run / deploy
This is a static website. Upload the contents of this folder to a static HTTPS host. Service workers and PWA installation require HTTPS (localhost is also suitable for development).

## Install
- iPhone/iPad: open the HTTPS site in Safari, tap Share, then Add to Home Screen.
- Android: open the HTTPS site in Chrome and use Install app / Add to Home screen when offered.

## Current limitations
- No backend, accounts, cross-device sync, payments, push notifications, or real app blocking yet.
- Guest data is stored in the browser on that device. Clearing browser data can erase it.
- The timer is a web timer and does not block other apps.
- This is a prototype/starter, not a production-secure service. Before public launch, add backend authentication, cloud database, privacy policy, security review, analytics consent controls, accessibility testing, and platform-specific app-blocking integrations.
