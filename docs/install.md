---
title: Install
nav_order: 2
---

# Install

1. Download **`Gary-win-Setup.exe`** from [the latest release](https://github.com/dgutierrez1287/gary-releases/releases/latest).
2. Run it.

That's it. No admin rights needed — it installs to your user account. You don't need to
install .NET or anything else first; everything is bundled.

{: .warning }
**Windows will warn you.** You'll get *"Windows protected your PC"* — click **More info**,
then **Run anyway**. This happens because the installer isn't code-signed, and a signing
certificate costs a few hundred pounds a year for a project that isn't making any money.
Nothing is wrong; it just means Microsoft doesn't know who built it.

## Updates

Automatic. Gary checks on launch, downloads quietly in the background, and applies the new
version next time you start him. He never restarts himself mid-session — the one exception is
finishing a voice download (see [Voices](first-run.html#voices)), which needs a restart to take
effect and tells you before it happens.

## Uninstall

Windows **Settings → Apps → Installed apps → Gary**. That removes the program. Your settings,
logs and history stay in `%AppData%\Gary` — delete that folder too if you want it all gone. See
[Where Gary keeps things](troubleshooting.html#where-gary-keeps-things) for what's in there.

## Next

**[First run →](first-run.html)** Get push-to-talk mapped and Gary talking.
