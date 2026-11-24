---
title: Swipecap Privacy Policy
permalink: /privacy-policy/
---

# Swipecap Privacy Policy

Effective date: 25 November 2026

Swipecap ("the app") is an Android app that counts the Reels and Shorts you watch and, if you choose, stops those viewers after a daily limit. This policy explains what the app accesses, what it stores, and what it sends off your phone. The Play application id is `app.swipecap`.

## Summary
- Daily counts, captions and anything you watch stay on your phone. Swipecap does not upload Reels, screen text or your counts.
- There is no account and no cloud sync.
- Starting with version 1.0.2, Swipecap sends a small, content-free install and app-open signal to Google Analytics (Firebase / GA4) and Meta so that ads can be measured. This uses the Internet permission and may include your advertising ID.
- Swipecap does not use that signal for ad personalization, and it does not include your counts or anything you watch.

## Accessibility Service
Swipecap uses the Android Accessibility Service API for its core feature. With your permission, the service receives screen events only from Instagram (`com.instagram.android`) and YouTube (`com.google.android.youtube`). It inspects the visible screen structure and visible labels such as creator names and captions to estimate when a different Reel or Short appears, and it shows a limit screen over recognised Reels and Shorts viewers once your daily limit is reached.

- This screen content is processed only on your phone.
- Selected screen text is held briefly in memory to avoid counting the same video twice. It is not written to storage and is not sent anywhere.
- Captions, creator names, screenshots, messages and other screen content are never stored or shared.
- The Accessibility Service is off until you read the in-app disclosure, agree, and turn it on in Android settings. You can decline. You can pause counting in the app or turn the service off in Android settings at any time.

Android gives any accessibility service a broad technical ability to read the screen. Swipecap limits its own service to Instagram and YouTube and uses it only as described above.

## Data stored on your phone
Swipecap stores the following only in its private app storage on your phone:
- Daily per-app counts of recognised Reels and Shorts, and the dates they were recorded.
- Your daily limit, your optional estimates of daily count and daily time, and app settings (for example whether the floating counter is shown).
- Fixed, content-free status reasons used to show why something was or was not counted.

App backup is disabled, so this on-device data is not copied to Google Drive backups. It is not sent to Google Analytics or Meta.

## Analytics and advertising attribution
To understand whether a Meta or Google / YouTube ad led someone to install or open Swipecap, the app includes two third-party SDKs:

- Firebase Analytics (Google Analytics 4), operated by Google
- The Meta (Facebook) Android SDK app events, operated by Meta Platforms

These SDKs may collect and share:
- App activity: an app install / first-open event, later app-open events, and a coarse `onboarding_complete` event that does not describe what you watch or how many Reels you counted
- Device or other identifiers: your advertising ID (Android Advertising ID), and the Google Play install referrer when the app was installed from Play
- Technical diagnostics the SDKs need to deliver the event (for example app version and that the device is online)

They do not receive your daily counts, captions, creator names, Reel or Short content, or a Swipecap account id. There is no account. Ad personalization signals for Google Analytics are turned off. Automatic Meta logging of in-app purchases and other in-app events is turned off. Swipecap does not include Crashlytics or other extra analytics SDKs.

This data is sent over an encrypted connection. Google and Meta process it under their own policies, and it is used for analytics and advertising / marketing attribution. Swipecap does not provide an in-app button that deletes the copies held by Google or Meta. You can reset your advertising ID in Android settings, and you can uninstall Swipecap, which stops further events from this app.

## How to delete your data
In the app, open Settings, then Delete saved counts. That removes the saved counts on your phone. Uninstalling Swipecap deletes everything the app stored, including settings and estimates, and stops further analytics events. Turning off Swipecap counter in Android Accessibility settings stops screen access and does not by itself delete saved counts.

## Children
Swipecap is not directed at children under 13 and does not knowingly collect any information from children. It is intended for people aged 18 and over.

## Not affiliated
Swipecap is an independent app. It is not affiliated with, endorsed or sponsored by Meta, Instagram, Google or YouTube. Instagram and Reels are trademarks of Meta Platforms, Inc. YouTube and YouTube Shorts are trademarks of Google LLC. The Meta and Google analytics SDKs described above are used only to measure installs and app opens.

## Security
Daily counts are protected by your phone's own security. Anyone with access to your unlocked phone can open the app and see its counts. Attribution events are sent to Google and Meta over HTTPS.

## Changes to this policy
If the app's data practices change, this policy and the Google Play Data safety section will be updated before the change is released, and the effective date above will change.

## Contact
Questions about this policy can be sent to the developer email address shown on the Swipecap Google Play listing and in the app's Privacy & support screen.
