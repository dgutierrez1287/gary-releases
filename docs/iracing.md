---
title: iRacing
parent: Features
nav_order: 1
permalink: /features/iracing.html
---

# iRacing

Everything under [In both sims](./#in-both-sims), plus:

## Shared pit and fuel data

Every Gary install shares its pit stops anonymously (you can turn it off - see
[Pit data & privacy](../pit-data.html)). That pool is what lets Gary say useful things at a car
and track you've never driven before:

- **What a stop costs** - time lost in the pit lane, with and without tyres, dry and wet.
- **What a drive-through costs** - so a black flag comes with *"a drive-through here costs about
  22 seconds."*
- **Fuel burn** - until you've timed your own lap, automatic fuelling and *"fuel to the end"*
  use what other drivers' cars burned there, and tell you so.

Your own laps take over as soon as there are some.

## Your best in these conditions

Gary keeps every clean lap you drive with the conditions it was set in, and compares you against
your best **in conditions like now's**, not a lap from a cool morning on a rubbered-in track:

- **Wet and dry never mix.** Dry, damp, wet and very wet each have their own best - and damp on
  slicks is kept apart from damp on wets.
- **Track temperature within 10%** of what it is now - a narrow window when it's cool, a wider one
  when it's hot. Below 10 °C it's one cold window.
- **In practice and qualifying**, the sector rundown at the end of the lap is against your
  fastest lap in these conditions, and live sector calls against your best sectors in them. If
  you've nothing in these conditions yet, he says so and uses your overall best.
- **In a race**, they're against your best lap of that race - fuel, tyre wear and traffic make a
  race lap a different thing from a hotlap.

**Race pace.** In a race Gary also watches your last three clean laps against your best in these
conditions. If you're well off it - more than 2% - he tells you, says it again if nothing changes
(no more than every 10 laps), and tells you when you're back on it. Laps with traffic, a caution,
an off, fuel saving or cold tyres after a stop don't count. With *Let the crew chief swear* on, he
gets a lot less polite about it.

The more you drive a car and track, the more conditions Gary has a best for. Your first session
at a combination compares against your overall best until the laps build up.

## Where is everyone

Ask where any car is and Gary tells you the corner they're in - or the one they're closest to,
or the straight they're on - their position, and the gap to you:

> *"Max Driver, P3 in class, is coming through Remus, 2.3 seconds up the road from you."*

In a multiclass race positions mean **your class** unless you say *"overall"*. A car a lap or more
up or down gets both: *"a lap down, 8.0 seconds behind you on the road"*. A faster car on your
lap that's about to lap you is *"behind you"*, not most of a lap up the road.

By name (*"where is Verstappen"*), by position (*"where's P3"*), the leader, your class leader,
the nearest car or the leader of a class (*"where's the nearest GTP"*), or the nearest car from a
faster or slower class. See [Voice commands](../voice-commands.html#race).

## Chase a Garage61 lap

Connect Garage61 on Gary's front page and, in an **offline test session**, ask *"find me a
target"*. Gary finds other drivers' best laps in your car at this track, in conditions like
yours - track and air temperature, rubber, wet or dry - and picks one a little quicker than your
best:

> *"Out of 8 drivers, your target is Alex Moreno's 1 minute 11.37, seven tenths quicker than your best."*

Then every clean lap is checked against it. Your lap time first, then either where you stand
against them, sector by sector, or:

> *"You beat Alex Moreno's 1 minute 11.37. Next up Sam Ortiz's 1 minute 10.40."*

- *"Go for the fastest"* skips straight to the quickest lap found; *"next target"* moves you one
  step up; *"what's my target"* tells you who and how far off.
- Sector comparisons follow your sector setting - after the lap, or live as you cross each sector
  (*"sector by sector"*). While you have a target, they replace the usual comparison with your own best.
- **Laps from** on the front page picks whose laps: **All drivers**, or one of your Garage61 teams.
  Change it any time, even mid-session.
- If there aren't many laps in your conditions, Gary widens the search and says so.
- Offline testing only - never in practice, where there are other cars on track.
- Gary asks Garage61 as little as it can: nothing until you ask for a target, searches are
  remembered for a day, and a session never makes more than a handful of requests.

A free Garage61 account is enough - it's sector times, not telemetry.

## Hotlapping with Active Reset

Use iRacing's Active Reset and Gary notices, and treats the rest of the session as hotlapping.
Resetting puts the car back as it was when you saved the point - fuel included - so from then on
he only talks about what matters: **lap times, sectors, your Garage61 target**, and whether an
off cost you the lap. No fuel warnings, no "tidy it up". The bit of lap before you cross the line
after a reset never counts; your flying lap starts at the line.

Getting out of the car and back in is fine - hop in, hit reset, go.

## Fuel check on the grid

As a race session starts, Gary checks you're not still on your qualifying fuel - *"Fuel check -
you've only got about 9 laps in, and the race is about 17. Top it up."* Silent when the fuel's fine.

## Pit stops

Set up your stop by voice: *"four tyres"*, *"left side"*, *"add 20 litres"*, *"add 5 laps of
fuel"*, *"tearoff"*, *"fast repair"*, *"clear the pit stop"* - or *"set up my pit stop"* to be
walked through it. *"What's my stop set to"* reads it back.

## Tyres

- **Two-compound rule.** For the cars that have more than one dry compound (IR18, iR-01, and the
  F1 cars), Gary keeps track of whether you've run both, and reminds you before it's too late.
- **Last stop's tyres.** iRacing only measures tread in the box - *"how were my tyres last stop"*
  reads what it measured, corner by corner. Handy in practice, and on ovals with back-to-back
  cautions.
- **Limited tyres on ovals.** Left and right sides are counted separately, the way iRacing does.
  You hear what you've got at the start and what's left after each stop, and get a warning when
  you're running short on one side.

## Ovals

- Full-course cautions, one to green, green held, and restart format (single or double file,
  whatever iRacing says it is).
- **Getting into line.** iRacing freezes the order when the caution comes out, so the field on
  track rarely matches it. Gary tells you who to let by and who you can pass to get into your
  spot.
- **Your restart spot** at one to go - *"row 4"* for double file, *"7th in line"* for single.
- **Pit or not.** A few seconds after the caution, whether you've got fuel to the end, whether
  one fill makes it (good time to pit), or whether topping off now pushes your next stop back.
- The free pass, being waved around, and being sent to the tail of the line.
- Penalty laps counted the oval way - only green-flag laps.

## Incidents

Your incident count, a warning as you get close to the limit, and *"where did I pick up my
incidents"* for a rundown.

## Drivers

iRating and licence for you and the cars around you, and strength of field (per class, in
multiclass).

## Team races

When a teammate is driving, Gary goes quiet - he's not going to talk you through someone else's
stint. Their stops and stints still feed the shared data.

If you're saving fuel to drop a stop, he works out the target in the box before you climb out and
says it once as your teammate takes over: *"Fuel save target for your teammate is 2.4 liters a lap
to the end. Pass that on."* If they run Gary too, they can say *"our fuel save target is 2 point
4"* and his Gary keeps them on it. When you're back in, the save carries on, re-worked from what's
actually in the tank.

## Next

**[Le Mans Ultimate →](lmu.html)**
