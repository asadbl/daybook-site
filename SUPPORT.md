# Daybook — Support

A field record for people whose work has to be proved after the fact.

**Get help:** [open an issue](https://github.com/asadbl/daybook-site/issues). Include your iOS
version and what you were doing when it went wrong.

## Getting started

**Make a job.** Projects → **+**. A name is the only thing required; client, reference, address
and dates can be filled in whenever you have them.

**Photograph it.** Camera → shutter. The chip at the top says which job the photo lands in — tap
it to switch without leaving the camera. If you shoot before making a job, the photos wait in
**Unsorted** and you file them later.

**Mark before, during and after.** Select photos in the grid and set the phase. Phases print as
labels on the report and are searchable.

**Tag them.** Tags group photos that belong together across days — every frame of tooth 10, of the
north elevation, of unit 3B. Tag one photo from its own screen, or a whole selection at once, then
switch the project grid from **By day** to **By tag**.

## Notes

Two kinds, deliberately kept apart:

- **Notes on a job** — the running log. Written from the project screen. Pin one and it stays at
  the top.
- **Notes on a photograph** — what the inspector objected to, what the client approved, why you
  reshot it. Written from the photo screen or its Actions menu. Each records who wrote it and
  when, and the newest prints under that photo in the report.

A note on a photograph stays on that photograph — it does not clutter the job's log. Deleting a
photo does not delete what people wrote about it. To remove a note, use the **⋯** menu on it.

## Reports

Open a job → **Export**. Two formats:

- **PDF report** — cover, photographs numbered and grouped by day, optional map, chain-of-custody
  appendix and signature page.
- **ZIP** — every original with a CSV manifest of hashes and locations, plus a README explaining
  how to verify them. Readable without this app.

On the free plan the PDF carries a small Daybook mark in the corner. Nothing else about it
differs, and the ZIP is never marked.

## Proving a photo has not been altered

Open a photo and tap **Verify Integrity**. Daybook re-hashes the file on disk and compares it with
the fingerprint recorded at capture. The same fingerprints are listed in the report's
chain-of-custody appendix, so a reader can check them independently.

## Languages

English, Hebrew, Arabic, Russian and Spanish, in Settings → Language. Hebrew and Arabic turn the
whole layout right to left. A few labels finish switching after you reopen the app.

## Subscription

Daybook Pro is an auto-renewing subscription — $9.99/month or $69.99/year, each starting with a
7-day free trial. It lifts the free plan's limits and removes the mark from reports.

Manage or cancel in Settings → Apple Account → Subscriptions, or in the app at
Settings → Subscription → Restore Purchases if you have changed device.

Reading and exporting are never blocked, on any plan, including after a subscription ends.

## Common questions

**The camera shows "SAMPLE" images.** You are running in the iOS Simulator, which has no camera.
Daybook substitutes obvious placeholder frames so the rest of the app can be used.

**The map page is missing from my report.** Map tiles need a network connection at the moment the
report is built, and only photographs that recorded a location appear on it. The report says how
many were left off.

**Does Daybook work offline?** Yes. Capture, notes, tags, search and reports all work with no
connection. Only the map page and the trusted-clock check need the network, and both degrade
quietly.
