---
title: Spotter voice packs
nav_order: 7
has_children: true
---

# Spotter voice packs

The spotter can use a recorded voice pack instead of one of Gary's voices. Packs use
CrewChief's format, so the spotter packs made for CrewChief work in Gary as they are.

Gary doesn't ship, download or host packs. It plays the ones you install. Packs are made by other
people - where one comes from and whose voice is on it is between you and whoever made it.

Want to record your own? See **[Making a spotter pack](making-spotter-packs.html)**.

## If you have CrewChief

Nothing to install. Every spotter in your CrewChief install shows up in Gary on its own,
including CrewChief's default spotter, Jim. A pack you install into CrewChief later shows up too.

Gary reads them from CrewChief's sound folder and never changes anything in it:

```
%LOCALAPPDATA%\CrewChiefV4\Sounds\voice
```

## Without CrewChief

1. Create this folder if it isn't there yet:

   ```
   Documents\Gary\SpotterPacks
   ```

2. Unzip the pack into it. You should end up with a `spotter_` folder, and usually a
   `radio_check_` folder next to it:

   ```
   Documents\Gary\SpotterPacks\
       spotter_Name\
           car_left\
           car_right\
           clear_all_round\
           ...
       radio_check_Name\
           test\
   ```

   If the zip has its own folder around these two, move them up so they sit straight inside
   `SpotterPacks`.

## Choosing a pack

**Settings → Spotter voice**, pick the pack and **Save**, then **Stop** and **Start**. The pack's
radio check plays the next time you open Gary.

- CrewChief's spotters are listed as **Name (CrewChief pack)**.
- Packs from `Documents\Gary\SpotterPacks` are listed as **Name (voice pack)**.

A pack added while Settings is open shows up the next time you open it.

## What changes with a pack

- **Its own radio check.** If the pack has a `radio_check_` folder, it answers the radio check
  when Gary starts.
- **Same volume as the crew chief.** Packs are usually recorded much louder than Gary's voices.
  Gary brings every recording to the crew chief's level, then applies your **Spotter volume**.
  Your pack files aren't changed.
- **No radio click by default.** Most packs already sound like a radio. **Radio effect on spotter
  voice packs** in Settings turns Gary's click and squelch back on for them.
- **Gaps are filled in.** Any call a pack doesn't have is said by Gary's own spotter, so nothing
  goes silent.
- **Variety.** Packs usually have several recordings of each call. Gary shuffles them and never
  plays the same one twice in a row.

With a pack, the captions show what Gary's own spotter would have said, not the pack's words.

## Going back

Pick any of Gary's voices in **Spotter voice**, **Save**, then **Stop** and **Start**.

If you delete a pack while it's selected, Gary uses the default spotter the next time it starts.

## A pack doesn't show up

- The folder has to start with `spotter_` (CrewChief's default spotter is just `spotter`).
- It has to sit straight inside `SpotterPacks` or CrewChief's `voice` folder, not one level
  deeper.
- It needs recordings in at least one of `car_left`, `car_right` or `clear_all_round`.
- Recordings must be `.wav` files: mono, 16-bit. That's what CrewChief packs already use.

Still stuck? Send the log on [Discord](https://discord.gg/XAdbGx8zV8) - see
[Troubleshooting](troubleshooting.html). It names the pack Gary loaded and where from.
