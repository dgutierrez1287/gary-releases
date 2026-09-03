# Gary

A crew chief for iRacing. He watches your telemetry and tells you the things you'd otherwise
be reading off an overlay — lap times and where you found or lost them, fuel, gaps, flags,
incidents, and the whole pit sequence from the limiter to "go, go, go".

You can also just ask him things. Hold your push-to-talk button and say *"what's my delta"*,
*"fuel usage"*, *"what's my last lap"*.

**This is an alpha.** It works, it's in daily use, and it will still get things wrong.

---

## Install

1. Download **`Gary-win-Setup.exe`** from [the latest release](../../releases/latest).
2. Run it.

**Windows will warn you.** You'll get *"Windows protected your PC"* — click **More info**, then
**Run anyway**. This happens because the installer isn't code-signed, and a signing certificate
costs a few hundred pounds a year for a project that isn't making any money. Nothing is wrong;
it just means Microsoft doesn't know who built it.

No admin rights needed — it installs to your user account. You don't need to install .NET or
anything else; everything is bundled.

Updates are automatic. Gary checks on launch, downloads quietly in the background, and applies
the new version next time you start him. He never restarts himself mid-session.

---

## First run

Gary starts talking to iRacing on his own. You should hear a radio check from the crew chief and
the spotter — if you do, audio is working.

Two things worth setting up straight away, in **Settings**:

**Push-to-talk.** Click **Map...** next to *Push-to-talk button* and press a button on your wheel.
Without one mapped, Gary's microphone is **always listening**, which mostly means he'll pick up
you talking to someone else and try to answer.

**Your name**, if you want him to use it on urgent calls.

The **Always on top** tickbox on the front page is handy if you run him on a second monitor and
your sim keeps covering him up.

---

## Voices

Two voices ship with Gary — **Alan** for the crew chief and **Sophie** for the spotter. Fifteen
more are available in Settings.

Downloading one takes about 60 MB and a minute or two, because Gary also has to render the
spotter's phrases in that voice. **Gary restarts himself when a download finishes** — that's
expected, and it's the only way the new voice takes effect.

Any voice can be either persona, including the same one for both. **Clear unused** deletes voices
you tried and didn't keep.

---

## What works, and what doesn't

Working and in regular use: lap times with a sector-by-sector breakdown, live delta, fuel use
and warnings, off-track and incident calls, flags, gaps to the cars around you, the full pit
sequence, and voice questions.

Rough or unproven:

- **Le Mans Ultimate** support is partial. Some things are wired, plenty aren't.
- **Blue flags and lapped traffic** have never actually fired in testing — nobody has managed to
  get lapped yet. They may not work at all.
- **Rally and dirt** handling exists but has barely been driven.
- Pit stop time estimates need a few stops at a given car and track before Gary will quote one.
  He'll tell you when he hasn't got enough to go on.


---

## What you can ask him

Hold your push-to-talk button and speak. Each of these has several accepted wordings — the
examples below are just one each, and Gary is fairly forgiving about how you phrase it.

**Your lap**

| Ask | You get |
|---|---|
| *"what's my delta"* | How far up or down you are on your best |
| *"last lap"* | The time you just did |
| *"best lap"* | Your best of the session |
| *"sector times"* | Your last sector (LMU only) |

**Fuel**

| Ask | You get |
|---|---|
| *"how's my fuel"* | Laps of fuel left |
| *"fuel usage"* | Last lap, best, worst and stint average |
| *"fuel to the end"* | Sets the pit stop to fill exactly enough to finish |

**Race**

| Ask | You get |
|---|---|
| *"what position am I in"* | Your position, in class |
| *"gap ahead"* / *"gap behind"* | Time to the car either side |
| *"who's leading"* | The leader |
| *"how long is left"* | Time or laps remaining |
| *"status update"* | Position, gaps and fuel in one go |
| *"do I need another stop"* | Whether you can make the finish |

**The car**

| Ask | You get |
|---|---|
| *"how's the car"* | Damage |
| *"tyre wear"* / *"tyre temps"* | Tyre condition (LMU only) |
| *"how many incidents"* | Your incident count |
| *"any penalties"* | Penalty status |

**Conditions**

*"is it raining"*, *"track temp"*, *"air temp"*, *"is the track wet"*.

**Other drivers** — by name, e.g. *"what's Verstappen's last lap"*, *"what position is Hamilton"*,
*"what's their iRating"*, *"what tyres are they on"*.

**Briefings**, if you want several things at once: *"tell me about my fuel"*, *"tell me about the
tyres"*, *"tell me about the race"*, *"tell me about the car"*.

**Pit stops** — *"set up my pit stop"* walks you through it. You can also set things directly:

- Tyres: *"four tyres"*, *"fronts only"*, *"rears only"*, *"left side"*, *"change the right front"*,
  *"no tyres"*
- Fuel: *"add fuel"*, *"no fuel"*, or *"fuel to the end"* to work out the amount for you
- Also: *"tearoff"*, *"fast repair"*, *"clear the pit stop"*

**Telling him to shut up**

| Say | Effect |
|---|---|
| *"quiet mode"* / *"pipe down"* / *"shut up"* | Only urgent calls get through |
| *"back to normal"* | Normal chatter |
| *"keep me informed"* | Everything, no pacing limits |
| *"mute the spotter"* / *"spotter on"* | Spotter only |
| *"race prep on"* / *"race prep off"* | Stint-practice mode |

There is also one command that does nothing useful whatsoever. You'll find it.

---

## Settings

**Session**

- **Game** — iRacing or Le Mans Ultimate.
- **Always on top** — keeps the window above your sim. Handy on a second monitor.

**In the Settings window**

- **Your name** — used on urgent calls only ("Diego! Box this lap"). Leave blank to skip it.
- **Spotter "still there" repeat** — how often the spotter reminds you a car is alongside.
  Seconds. Lower is more insistent.
- **Fuel warning laps** — when to warn, as laps of fuel remaining. `4,2` warns twice.
- **Auto fuel margin** — spare laps added by *"fuel to the end"*, so you aren't finishing dry.
- **Braking zone quiet threshold** — how hard you have to be braking before Gary holds routine
  chatter. Percent of full brake. Lower means he shuts up more readily.
- **Temperature unit** and **distance unit** — Celsius/Fahrenheit, metres/feet, for spoken calls.
- **Tyre wear warning**, **tyre cold/hot thresholds** — LMU only.
- **Track temp change to announce** — how big a swing is worth mentioning.
- **Crew chief voice** and **spotter voice** — see above. Any voice can be either.
- **Radio voice effect** and **radio click** — cosmetic. Turn them off if they annoy you.
- **Start minimized to tray**, **start automatically on launch** — both on by default.

Settings take effect on **Stop then Start**, or on the next launch. Changing a voice restarts
Gary by itself.

---

## When something goes wrong

**Send the log.** It's the single most useful thing, and it contains everything needed to work out
what happened — including which build you were on.

```
%AppData%\Gary\logs
```

Newest file, one per launch, last twenty kept. Paste the path into Explorer's address bar.

Along with it, say roughly **when** it happened and **what you expected instead**. "Around lap 6 it
said I'd gone off and I hadn't" is enough to find it — timestamps in the log will do the rest.

The version is in Gary's title bar, so a screenshot carries it too.

---

## Where Gary keeps things

Everything is local. Nothing is uploaded anywhere.

```
%AppData%\Gary\settings.json    your settings
%AppData%\Gary\logs\            one log per launch
%AppData%\Gary\voices\          voices you downloaded
%AppData%\Gary\history\         lap and pit stop history he's learned from
```

Deleting `settings.json` resets Gary to defaults. Deleting `history` makes him forget your
reference laps and pit times, and he'll start relearning them.

---

## Uninstall

Windows **Settings → Apps → Installed apps → Gary**. That removes the program. Your settings,
logs and history stay in `%AppData%\Gary` — delete that folder too if you want it all gone.
