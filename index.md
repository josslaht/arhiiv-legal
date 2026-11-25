---
title: Arhiiv Privacy Policy
---

# Arhiiv Privacy Policy

*Effective TODO(Joosep): the date this is published, before 1.2 is submitted*

Arhiiv is a film-photography logging app made by Joosep Laht ("we", "us"). This
policy explains what Arhiiv does with your data. It's short because Arhiiv
doesn't do very much with it: there are no accounts, no ads, and nothing of
yours is for sale.

## The short version

- Your camera bodies, lenses, rolls, frames, and notes are stored **on your
  device** and, if iCloud Sync is on, in **your own private iCloud**. We
  never see them, unless you choose to export and share them yourself.
- Arhiiv uses your location to tag where each frame was shot. The
  coordinates are sent to Apple to look up the place name; we never receive
  them.
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
your device using Apple's on-device database (SwiftData), and in your private
iCloud if iCloud Sync is on (see below). We don't have access to it. Apart
from iCloud Sync and the place-name lookup described under Location, it
leaves your device only when you export or share it yourself.

## iCloud Sync

If Sync with iCloud is on (it is by default on new installs), Arhiiv stores
your rolls, frames, gear and custom film stocks, including frame locations
and notes, in your private iCloud database using Apple's CloudKit, under your
Apple Account. This data is visible only to you: we can't access it, and it
isn't sent to us or to anyone else. Frame locations, notes, gear notes,
serial numbers and lab details are stored in iCloud in encrypted form.
[Apple's iCloud terms](https://www.apple.com/legal/internet-services/icloud/)
and [privacy policy](https://www.apple.com/legal/privacy/) apply to data
stored in iCloud.

You can turn sync off in Arhiiv's Settings, and your data stays on your
device. Turning it off leaves the copy in iCloud in place, so you can turn
sync back on later. To delete that copy, go to Settings > [your name] >
iCloud > Storage > Arhiiv in the iOS Settings app. If you sign out of iCloud,
iOS removes synced data from the device until you sign in again; it stays
in your iCloud.

## Location

When you log a frame, Arhiiv silently captures a single, one-shot location
fix from your device (no continuous or background tracking) and stores it
with that frame, on your device (and in your private iCloud if iCloud Sync is
on, encrypted). This is used solely to show you where a
shot was taken. You can decline location access entirely when prompted;
frames simply log without coordinates.

To show where a frame was taken (for example "Berlin"), Arhiiv sends that
frame's coordinates to Apple's Maps service for reverse geocoding when the
frame is displayed. The request goes directly from your device to Apple,
which handles it under
[Apple's privacy policy](https://www.apple.com/legal/privacy/). We never
receive these coordinates, and the place name is kept only on your device
(it isn't synced to iCloud).

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
  coordinates, or the names you give your gear or rolls. One event reports
  when Arhiiv fails to save your data. It carries only the internal name of
  the code that failed, so we can catch and fix data-loss bugs.
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

The one exception is the failed-save report described under Analytics. It's
only sent when "Share anonymous usage data" is on. Nothing else diagnostic
leaves your device.

## Who we share data with

- **TelemetryDeck GmbH (Germany)** receives anonymized usage data, including the
  failed-save report, acting as our data processor, as described above.
- **Apple** (Apple Maps reverse geocoding) receives the coordinates of the
  frames you log, for the sole purpose of returning a place name, as
  described under Location. We don't receive these coordinates ourselves.
- **Apple** (iCloud) stores your Arhiiv data in your private iCloud if iCloud
  Sync is on, as described under iCloud Sync. This is your own iCloud
  storage, under your Apple Account; we can't access it.

We don't sell your data, share it with advertisers, or share it with anyone
else. Beyond the anonymized usage data and the coordinates described above,
we don't have anything of yours to share, since the rest lives only on your
device and in your own private iCloud.

## Your choices

- **Turn off analytics** at any time in Settings.
- **Delete your data** by deleting it in the app. With iCloud Sync on, that
  deletes it in iCloud and on your other devices too. Uninstalling Arhiiv
  removes the copy on that device; to also remove the copy in iCloud, go to
  Settings > [your name] > iCloud > Storage > Arhiiv.
- **Turn off iCloud Sync** at any time in Arhiiv's Settings.
- **Analytics data can't be deleted on request**, because it's anonymous by
  design: we have no way to connect a signal back to a specific person or
  device to find it.

## Legal basis and regional notes

Where GDPR applies, our bases for the limited processing described above are:

- **Location and camera:** your consent, given through the system permission
  prompts. The location prompt covers both recording where a frame was shot
  and sending the coordinates to Apple to look up the place name. You can
  withdraw your consent at any time in iOS Settings.
- **iCloud Sync:** your choice to keep it on. The data is stored by Apple, as
  your iCloud provider, in your own account; we don't process it.
- **Anonymous usage statistics (TelemetryDeck):** our legitimate interest in
  understanding how Arhiiv is used, and catching bugs that lose data, so we
  can improve it (Article 6(1)(f) GDPR). This covers the failed-save report
  too. The statistics are anonymised and can't identify you. You can object
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

We may update this policy from time to time. If we do, we'll change the
effective date at the top of this page.

## Contact

Questions? Email [arhiivapp@gmail.com](mailto:arhiivapp@gmail.com).
