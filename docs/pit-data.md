---
title: Pit data & privacy
nav_order: 7
---

# Pit data & privacy

## What gets uploaded

**iRacing only, for now.** Gary uploads each completed pit stop - car, track, series, and the
timing breakdown (how long fuel took, how long tyres took, whether they overlapped) - to build
better pit and fuel time estimates, faster, by pooling data across the community instead of
each install slowly building up its own from scratch.

**Nothing that identifies you is sent.** No name, no Windows username, no driver ID - nothing
beyond the stop itself. The upload is tied to a per-installation token, not to you personally.

On by default while there are few enough testers that data volume is the priority. Turn it off
any time in **Settings → Share pit stop data** — your own local pit history keeps working
exactly the same either way; only the upload stops.

## What never leaves your machine

Everything else. Your settings, your logs, your lap and pit history — all local, all in
`%AppData%\Gary`. See [Where Gary keeps things](troubleshooting.html#where-gary-keeps-things)
for the full breakdown.

## A log does contain personal information

This is different from pit data. If you ever send a **log file** (see
[Troubleshooting](troubleshooting.html)), be aware it can contain your iRacing customer ID,
session driver names from the field, your Windows username (it's in file paths), and your
machine name. Logs are sent by you, directly, when something's wrong - never uploaded
automatically - but it's worth knowing what's in one before you paste it somewhere public.

## Next

**[Troubleshooting →](troubleshooting.html)**
