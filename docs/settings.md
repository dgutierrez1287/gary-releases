---
title: Settings
nav_order: 6
---

# Settings

Settings take effect on **Stop then Start**, or on the next launch. Changing a voice or your
push-to-talk button restarts Gary by itself.

## On the front page

| Setting | What it does |
|---|---|
| **Game** | iRacing or Le Mans Ultimate |
| **Always on top** | Keeps Gary above your sim window - handy on a second monitor |
| **Push-to-talk button** | **Map...** a button on your wheel or button box. No button mapped = Gary doesn't listen. See [First run](first-run.html#push-to-talk) |
| **Listen without a push-to-talk button** | Hands-free always-on mic. Off by default - it acts on anything it hears |
| **Microphone** / **Speaker** | Which devices Gary listens on and talks through |
| **Garage61** | **Connect** signs you in through your browser (Gary never sees your password); **Laps from** picks whose laps you chase - All drivers or one of your teams. iRacing only - see [Chase a Garage61 lap](features/iracing.html#chase-a-garage61-lap) |
| **Voice recognition** | *Modern* uses your Windows default mic; *Classic* lets you pick one. If commands feel unreliable, try the other |

## In the Settings window

**Voices on or off**

| Setting | What it does |
|---|---|
| **Crew chief calls** | The crew chief's own calls. Off leaves the spotter on its own - questions you ask by push-to-talk are still answered |
| **Spotter calls** | The spotter. Off leaves the crew chief on his own. *"Spotter on"* brings it back for the session |

**You**

| Setting | What it does |
|---|---|
| **Your name** | Used on the greeting and urgent calls ("Diego! Box this lap."). Blank to skip it |
| **Let the crew chief swear (occasionally)** | Exactly what it says |

**Spotter**

| Setting | What it does |
|---|---|
| **Spotter "still there" repeat** | How often the spotter reminds you a car is still alongside, in seconds. Lower is more insistent |

**Fuel**

| Setting | What it does |
|---|---|
| **Fuel warning laps** | When to warn, as laps of fuel left. `4,2` warns twice |
| **Auto fuel margin** | Spare laps added on top of *"fuel to the end"* and automatic fuelling |
| **Let Gary set my fuel at every race stop** | One tickbox per sim. When you turn into the pits in a race, Gary sets fuel (or Virtual Energy in LMU) for the end plus your margin, and tells you what he set. Say *"fuel margin two laps"* to change the margin for one stop |
| **Track Virtual Energy** | **LMU**, experimental. Reads a separately installed community plugin for extra energy detail - turn off if it misbehaves |

**Tyres (LMU)**

| Setting | What it does |
|---|---|
| **Tyre wear warning** | Wear percentage that triggers a warning |
| **Tyre cold / hot threshold** | Temperatures for the tyre temp calls |

**Calls**

| Setting | What it does |
|---|---|
| **Sector reporting** | *End of lap* - one rundown after each lap. *Live, every sector* - each called as you finish it. *Live, notable only* - live, but quiet unless it's worth hearing. Can also be changed by voice |
| **Braking zone quiet threshold** | How hard you have to be braking, as a percent of full brake, before Gary holds routine chatter. Lower means he shuts up more readily |
| **Track temp change to announce** | How big a swing is worth mentioning |
| **Temperature unit** | Celsius or Fahrenheit |
| **Distance unit** | Metres or feet, for spoken calls |

**Voices** - see [First run](first-run.html#voices).

| Setting | What it does |
|---|---|
| **Crew chief voice** / **Spotter voice** | Any voice, either role. Each one is described in the dropdown (accent, male or female). **Download selected voices** fetches ones you don't have yet; **Clear unused** deletes ones you're not using |
| **Better voice understanding (Whisper)** | When Gary doesn't catch a push-to-talk command, a second listener on your PC has another go, so more ways of saying things work. Downloads a 78 MB model the first time. Off by default |
| **Radio voice effect** | Makes the crew chief sound like he's on the radio. Urgent calls are never degraded |
| **Radio click and squelch on crew chief messages** | Radio click on crew chief messages, with a choice of start sound. Untick it for no click at all - the radio voice effect stays |
| **Radio click and squelch on spotter calls** | The same for the spotter, set separately |
| **Crew chief volume** / **Spotter volume** | 0 to 200%. Above 100% makes the voice louder with the loudest peaks softened rather than clipped - useful if Gary is lost under the iRacing spotter |

**Startup**

| Setting | What it does |
|---|---|
| **Start minimized to tray** | On by default |
| **Automatically start when the app launches** | On by default - Gary connects without you pressing Start |

**Sharing (iRacing)** - see [Pit data & privacy](pit-data.html).

| Setting | What it does |
|---|---|
| **Share pit stop data** | Pit stop timings, so estimates get better for everyone |
| **Share GPS data for tracks that need it** | One clean lap of GPS at tracks still missing corner data |
| **Share tyre wear data** | One row per stint, to build a tyre wear model |

**Developer**

| Setting | What it does |
|---|---|
| **Log performance timing** | Writes how much work Gary is doing to the log once a minute. Leave off unless asked |
| **Show the test checklist button** | A small always-on-top checklist window, for testing |

## Next

**[Pit data & privacy →](pit-data.html)**
