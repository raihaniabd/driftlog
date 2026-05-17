---
layout: default
title: Privacy Policy
description: How Driftlog handles your data — short version, we don't collect any.
permalink: /privacy/
---

<div class="legal-page" markdown="1">

# Privacy Policy

<p class="legal-meta">Effective date: 2026-05-17 · Last updated: 2026-05-17</p>

## The short version

Driftlog does not collect any personal information. The app does not contain a server. It does not contain ads or analytics. Nothing you enter into the app — tank details, parameter readings, livestock, journal entries, photos, reminders — ever leaves your device.

If at any point that becomes untrue, this document will be updated and a new effective date will be set.

## What is stored, and where

The app stores the following data **locally on your device only**, inside the iOS app sandbox:

- Tanks you create (name, type, volume, setup date, cover photo)
- Parameters and parameter readings (pH, ammonia, salinity, alkalinity, etc., plus any custom parameters you add)
- Livestock (name, species, appearance settings, photo, behavior, notes, status)
- Equipment (name, category, install date, service interval, notes)
- Journal entries (text + optional photo)
- Reminders (title, schedule, time-sensitive flag)
- Your preferences (units, language, theme)
- Photos you attach to any of the above, written to the app's documents directory

This data is written through Apple's standard on-device storage APIs. It is included in your iCloud device backup only if you have iCloud Backup enabled on your iPhone — in which case it is encrypted by Apple and we have no access to it. Uninstalling the app removes all of this data permanently from the device.

## What we do not collect

- We do not have user accounts. There is no email, no username, no password.
- We do not send any data to a server. The app does not make network requests during normal use.
- We do not use advertising SDKs, analytics SDKs, or crash-reporting SDKs.
- We do not track you across apps or websites. The IDFA (advertising identifier) is not requested.
- We do not collect device identifiers, location, contacts, microphone, or any other sensor data.

## Permissions the app may ask for

The app asks for three iOS permissions, and only when you actively use a feature that needs them. You can decline any of them and continue to use the rest of the app.

- **Notifications.** Requested when you create your first reminder. Reminders are scheduled locally on your iPhone through iOS. There is no remote push server. No push tokens are generated or transmitted. Driftlog uses iOS Time-Sensitive Notifications when you enable that option, so reminders can break through Focus Mode.
- **Photo library.** Requested when you tap a photo placeholder (tank cover, fish portrait, journal entry) and choose "Choose from library." The app reads only the photo you select; it does not enumerate or analyze your library. The selected image is copied into Driftlog's app sandbox so the picker's temporary URL doesn't break later.
- **Camera.** Requested only when you choose "Take photo" from the same picker. The camera output goes straight into the app sandbox; it is not shared anywhere.

## Children

The app does not knowingly collect any data from anyone, including users under 13. It is rated 4+ and contains no objectionable content.

## Your rights

Because we do not collect personal data, there is nothing of yours that we hold. The data you have is the data on your phone, and you control it.

- **Export.** Settings → Data → "Export parameters (CSV)" hands a CSV of every reading across every tank to the iOS share sheet. You can email it to yourself, save it to Files, or send it anywhere.
- **Delete a single record.** Open any tank, fish, equipment item, journal entry, or reminder and use the trash icon in the edit screen.
- **Delete a whole tank.** Open the tank, long-press its dashboard card to edit it, then tap the trash icon. This deletes the tank along with every reading, fish, equipment item, journal entry, and reminder belonging to it.
- **Uninstall.** Removing the app from your device deletes every byte of app data, including photos.

If you are in the EU/EEA or UK and exercising rights under the GDPR (access, rectification, erasure, restriction, portability, objection), the app-provided export and delete actions satisfy these for the data the app actually has. If you live in California and would like to exercise CCPA rights, the same is true. We do not sell personal information because we do not have any.

## Changes

If we ever materially change this policy, we will update the effective date above and ship a new app version with the updated text in-app. Continued use of the app after such a change means you accept the new policy. You can always read the latest version inside the app at Settings → Legal → Privacy Policy.

## Contact

For any privacy question, email **[abdessamadraih2@gmail.com](mailto:abdessamadraih2@gmail.com)**.

</div>
