---
title: Pit data & privacy
nav_order: 8
---

# Pit data & privacy

## What gets uploaded

Three things, each with its own switch in **Settings**, all on by default. Pit stops and GPS are
iRacing only for now; tyre wear is both sims:

- **Pit stops** - car, track, series and the timing breakdown: time lost in the pit lane, how
  long fuel and tyres took, fuel burned per lap over the stint. This is what lets Gary tell you
  what a stop or a drive-through costs, and fuel you, at a car and track you've never driven.
- **GPS for tracks that need it** - at a track still missing corner data, one clean lap's worth
  of position data, so corner names can be added. Most laps upload nothing at all.
- **Tyre wear** - one row per stint: conditions, tyre wear, lap times (with the fuel on board and
  whether you were in traffic on each lap, and how old the tyres were at the start), how hard the car was
  driven (cornering and braking load, how much of the braking was on ABS), the incident points
  picked up, and (unless it was a fixed setup) camber, toe and brake bias. Used to build a tyre
  wear model. **In Le Mans Ultimate** the row is the same idea in its own LMU table: tyre wear per
  corner, compounds, lap times and fuel, conditions, the session's wear and fuel multipliers, and
  any damage and lockups during the stint.

**Nothing that identifies you is sent.** No name, no Windows username, no driver ID - the upload
is tied to a random per-installation token, not to you. Turning any of these off stops only the
upload; everything Gary does locally keeps working the same.

## The keyboard (Le Mans Ultimate)

If you've bound **regen up and down to keyboard keys** in LMU, Gary watches those two keys - and only
those two - so he can follow your regen setting (LMU doesn't publish it). Every other key is
ignored the moment it arrives; nothing you type is looked at, kept or sent. With regen bound to a
wheel button instead, Gary watches that button the same way he watches push-to-talk.

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
