# Chepito Rios Online Radio — Privacy Policy

Public hosting for the privacy policy of the **Chepito Rios Online Radio** mobile app
(iOS and Android).

Live at: https://xanderyeng.github.io/chepito-rios-privacy/

## Why this repo exists

Apple requires a publicly reachable privacy policy URL on the App Store listing, and the
policy has to match the App Privacy label declared in App Store Connect. The app's own
repository is private, so GitHub Pages cannot serve from it on the free plan. This repo
holds nothing but the policy page, so it can be public without exposing any app code.

## Keeping it accurate

The policy states that the app collects no data. That is true as of the current build:
no analytics, crash-reporting, advertising or attribution SDKs, no accounts, and no
tracking. The App Privacy questionnaire in App Store Connect is answered "No" on that
basis.

If any of the following are ever added to the app, this page and the App Store Connect
privacy label both have to be updated before the next release:

- any analytics, crash-reporting or attribution SDK
- advertising of any kind
- user accounts, login, server-synced favourites, or push notifications tied to a device token
- listener analytics or request logging on the Now Playing backend
- anything that calls App Tracking Transparency

## Editing

`index.html` is a single self-contained page — no build step, no dependencies. Edit it and
push to `main`; GitHub Pages redeploys automatically. Update the effective date near the top
whenever the content changes materially.
