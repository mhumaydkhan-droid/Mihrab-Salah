# Salah Tracker v2

Features: daily date selector; green on-time and yellow Qaza toggles; per-prayer Fard rakaat accounting; outstanding Qaza counters; monthly Qaza rakaat logged vs rakaat made up progress bar; backup export/import; pastel grey/sage styling; installable PWA shell.

## Data model
Data is stored in localStorage in this browser/device. It is not stored in Claude and is not shared with other people. To give family members a shareable link, host this folder on HTTPS. Each browser profile will have its own local data. For secure multi-device sync, authentication and a cloud database with per-user access control must be added.

## Host and install
Upload all files to a static HTTPS host (e.g. GitHub Pages). Share the resulting HTTPS URL. On Android Chrome open the URL, menu ⋮ → Install app / Add to Home screen.

## Accounting behavior
Marking a prayer Qaza on a date adds one prayer to the outstanding count for that Salah; changing/removing that Qaza mark reverses that addition. In the Qaza tab, tap − when you complete an outstanding Qaza prayer; it records that completion against the current date for monthly progress. Monthly progress compares Fard rakaat logged as Qaza in the selected month with Fard rakaat marked as made up in that month. Outstanding balance is separate and carries across months.


Updated controls: use ‹ and › beside the date field to move one day backward or forward, or tap Today to jump back to the current date. Prayer cards are displayed in one vertical line and the entire card turns green for On time or yellow for Qaza.
