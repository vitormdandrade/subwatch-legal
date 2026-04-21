---
layout: default
title: Offsub Privacy Policy
---

# Offsub Privacy Policy

**Last updated: 2026-04-20**

Offsub is a subscription-tracking app for Android. This policy explains — in plain English — what Offsub does and does not do with your information.

## Short version

Offsub does not collect, transmit, sell, or share any personal data. Everything you enter stays on your device. There are no accounts, no servers, no analytics, and no tracking. That is the entire product.

If the short version is enough for you, you can stop reading. The rest of this page is the long-form explanation required by Google Play and regional privacy laws.

## What Offsub is

Offsub helps you keep track of your recurring paid subscriptions (streaming services, SaaS tools, memberships, etc.) and reminds you before they renew. It works fully offline.

## What data Offsub collects

**Subscription information you enter manually.** Names, amounts, billing cycles, renewal dates, categories, colors, optional notes, and reminder preferences for each subscription you add. This data is stored in a local SQLite database file on your device (`Offsub.db`) and in Android SharedPreferences for app settings like theme. It never leaves your device.

**Nothing else.** Offsub does not collect your name, email address, phone number, location, contacts, photos, device identifiers, advertising ID, IP address, or usage analytics. There is no sign-up, no login, and no user account.

## Permissions Offsub requests

**Notifications (Android 13+).** Required to show you renewal reminders. You can deny this permission or revoke it at any time in Android Settings; the rest of the app continues to work.

**Exact alarm scheduling (Android 12+).** Required so reminders fire at the time you set, not up to a few hours later. Used only to wake the app briefly when a reminder is due.

**No internet permission.** The release build of Offsub does not request the `INTERNET` permission. Android enforces this at the operating-system level: even if a bundled library attempted a network request, your operating system would block it. You can verify this yourself by checking the app's permissions in the Google Play Store listing.

## Third parties

**Google Play.** If you purchase Offsub (or, in the future, a paid in-app upgrade), the payment is processed by Google Play. Google receives the information it needs to complete the purchase under [Google's own privacy policy](https://policies.google.com/privacy). Offsub never sees your payment details, card number, billing address, or Google account — Google handles the transaction entirely on its side.

**No one else.** Offsub does not integrate any analytics SDK, crash-reporting SDK, advertising SDK, attribution SDK, or social-login SDK. No third party receives data from this app at runtime.

**A note on fonts.** Offsub uses the Inter font from the `google_fonts` Flutter package for typography. On Android, the release build cannot make network requests (see the "No internet permission" section above), so the font is rendered from the system's fallback font. No font-download request reaches Google at runtime.

## Where your data lives

On your device. Specifically, in the application-private storage area that Android reserves for Offsub, which other apps cannot read. If you uninstall Offsub, Android deletes this data. If you use Android's app-data backup feature (Google Drive backup), your subscription data may be included in that encrypted backup under your Google account; that backup is governed by Google's terms, not Offsub's.

## Your rights

Because Offsub stores nothing about you on any server, there is no account to access, no record to port, and no remote data to delete. You have complete, direct control over every piece of data in the app:

- **To see your data:** open the app; everything is there.
- **To export your data:** [If a CSV export feature exists, mention it here; otherwise remove this bullet.]
- **To correct your data:** edit any subscription inside the app.
- **To delete your data:** delete individual subscriptions in the app, or uninstall Offsub to delete everything.

Users in the European Union, United Kingdom, Brazil (LGPD), and California (CCPA/CPRA) have legal rights to access, correct, delete, and port their personal data and to object to processing. Those rights are satisfied in full by the on-device design above. If you believe a right has not been honored, contact me at the email below.

## Children

Offsub is not directed at children under 13 and does not knowingly collect data from anyone. It also does not collect data from adults. If you are a parent and believe a child has somehow provided personal information to Offsub, that is not possible given the app's design — but please email me so I can help troubleshoot.

## Data breaches

Because Offsub holds no user data on any server, there is no data for me to lose. A breach scenario in the traditional sense does not apply. If a future version ever introduces server-side features, this policy will be updated and existing users will be notified inside the app before the change takes effect.

## Changes to this policy

If this policy materially changes, I will update the "Last updated" date at the top, post the change at the URL where you found this policy, and — if the change involves new data collection — notify users inside the app before the change takes effect.

## Contact

Offsub is a solo independent project.

- Developer: Vitor Andrade
- Email: vitormachadodeandrade@gmail.com

For data-subject requests under GDPR, LGPD, CCPA, or any other law, email me at the address above with a description of your request. I aim to respond within 30 days.
