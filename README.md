# Starboard - play many games from the PortMaster library on your Android handheld


PortMaster put hundreds of free, community-ported games on Linux handhelds. Starboard brings many (but not all) of those games to Android by running them in a real Linux environment under the bonnet. Many games work great, some are playable (but some are flat-out incompatible!). [Check the current compatibility list](https://get-starboard.app/compatibility).

![Starboard Launcher](https://get-starboard.app/images/library.png)

![Celeste on Starboard](https://get-starboard.app/images/ingame.png)

## Download

The easiest way to install and stay up to date is with [Obtainium](https://github.com/ImranR98/Obtainium) - it auto-updates Starboard whenever a new release ships:

[<img src="https://raw.githubusercontent.com/ImranR98/Obtainium/main/assets/graphics/badge_obtainium.png" alt="Get it on Obtainium" height="60">](https://apps.obtainium.imranr.dev/redirect.html?r=obtainium%3A%2F%2Fapp%2F%257B%2522id%2522%253A%2522org.force9.starboard%2522%252C%2522url%2522%253A%2522https%253A%252F%252Fgithub.com%252Fget-starboard%252Fstarboard%2522%252C%2522author%2522%253A%2522get-starboard%2522%252C%2522name%2522%253A%2522Starboard%2522%252C%2522otherAssetUrls%2522%253Anull%252C%2522apkUrls%2522%253Anull%252C%2522preferredApkIndex%2522%253A0%252C%2522additionalSettings%2522%253A%2522%257B%255C%2522includePrereleases%255C%2522%253Afalse%252C%255C%2522fallbackToOlderReleases%255C%2522%253Atrue%252C%255C%2522filterReleaseTitlesByRegEx%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522filterReleaseNotesByRegEx%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522verifyLatestTag%255C%2522%253Afalse%252C%255C%2522sortMethodChoice%255C%2522%253A%255C%2522date%255C%2522%252C%255C%2522useLatestAssetDateAsReleaseDate%255C%2522%253Afalse%252C%255C%2522releaseTitleAsVersion%255C%2522%253Afalse%252C%255C%2522github-creds%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522GHReqPrefix%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522trackOnly%255C%2522%253Afalse%252C%255C%2522versionExtractionRegEx%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522matchGroupToUse%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522versionDetection%255C%2522%253Atrue%252C%255C%2522releaseDateAsVersion%255C%2522%253Afalse%252C%255C%2522useVersionCodeAsOSVersion%255C%2522%253Afalse%252C%255C%2522apkFilterRegEx%255C%2522%253A%255C%2522%255C%255C%255C%255C.apk%2524%255C%2522%252C%255C%2522invertAPKFilter%255C%2522%253Afalse%252C%255C%2522autoApkFilterByArch%255C%2522%253Atrue%252C%255C%2522appName%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522appAuthor%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522shizukuPretendToBeGooglePlay%255C%2522%253Afalse%252C%255C%2522allowInsecure%255C%2522%253Afalse%252C%255C%2522exemptFromBackgroundUpdates%255C%2522%253Afalse%252C%255C%2522skipUpdateNotifications%255C%2522%253Afalse%252C%255C%2522about%255C%2522%253A%255C%2522Run%2520PortMaster%2520games%2520on%2520Android%252C%2520no%2520root%2520required.%255C%2522%252C%255C%2522refreshBeforeDownload%255C%2522%253Afalse%252C%255C%2522includeZips%255C%2522%253Afalse%252C%255C%2522zippedApkFilterRegEx%255C%2522%253A%255C%2522%255C%2522%257D%2522%252C%2522categories%2522%253A%255B%2522Launcher%2522%255D%252C%2522overrideSource%2522%253A%2522GitHub%2522%252C%2522allowIdChange%2522%253Afalse%257D)

Prefer to install manually? Grab the latest signed APK straight from the [Releases page](https://github.com/get-starboard/starboard/releases/latest).

## Features

- **One-tap PortMaster catalogue** - browse, search and install ports from the live catalogue, with artwork and featured picks, all in a single controller-friendly library.
- **Dual-screen support** - a companion UI renders on a second screen if available, while your primary screen keeps full gamepad control.
- **GPU acceleration (very experimental!)** - flip a per-port *Run on GPU* switch to route OpenGL through your device's actual GPU (Adreno etc) via virgl instead of software rendering.
- **ES-DE integration** - installed ports register themselves into [EmulationStation DE](https://es-de.org/) if enabled, complete with cover art and descriptions.
- **On-screen touch controls** - a virtual gamepad overlay for playing without physical buttons.
- **No root required**


## Compatibility

- **Android gaming handhelds** with an `arm64-v8a` (ARM64) CPU - Retroid Pocket, AYN Thor, Mangmi Air X, and similar devices. Phones work too, but occasionally cause issues with some ports. 
- Compatibility varies per port as the project matures - [check the current compatibility list](https://get-starboard.app/compatibility).

Real-world compatibility reports are hugely valuable - please make use of the in-app feedback system!

## Community & Support

- **Issues & feature requests:** [GitHub Issues](https://github.com/get-starboard/starboard/issues)
- **Website:** [get-starboard.app](https://get-starboard.app)

## Credits

Starboard stands on a lot of community shoulders. Huge thanks to:

- **Every game's authors** - Without those authors, none of this would be possible.
- [**PortMaster**](https://portmaster.games) - the ports themselves, and the community that builds and tests them. 
- [**proot**](https://proot-me.github.io) - userspace chroot.
- [**SDL2**](https://www.libsdl.org), [**Mesa / OSMesa**](https://www.mesa3d.org), [**ALSA**](https://www.alsa-project.org) - the Linux media stack many games are built against, and what Starboard uses to render them.
- [**Debian**](https://www.debian.org) - the Linux execution environment Starboard uses.


## FAQ

<details>
<summary><strong>What is Starboard?</strong></summary>

It's a catalog manager and execution environment for games in the [PortMaster catalog](https://portmaster.games).

</details>

<details>
<summary><strong>Do all games from the PortMaster library work?</strong></summary>

No. View the [compatibility list](https://get-starboard.app/compatibility) for the most up to date information.

It's incredibly unlikely that we'll ever get to a place where *all* PortMaster games will work on Starboard. The architectural differences between Android and Linux (where PortMaster ports were designed to run), and the methods used to make them run in Starboard, simply don't scale to some of the more demanding or hardware-specific games.

Furthermore, some games don't make sense to put effort into making them work (if they don't already), either because native Android ports already exist, or because they were Android games in the first place.

</details>

<details>
<summary><strong>Why did you build Starboard?</strong></summary>

For the love of gaming, and to give back to the community from which I've gained so much enjoyment. Literally no other agenda.

I was sat one day thinking it would be cool if games in the PortMaster catalog were playable on Android, so I got to work on a tech spike to see if I could make a simple [SDL](https://www.libsdl.org) game like [Simple Sokoban](https://simplesok.sourceforge.net/) run. Lo-and-behold my idea worked, and it grew legs from there.

</details>

<details>
<summary><strong>Is this an official PortMaster project?</strong></summary>

Nope.

</details>

<details>
<summary><strong>Did you use AI to help build Starboard?</strong></summary>

Yes. The speed at which LLMs enable software engineering, it would be crazy not to. Non-AI purists will tell you I'm wrong, but this is the state of the world in 2026 - engineers use LLMs to go way faster than ever before. This is different to 'vibe coding' - where non-engineers build stuff without any care for the final result.

If this bothers you, feel free to skip over Starboard, I don't mind. However, you might also want to stop buying from [Amazon](https://the-decoder.com/amazons-ai-assistant-saves-4500-years-of-development-time-ceo-andy-jassy-says/) (whose AI platform saved them 4,500 years of developer work), stop buying from stores that use [Stripe](https://stripe.dev/blog/minions-stripes-one-shot-end-to-end-coding-agents) as a payment processor (whose AI minions merge over a thousand PRs a week), and steer clear of [Google](https://fortune.com/2024/10/30/googles-code-ai-sundar-pichai/) (over a quarter of their new code is AI-generated) while you're at it.

</details>

<details>
<summary><strong>Will Starboard be open source?</strong></summary>

Yes. See [this issue](https://github.com/get-starboard/starboard/issues/1).

</details>

## Licence

The Starboard APKs distributed from this repo are free to download and use, but the source is not yet public. See [this issue](https://github.com/get-starboard/starboard/issues/1).

The Linux runtime image build is open at [get-starboard/starboard-runtime](https://github.com/get-starboard/starboard-runtime).

Third-party components bundled inside the APK retain their original licences; full attributions ship inside the app under "About → Third-party notices."
