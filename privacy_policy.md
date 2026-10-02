# Privacy Policy — TripLord

**Last updated: October 2026**

---

## Who we are

TripLord is an iOS application developed for use in classic car rally navigation.
This privacy policy explains what data the app uses, where it stays, and what it
never does.

---

## What data TripLord uses

### Location (GPS)

TripLord uses your device's GPS and compass to display:

- Current speed
- Travel direction (heading / course)
- Trip, total, and navigation distance counters
- Elapsed time

Location data is processed **entirely on your device**. It is never transmitted,
uploaded, or shared with anyone — including the developer.

TripLord requests the **"Always"** location permission. This is needed so the app
continues tracking distance and heading when the device screen is managed by the
car's mount. If you prefer, **"While Using"** permission is sufficient when you
keep the app in the foreground throughout your drive.

### Microphone and speech recognition

TripLord can optionally listen for a spoken distance value (for example
"thirteen fifty") to set a countdown counter during a regularity stage. This
feature is activated only when the navigator deliberately taps the microphone
button.

- The microphone is **never active in the background** and is never used for
  any purpose other than recognising a single spoken number.
- Speech recognition runs **on-device** using Apple's on-device speech
  recognition engine. No audio or transcription is sent to any external server.
- No audio is recorded or stored. The recognised text is discarded immediately
  after the number is parsed.

### AVG dial audit log

TripLord keeps a local log of every event in which the average-speed dials are
switched on or off. Each log entry contains:

- A timestamp (date and time)
- Whether the dials were switched on or off
- How long the dials were visible / hidden

This log is stored in a private file on your device
(`Documents/triplord_avg_log.json`). It exists solely to allow rally organisers
or jury members to verify correct use of the average-speed display during a
competition. The log is never transmitted off the device.

### App preferences

TripLord saves a small number of preferences using your device's standard local
storage (UserDefaults), such as:

- Number of decimal digits shown on distance counters
- Time display style
- Trip reset behaviour
- Compass display mode
- Voice language for distance input

These preferences stay on your device and are never transmitted anywhere.

---

## What TripLord does NOT do

| &nbsp; | &nbsp; |
|---|---|
| Collect personal information | ✗ Never |
| Create user accounts | ✗ Never |
| Transmit any data to external servers | ✗ Never |
| Use analytics or crash-reporting SDKs | ✗ Never |
| Show advertisements | ✗ Never |
| Share data with third parties | ✗ Never |
| Track you across other apps or websites | ✗ Never |
| Record or store audio | ✗ Never |
| Send speech data to any server | ✗ Never |
| Access your contacts, camera, or photos | ✗ Never |

---

## Screen stays on

While TripLord is active, it prevents the device screen from auto-locking. This
is intentional behaviour to keep the display visible during a drive. It stops
as soon as you leave the app.

---

## Children

TripLord does not knowingly collect any data from anyone, including children.
There is nothing to collect — all data stays on the device.

---

## Changes to this policy

If a future update of TripLord were ever to change how data is handled, this
policy would be updated before that version is released. The "Last updated" date
at the top of this page will always reflect the current version.

---

## Contact

If you have any questions about this privacy policy or the TripLord app, please
open an issue on the GitHub repository where this document is hosted.

---

*TripLord is a private navigation tool. It exists to help you drive, not to
collect data about you.*
