---
layout: default
title: Support
description: How to get help with Driftlog, what to include in a report, and what's in scope.
permalink: /support/
---

<div class="legal-page" markdown="1">

# Support

<p class="legal-meta">Last updated: 2026-05-17</p>

## How to reach me

Email is the fastest way to get help. I usually reply within **1–2 business days**.

[**abdessamadraih2@gmail.com**](mailto:abdessamadraih2@gmail.com?subject=Driftlog%20support)

## What to include in a report

To get the fastest, most useful answer, include:

1. Your **iOS version** (Settings → General → About → Software Version).
2. Your **iPhone model**.
3. The **app version** (Driftlog → Settings → About → Version).
4. A short description of what you tried and what you expected to happen.
5. A screenshot or screen recording if the issue is visual.

If the app crashed, also mention what you were doing right before — for example "I added a fish with the 'top' behavior and tapped Save."

## Common questions

### How do I export my data?

Open the app, go to **Settings → Data → Export parameters (CSV)**. The CSV contains every reading across every tank, with tank name, parameter, value, unit, timestamp, and any notes. The iOS share sheet lets you save it to Files, email it, or AirDrop it.

### How do I switch language?

**Settings → Language.** Five languages: English, Arabic, French, Spanish, German. Switching to Arabic flips the layout to right-to-left and requires a quick restart of the app.

### My reminder didn't fire. What happened?

A few things to check:

- **Permissions.** Open iOS Settings → Notifications → Driftlog. "Allow Notifications" must be on. If you want the alert to break through Focus Mode, "Time Sensitive Notifications" must also be enabled.
- **Repeat rule.** iOS supports daily and weekly recurrences natively. Biweekly and monthly reminders use a 14-day / 30-day interval — they may drift slightly over many cycles. That's expected.
- **Test it.** Inside the New Reminder screen there's a **"Send a test notification in 10s"** button. Lock your screen or background the app and you'll see exactly how the notification looks on your device.

### Tapping a notification doesn't open the right tank.

That should always work for reminders created in Driftlog. If it doesn't, please send a screenshot of the notification — it likely means the reminder was created in a very old build that didn't bundle the tank id into the notification payload. Re-creating the reminder will fix it.

### Can I track custom parameters my favorite parameter wasn't on the default list?

Yes. **Settings → Custom parameters → pick a tank type → Add parameter.** Whatever you add (name, unit, optional min/max safe range) is automatically applied to every existing tank of that type and every new tank of that type going forward.

### Can I get data from one tank to another?

Not in v1.0. Each tank has its own readings, livestock, equipment, and journal. If this is something you need, email me — I'll add it to the roadmap.

### I deleted a fish by mistake.

When you delete a tank, fish, equipment, journal entry, or reminder, it's gone immediately and not recoverable. The CSV export gives you a way to keep your readings offline; for in-app data, an Undo flow is on the roadmap.

### Is there an Android version?

Not currently. The app is iOS-only.

## What's not in scope

- **Aquarium care advice.** I'm a developer, not a veterinarian or a hobbyist consultant. Use peer-reviewed species references or qualified veterinarians for care decisions.
- **Account recovery.** There are no accounts. Nothing to recover.
- **Cloud sync.** Driftlog is offline by design. Your data stays on the device.
- **Apple-side billing issues.** Refund requests for App Store purchases are handled by Apple. See <https://support.apple.com/en-us/HT204084> to request one.

## Roadmap and feedback

Feature suggestions are very welcome. The next planned additions:

- Photo timeline per tank
- Water-change task history
- A few extra languages
- Apple-Pencil/scratch-pad note attachments to journal entries

If something you'd love isn't on that list — write me. The roadmap is genuinely driven by what hobbyists ask for.

</div>
