---
title: Spindot — Privacy Policy
layout: default
---

# Privacy Policy

**Last updated:** 2026-04-23

Spindot ("the app", "we", "our") is a single-player reflex game for iOS. This policy describes what data the app processes and how.

## Summary

- The app has **no user accounts, no logins, and no sign-ups**.
- Your game progress (best level, best clean-shots count) is stored **only on your device**. It never leaves your phone.
- The app shows ads using **Google AdMob**, which may collect standard mobile-advertising data. If you deny App Tracking Transparency, AdMob serves **non-personalized** ads.

## Data the app itself collects

**None that leaves your device.** The app writes the following to the iOS `UserDefaults` container, which is private to the app and removed when you uninstall:

- `bestLevel` — the highest level you've cleared.
- `bestCleanShots` — the highest correct-shot count in a single run.
- Per-install flags indicating whether the ATT and notification prompts have been shown.
- Your preference for the daily reminder notification.

We have no server. We have no way to read this data. Uninstalling Spindot deletes it.

## Data collected by third-party services

The app integrates **Google AdMob** to serve rewarded video ads on the loss screen and banner ads on the landing and loss screens. AdMob may collect:

| Data type                                     | Purpose                         | Linked to you? | Used for tracking? |
| --------------------------------------------- | ------------------------------- | :------------: | :------------------: |
| Identifier for Advertisers (IDFA)             | Third-party advertising         | No             | Yes (only if ATT is granted) |
| Advertising data (ad interactions)            | Third-party advertising         | No             | Yes (only if ATT is granted) |
| Product interaction / usage data              | Ad measurement & analytics      | No             | No                   |
| Crash and performance data                    | App functionality & diagnostics | No             | No                   |
| Coarse location (from IP address)             | Third-party advertising         | No             | Yes (only if ATT is granted) |

Google's full AdMob privacy disclosure is available at <https://support.google.com/admob/answer/6128543>.

## App Tracking Transparency (ATT)

On first launch, iOS shows you a prompt asking whether the app may track you across other companies' apps and websites. This is the standard ATT prompt.

- **Allow** → AdMob can use your IDFA for personalized ads.
- **Ask app not to track** → AdMob serves only non-personalized ads. The game still works identically.

You can change this decision any time in *Settings → Privacy & Security → Tracking*.

## Local notifications

Spindot offers an opt-in daily reminder notification (default: 7:00 PM local time) with a short, playful prompt to come play. This is a **local** notification — no server is involved, and we do not have your device token. You can disable it at any time from the Settings panel inside the app, or from iOS *Settings → Notifications → Spindot*.

## Children

Spindot is rated **4+**. The app does not knowingly collect data from children. Ads served by AdMob for this app follow Google's policies for ads shown in apps rated for general audiences.

## Account deletion

The app has no account system. There is nothing to delete on our side. To remove all app-related data from your device, uninstall the app from your home screen.

## Your rights

You can:

- Opt out of personalized ads via the ATT prompt or iOS Settings.
- Reset your AdMob advertising identifier in *iOS Settings → Privacy & Security → Tracking*.
- Remove all local data by uninstalling the app.

## Changes to this policy

If we update this policy, we'll change the date at the top and, if the change is significant, announce it in the app's release notes.

## Contact

Questions about this policy? Email **mypawpal.application@gmail.com**.

---

*This policy applies only to Spindot. Third-party services referenced above have their own privacy policies — please review them separately.*
