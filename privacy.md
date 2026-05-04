---
layout: default
title: Privacy Policy — Timeskip
---

# Privacy Policy

**Effective date: May 4, 2026**

Timeskip ("the app", "we", "us") is designed with privacy as a default. This Privacy Policy explains what limited information the app handles and what we do — and don't — do with it.

## TL;DR

- **All your data stays on your device.** Your weight logs, lift logs, photos, journal entries, and measurements are stored locally in the app's database on your iPhone. Nothing is uploaded to our servers — we don't run any.
- **We don't track you.** No analytics, no advertising SDKs, no third-party trackers, no fingerprinting.
- **We don't have an account system.** You don't sign up, you don't give us an email.
- **The only network calls the app makes** are to Apple's StoreKit (for subscriptions) and Apple's standard system services. That's it.

## What information the app handles

### Information you create inside the app

The app stores everything you log — weight entries, body measurements, lifts, cardio sessions, meals, journal entries, progress photos, custom goals, achievements, and your preferences (units, notification choices, etc.) — **only on your device**, in Apple's local SwiftData database and your app's sandboxed file system.

We don't have access to this data. We can't see it. There is no server we operate that receives it.

### Photos

Progress photos you import or capture are stored:

- In the app's local sandboxed storage on your device.
- In a shared Apple "App Group" container so the Timeskip widget on your home screen can display them.

Photos never leave your device through the app. If you choose to export or share a photo (e.g. via iOS Share Sheet), you control where it goes.

To use the Photos and Camera features, the app requests Apple's standard `NSPhotoLibraryUsageDescription`, `NSPhotoLibraryAddUsageDescription`, and `NSCameraUsageDescription` permissions. You can revoke these any time in iOS Settings → Timeskip.

### Subscription information

If you purchase a Timeskip Pro subscription, the purchase is processed entirely by Apple's App Store / StoreKit framework. The app receives a transaction confirmation from Apple to unlock Pro features locally — we never see your name, payment method, billing address, or any personal Apple ID information. Apple's privacy policy governs that transaction: [https://www.apple.com/legal/privacy/](https://www.apple.com/legal/privacy/).

### Notifications

If you enable notifications (e.g. for the rest timer), they are scheduled and delivered **locally** by your device using Apple's `UNUserNotificationCenter`. We do not send push notifications. We do not have a server. There is no notification token sent anywhere.

## Information we DO NOT collect

To be explicit:

- We do not collect personal information (name, email, phone, address).
- We do not collect health data, HealthKit data, or biometric identifiers.
- We do not collect location data.
- We do not collect device identifiers, IDFA, or advertising IDs.
- We do not use cookies (the app is not a website).
- We do not integrate any analytics service (no Firebase, Mixpanel, Amplitude, Sentry, etc.).
- We do not integrate any advertising network.
- We do not sell, rent, or share your data, because we don't have it.

## Third-party services

The only third party involved in the app's normal operation is **Apple Inc.**, through:

- The iOS operating system itself.
- The App Store (purchase, subscription management, refund processing).
- StoreKit (in-app purchase verification).

Apple's handling of this data is governed by Apple's Privacy Policy.

## Children's privacy

Timeskip is not directed to children under 13. We do not knowingly collect any data from anyone (see above), so this is largely a formality, but: if you are under 13, please do not use the app.

## Your rights

Because all your data lives on your device, you have full control over it at all times:

- **Access:** every piece of data is visible in the app itself.
- **Export:** you can share progress photos and progress cards via the iOS Share Sheet.
- **Delete:** you can delete entries one by one inside the app, or delete the entire app to wipe all of its local data permanently.

We do not have any data to provide, modify, or delete on our end — because we do not store any.

## Changes to this policy

If this policy ever changes, the new version will be posted at this URL with an updated effective date. Material changes will also be communicated in-app.

## Contact

Questions? Email **timeskip.support@icloud.com**.
