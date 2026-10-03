---
title: Arhiiv Privacy Policy
---

# Arhiiv Privacy Policy

*Effective 2 October 2026*

Arhiiv is a film-photography logging app made by Joosep Laht ("we", "us"). This
policy explains what Arhiiv does with your data. It's short because Arhiiv
doesn't do very much with it: there are no accounts, no ads, and nothing of
yours is for sale.

## The short version

- Your camera bodies, lenses, rolls, frames, and notes are stored **only on
  your device**. We never see them, unless you choose to export and share
  them yourself.
- Arhiiv uses your location to tag where each frame was shot — nothing else.
  The coordinates are sent to Apple to look up the place name; we never
  receive them.
- The camera is used only for the built-in light meter. No photo or video is
  ever captured or stored.
- We use TelemetryDeck, a privacy-focused analytics service, to understand
  which features people use. It's anonymous, not linked to you, and you can
  turn it off.
- We have no way to identify you, because we never collect anything that
  could — no email, no name, no account.

## What's stored, and where

Arhiiv has no server and no user accounts. Everything you enter — camera
bodies, lenses, rolls, frames, notes, and film stocks — is stored locally on
your device using Apple's on-device database (SwiftData). We don't have
access to it, and it isn't sent anywhere unless you explicitly export or
share it yourself — the one exception is the place-name lookup described
under Location below.

## Location

When you log a frame, Arhiiv silently captures a single, one-shot location
fix from your device (no continuous or background tracking) and stores it
with that frame, on your device. This is used solely to show you where a
shot was taken. You can decline location access entirely when prompted;
frames simply log without coordinates.

To turn those coordinates into a place name, Arhiiv sends them to Apple
(Apple Maps), which looks up the name of the place. The request goes
directly from your device to Apple, and the coordinates are handled under
[Apple's privacy policy](https://www.apple.com/legal/privacy/). We never
receive them.

If you export a roll to CSV, any coordinates you've logged are included in
that file, because you asked for it.

## Camera

Arhiiv's light meter uses your device's camera to estimate exposure. No
photo or video is ever captured, stored, or transmitted — the camera feed is
read and discarded in real time.

## Analytics (TelemetryDeck)

We use [TelemetryDeck](https://telemetrydeck.com) (provider: TelemetryDeck
GmbH, Von-der-Tann-Str. 54, 86159 Augsburg, Germany) to understand how
Arhiiv is used — for example, whether a roll gets fully logged, or whether
the light meter gets used — so we can improve the app. TelemetryDeck is
built for privacy:

- It identifies your device with an anonymous, salted-hash ID that **cannot
  be linked back to you**. There's no advertising identifier, no cross-app
  tracking, and no App Tracking Transparency prompt, because none of that
  applies here.
- The events we send are counts and categories (for example, "a roll was
  completed," rounded to a range) — never your photos, frame notes, GPS
  coordinates, or the names you give your gear or rolls.
- The one exception: if you add a custom film stock, its brand and name are
  sent, so we can improve Arhiiv's built-in film catalog for everyone. A
  film stock name (e.g. "Kodak Portra 400") isn't personal information.
- TelemetryDeck's servers are hosted in the EU/Switzerland.

Further detail on TelemetryDeck's own processing is at
[telemetrydeck.com/privacy](https://telemetrydeck.com/privacy).

You can turn this off at any time in Arhiiv's Settings, under "Share
anonymous usage data." It's on by default so early feedback can help guide
the app, but nothing else about the app changes if you turn it off.

## Diagnostics

Arhiiv uses Apple's MetricKit to log crash and performance details to your
device's local system log, purely to help us debug a problem if you report
one to us directly. This stays on your device and isn't automatically sent
to us or anyone else.

## Who we share data with

- **TelemetryDeck GmbH (Germany)**, acting as our data processor, receives
  anonymized usage data, as described above.
- **Apple** receives the coordinates of a frame when Arhiiv looks up its
  place name, as described under Location. This goes directly from your
  device to Apple; we never see it.

We don't sell your data, share it with advertisers, or share it with anyone
else.

## Your choices

- **Turn off analytics** at any time in Settings.
- **Delete your data** by deleting it in the app or uninstalling Arhiiv —
  since everything lives locally, that removes it completely.
- **Analytics data can't be deleted on request**, because it's anonymous by
  design: we have no way to connect a signal back to a specific person or
  device to find it.

## Legal basis and regional notes

Where GDPR applies, our bases for the limited processing described above are:

- **Location and camera:** your consent, given through the system permission
  prompts. The location prompt covers both recording where a frame was shot
  and sending the coordinates to Apple to look up the place name. You can
  withdraw your consent at any time in iOS Settings.
- **Anonymous usage statistics (TelemetryDeck):** our legitimate interest in
  understanding how Arhiiv is used so we can improve it (Article 6(1)(f)
  GDPR). The statistics are anonymised and can't identify you. You can object
  at any time by turning off "Share anonymous usage data" in Arhiiv's
  Settings, which takes effect immediately.

California residents: we don't sell or share personal information as
defined by the CCPA/CPRA, and don't collect personal information beyond what's
described above.

## Children

Arhiiv isn't directed at children and doesn't knowingly collect personal
information from anyone, of any age — there's nothing to collect, since
there are no accounts or profiles to begin with.

## Changes to this policy

If this policy changes in a way that matters, we'll update the effective
date above and note what changed.

- **2 October 2026:** Arhiiv now sends a frame's coordinates to Apple (Apple
  Maps) to look up the place name. We never receive the coordinates. Apple is
  now listed under who we share data with, and the location prompt is stated
  to cover this lookup.
- **26 September 2026:** new contact address, and the basis for anonymous
  usage statistics is now stated as legitimate interest rather than consent,
  matching how the Settings toggle works (on by default, off whenever you
  choose).

## Contact

Questions? Email [arhiivapp@gmail.com](mailto:arhiivapp@gmail.com).
