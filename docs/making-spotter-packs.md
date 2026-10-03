---
title: Making a spotter pack
parent: Spotter voice packs
nav_order: 1
---

# Making a spotter pack

A spotter pack is a folder of recordings, one subfolder per call. It's CrewChief's format, so a
pack you make for Gary works in CrewChief too, and the other way round.

Only record voices you have permission to use: your own, or someone who's agreed to it.

## The folder

Name it `spotter_` followed by the name you want in the list, with no spaces:
`spotter_Sam` shows up as **Sam**.

```
spotter_Sam\
    car_left\
        1.wav
        2.wav
        3.wav
    car_right\
    clear_left\
    clear_right\
    clear_all_round\
    in_the_middle\
    three_wide_on_left\
    three_wide_on_right\
    still_there\
radio_check_Sam\          (optional)
    test\
        1.wav
```

## The calls

Each folder holds the recordings for one call. File names don't matter.

| Folder | When it plays | Say something like |
|---|---|---|
| `car_left` | A car has just come alongside on your left | *"Car left"* |
| `car_right` | A car has just come alongside on your right | *"Car right"* |
| `clear_left` | The car on your left has gone | *"Clear left"* |
| `clear_right` | The car on your right has gone | *"Clear right"* |
| `clear_all_round` | You were in the middle of three wide and both cars have gone | *"Clear all round"* |
| `in_the_middle` | Cars on both sides | *"Three wide, you're in the middle"* |
| `three_wide_on_left` | Two cars on your right - you're on the left of the three | *"Three wide, you're on the left"* |
| `three_wide_on_right` | Two cars on your left - you're on the right of the three | *"Three wide, you're on the right"* |
| `still_there` | A reminder while a car stays alongside | *"Still there"* |

A few things to know:

- **`still_there` has no side.** It's used for a car on either side, so don't say left or right
  in it.
- **`clear_left` doesn't always mean all clear.** Coming out of the middle of three wide,
  *"clear left"* plays while the car on your right is still there. Keep it to the side that
  cleared.
- **You don't need every folder.** Any call your pack doesn't have is said by Gary's own spotter.
  `car_left`, `car_right` and `clear_all_round` are the ones that matter most - a pack needs at
  least one of them to show up at all.
- **CrewChief has a few more.** `car_inside`, `car_outside`, `clear_inside`, `clear_outside`,
  `three_wide_on_inside` and `three_wide_on_outside` are CrewChief's oval calls. Gary doesn't use
  them yet, but include them if you want the pack to be complete in CrewChief.

## Recording

- **Format:** `.wav`, mono, 16-bit. Any sample rate - 44.1 kHz is fine. Other formats aren't
  loaded.
- **Keep calls short.** Under a second for `car_left`, `car_right` and the clears. A call that
  can't start within a second of the car arriving is dropped, so a long recording can cost you
  the next call. `still_there` and `in_the_middle` can run a little longer.
- **Trim the silence at the start.** Every bit of silence before the word is a delay on track.
- **Record several takes of each call.** Three to five is plenty. Gary shuffles them and never
  plays the same one twice in a row, which is most of what stops a spotter sounding like a loop.
- **Don't worry about the exact volume.** Gary brings every recording to the crew chief's level.
  Do keep each take clean and not clipped.
- **Radio sound is up to you.** Record it clean or with a radio effect. Gary's own click is off
  for packs by default; drivers can turn it on in Settings.

## Radio check (optional)

Put a few short lines in `radio_check_Name\test` - *"Radio check, you hearing me?"* - and Gary
plays one when it starts with your pack selected. The name after `radio_check_` must match the
one after `spotter_`.

## Trying it

1. Put both folders in `Documents\Gary\SpotterPacks`.
2. **Settings → Spotter voice**, pick **Name (voice pack)**, **Save**, then **Stop** and **Start**.
3. Restart Gary to hear your radio check.

Gary's log shows which pack it loaded, and the caption box can show each spotter call as it
plays, which helps you check that the right recording comes at the right moment.

## Sharing it

Zip the `spotter_` and `radio_check_` folders together. Tell people to unzip them into
`Documents\Gary\SpotterPacks`, or into CrewChief's `%LOCALAPPDATA%\CrewChiefV4\Sounds\voice`
folder so both apps get it. See [Spotter voice packs](spotter-packs.html).
