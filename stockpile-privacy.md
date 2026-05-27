---
layout: default
title: Privacy Policy — Stockpile
permalink: /stockpile-privacy/
---

# Privacy Policy — Stockpile

**Effective date:** 2026-05-26
**Publisher:** BlackStar Dynamics

**Plain-English summary:** Stockpile does not collect any data about you. Everything you enter into the app stays on your iPhone unless you choose to export and share it yourself. We don't operate any servers. We don't have user accounts. We don't run analytics. We don't track you across apps or websites.

If that's all you wanted to know, you're done. The rest of this page exists to satisfy the App Store's disclosure requirements and to explain in detail what the app does, what permissions it asks for, and why.

---

## 1. Who we are

This app is published by **BlackStar Dynamics**. References below to *"we"*, *"us"*, and *"our"* mean BlackStar Dynamics. References to *"the app"* mean **Stockpile** on iOS.

To contact us about this policy or the app, email **owner@blackstardynamics.com**.

## 2. What information the app handles

The app exists to let you record an inventory of personal property — firearms, ammunition, shopping list items, range-day plans, and your notes about them. You type or pick that information yourself. We never see it.

Everything you enter is written only to the local database on your iPhone (Apple's SwiftData / SQLite storage, sandboxed to this app). A small amount of additional state lives in:

- **The iOS Keychain on this device** — your unlock PIN, stored as a salted SHA-256 hash. Accessible only when the device is unlocked.
- **Your iPhone's preferences (UserDefaults)** — a flag for whether you've enabled biometric unlock and a flag for whether you've ever set a PIN. No personal data.
- **Your iPhone's temporary files** — when you tap *Export*, the resulting CSV or PDF is written to a temporary file so iOS's share sheet can hand it off to wherever you choose to send it.

None of this is uploaded anywhere by the app.

## 3. What we do not do

- **No accounts.** You don't create one. There is no login system tied to a server.
- **No cloud sync operated by us.** The app does not contact any server we run. (If you have iCloud Backup enabled in iOS settings, Apple may include the app's local data in your encrypted iCloud Backup — that's a system-level feature of iOS, not something the app initiates.)
- **No analytics.** We don't use any third-party analytics SDK. We have no way of knowing the app has been opened, how often it's used, what's in it, or even how many people have installed it (beyond Apple's anonymous, aggregated App Store metrics, which we cannot tie to you).
- **No advertising.** No ads of any kind are shown in the app.
- **No tracking.** The app does not track you across other apps or websites, and does not contain any tracking SDKs.
- **No sharing.** Because nothing leaves the device through the app, there is nothing to share with anyone — including law enforcement — by us. (A subpoena directed at us would receive an honest answer of "we don't have it.")

## 4. iOS permissions the app asks for

The app may ask your permission to access:

- **Face ID / Touch ID** — purely to let you unlock the app's private inventory with biometrics. Biometric data never leaves the Secure Enclave on your device; the app only receives a yes/no result from iOS.
- **Photo Library** — only if you tap *Add Photo* on a firearm record and choose to attach a photo. The app receives only the photo you select, and only stores it inside your local inventory record on this device.

You can revoke either permission at any time in **iOS Settings → Stockpile**.

## 5. Children

Stockpile is not directed at children under 13 and does not knowingly collect data from them.

## 6. Your control over your data

Because all of your data is stored locally on your iPhone:

- **To view it**: open the app.
- **To export it**: use the *Settings → Export* options to generate a CSV or PDF you can send anywhere you choose.
- **To delete an entry**: swipe to delete inside the app.
- **To delete everything**: delete the app from your iPhone. iOS will remove the local database and the Keychain entry along with it.

There is no separate request you need to submit to us to delete your data — we don't have it.

## 7. Changes to this policy

If we update this policy, the new version will be posted at this URL with an updated *Effective date*. For TestFlight beta builds, material changes will be flagged in the TestFlight What's New notes for the corresponding build.

## Contact

Questions about this policy or your data:

**BlackStar Dynamics**
Email: owner@blackstardynamics.com
