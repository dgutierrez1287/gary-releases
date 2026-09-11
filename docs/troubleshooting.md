---
title: Troubleshooting
nav_order: 8
---

# Troubleshooting

## Send the log

It's the single most useful thing you can do, and it contains everything needed to work out
what happened — including which build you were on.

**The easy way:** click **Logs** in the Tools row on Gary's front page. It lists every kept log
with a readable session time, how long the run was, and a one-line summary (version, game,
track, session type) — pick the right one, then **Open** it or **Show in folder**.

**The manual way:** paste this into Explorer's address bar:

```
%AppData%\Gary\logs
```

Newest file, one per launch, last twenty kept.

Along with the log, say roughly **when** it happened and **what you expected instead**. "Around
lap 6 it said I'd gone off and I hadn't" is enough to find it — timestamps in the log do the
rest. The version is in Gary's title bar, so a screenshot carries it too.

{: .note }
A log can contain personal information — see [Pit data & privacy](pit-data.html#a-log-does-contain-personal-information)
before sending one somewhere public.

## Where Gary keeps things

Almost everything is local:

```
%AppData%\Gary\settings.json    your settings
%AppData%\Gary\logs\            one log per launch
%AppData%\Gary\voices\          voices you downloaded
%AppData%\Gary\history\         lap and pit stop history he's learned from
%AppData%\Gary\pit-data\        your installation's pit-data upload token
```

Deleting `settings.json` resets Gary to defaults. Deleting `history` makes him forget your
reference laps and pit times, and he'll start relearning them.

## Common issues

**Voice commands feel unreliable.** Try **Settings → Voice recognition → Classic**, and map
push-to-talk to a plain button off your wheel or button box rather than one routed through a
remapper — a remapper can make the button read as held-down or double-triggered in ways Gary
can't tell apart from a real press.

**Gary is listening to everything, not just when you hold the button.** Check **Settings → your
push-to-talk button is actually mapped**. With nothing mapped, Gary defaults to *not* listening
at all — but if *Listen without a push-to-talk button* got ticked at some point, that's the
hands-free mode, and it does act on anything it hears. Untick it.

**A voice download finished and Gary restarted on its own.** Expected — that's the only way a
new voice actually takes effect.

## Next

Back to **[Home](index.html)**, or check **[What works, and what doesn't](whats-working.html)**
before assuming something's broken.
