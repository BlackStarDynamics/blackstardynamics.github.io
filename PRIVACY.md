---
layout: default
title: Privacy Policy
permalink: /PRIVACY/
---

# Privacy Policy for Shot Solver

**Effective date:** May 26, 2026
**Publisher:** BlackStar Dynamics

This policy explains what data Shot Solver ("the app") collects, why, and what
happens to it. We've kept it short on purpose — the app is designed to do its
job without collecting personal data on our servers.

## Summary

- **All your data — rifles, loads, suppressors, DOPE cards, range sessions,
  and biometric readings — is stored locally on your device.** It is never
  sent to BlackStar Dynamics or any third party.
- The app uses your **device location** *only* to fetch local weather (temperature,
  pressure, humidity, wind) from a public weather service so the ballistic solver
  can use real atmospheric conditions. Your location is not stored on our servers
  and is not associated with any identifier.
- We do not use analytics SDKs, ad networks, or third-party trackers.
- We do not have user accounts, and the app does not require sign-in.

## What the app stores on your device

The following are saved in a local database on your phone (SQLite, sandboxed
to the app):

- Rifle profiles (name, caliber, barrel length, twist rate, sight height,
  zero range, click value, optional suppressor)
- Load profiles (name, bullet weight, BC, muzzle velocity, notes)
- Suppressor profiles (name, manufacturer, length, weight, mount type, serial
  number, MV offset)
- DOPE cards (range tables and the conditions they were generated under)
- Range sessions (date, rifle, load, location name, conditions snapshot, notes)
- Optional biometric values entered manually or imported from connected health
  data sources (heart rate, blood pressure, HRV, SpO₂)
- Application preferences (units, default rifle/load)

To delete this data, uninstall the app. There is no copy on our servers.

## What the app sends off-device

When you tap "Refresh weather" or "Use current weather," the app sends your
device's current latitude and longitude to a public weather provider
([Open-Meteo](https://open-meteo.com/)). The provider returns current weather
conditions for that location. Per Open-Meteo's policy, requests are not
associated with any account or identifier from us; we do not include any user
information in the request. We do not log or store these requests.

No other data leaves your device.

## Health data (HealthKit / Health Connect)

Shot Solver is designed to optionally read selected health metrics — heart
rate, blood pressure, heart rate variability, and blood oxygen — from Apple
HealthKit (iOS) or Health Connect (Android) so you can correlate physiology
with marksmanship performance.

- This integration is **disabled by default** and requires your explicit
  authorization through the operating system's health-permissions UI.
- Imported values are stored only on your device, in the same local database as
  your other range data.
- We never transmit health data off-device.

If you withdraw permission in your phone's system settings, the app stops
reading new values immediately. Previously imported values that you saved to a
range session remain on the device until you delete the session.

## Children

Shot Solver is not directed at children under 13 and does not knowingly
collect data from them.

## Changes to this policy

If we update this policy, the new version will be posted at this URL with an
updated "Effective date." For TestFlight beta builds, material changes will be
flagged in the TestFlight What's New notes for the corresponding build.

## Contact

Questions about this policy or your data:

**BlackStar Dynamics**
Email: owner@blackstardynamics.com
