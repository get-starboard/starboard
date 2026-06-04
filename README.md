# Starboard - the PortMaster library running on your Android handheld!


Starboard runs unmodified ARM64 Linux game binaries - the same [PortMaster](https://portmaster.games/) ports you know from Linux handhelds - directly on Android gaming handhelds like the Retroid Pocket, AYN Thor and Mangmi Air X. No root, no flashing, no custom firmware required.

![Starboard Launcher](https://get-starboard.app/images/library.png)

![Celeste on Starboard](https://get-starboard.app/images/ingame.png)

## Download

The easiest way to install and stay up to date is with [Obtainium](https://github.com/ImranR98/Obtainium) - it auto-updates Starboard whenever a new release ships:

[<img src="https://raw.githubusercontent.com/ImranR98/Obtainium/main/assets/graphics/badge_obtainium.png" alt="Get it on Obtainium" height="60">](https://apps.obtainium.imranr.dev/redirect.html?r=obtainium%3A%2F%2Fapp%2F%257B%2522id%2522%253A%2522org.force9.starboard%2522%252C%2522url%2522%253A%2522https%253A%252F%252Fgithub.com%252Fget-starboard%252Fstarboard%2522%252C%2522author%2522%253A%2522get-starboard%2522%252C%2522name%2522%253A%2522Starboard%2522%252C%2522otherAssetUrls%2522%253Anull%252C%2522apkUrls%2522%253Anull%252C%2522preferredApkIndex%2522%253A0%252C%2522additionalSettings%2522%253A%2522%257B%255C%2522includePrereleases%255C%2522%253Afalse%252C%255C%2522fallbackToOlderReleases%255C%2522%253Atrue%252C%255C%2522filterReleaseTitlesByRegEx%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522filterReleaseNotesByRegEx%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522verifyLatestTag%255C%2522%253Afalse%252C%255C%2522sortMethodChoice%255C%2522%253A%255C%2522date%255C%2522%252C%255C%2522useLatestAssetDateAsReleaseDate%255C%2522%253Afalse%252C%255C%2522releaseTitleAsVersion%255C%2522%253Afalse%252C%255C%2522github-creds%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522GHReqPrefix%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522trackOnly%255C%2522%253Afalse%252C%255C%2522versionExtractionRegEx%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522matchGroupToUse%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522versionDetection%255C%2522%253Atrue%252C%255C%2522releaseDateAsVersion%255C%2522%253Afalse%252C%255C%2522useVersionCodeAsOSVersion%255C%2522%253Afalse%252C%255C%2522apkFilterRegEx%255C%2522%253A%255C%2522%255C%255C%255C%255C.apk%2524%255C%2522%252C%255C%2522invertAPKFilter%255C%2522%253Afalse%252C%255C%2522autoApkFilterByArch%255C%2522%253Atrue%252C%255C%2522appName%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522appAuthor%255C%2522%253A%255C%2522%255C%2522%252C%255C%2522shizukuPretendToBeGooglePlay%255C%2522%253Afalse%252C%255C%2522allowInsecure%255C%2522%253Afalse%252C%255C%2522exemptFromBackgroundUpdates%255C%2522%253Afalse%252C%255C%2522skipUpdateNotifications%255C%2522%253Afalse%252C%255C%2522about%255C%2522%253A%255C%2522Run%2520PortMaster%2520games%2520on%2520Android%252C%2520no%2520root%2520required.%255C%2522%252C%255C%2522refreshBeforeDownload%255C%2522%253Afalse%252C%255C%2522includeZips%255C%2522%253Afalse%252C%255C%2522zippedApkFilterRegEx%255C%2522%253A%255C%2522%255C%2522%257D%2522%252C%2522categories%2522%253A%255B%2522Launcher%2522%255D%252C%2522overrideSource%2522%253A%2522GitHub%2522%252C%2522allowIdChange%2522%253Afalse%257D)

Prefer to install manually? Grab the latest signed APK straight from the [Releases page](https://github.com/get-starboard/starboard/releases/latest).

## Features

- **One-tap PortMaster catalogue** - browse, search and install ports from the live catalogue, with artwork and featured picks, all in a single controller-friendly library.
- **Dual-screen support** - a companion UI renders on a second screen if available, while your primary screen keeps full gamepad control.
- **GPU acceleration (experimental!)** - flip a per-port *Run on GPU* switch to route OpenGL through your device's actual GPU (Adreno and friends) via virgl instead of software rendering.
- **ES-DE integration** - installed ports register themselves into [EmulationStation DE](https://es-de.org/) if enabled, complete with cover art and descriptions.
- **Runs more than you'd expect** - SDL1 and SDL2, OpenGL and GLES, plus GameMaker (gmloader/YoYo runner) and Xash3D (Half-Life) ports.
- **On-screen touch controls** - a virtual gamepad overlay for playing without physical buttons.
- **No root required**


## Installation

1. Download the latest APK from the [Releases page](https://github.com/get-starboard/starboard/releases/latest).
2. Copy it to your device and install it (you may need to allow installs from unknown sources).
3. Launch Starboard and let it download the runtime on first start.
4. Browse the catalogue, install a port, and play.

## Compatibility

- **Android gaming handhelds** with an `arm64-v8a` (ARM64) CPU - Retroid Pocket, AYN Thor, Mangmi Air X, and similar devices. Phones work too, but occasionally cause issues with some ports. 
- Compatibility varies per port as the project matures 

## Community & Support

- **Issues & feature requests:** [GitHub Issues](https://github.com/get-starboard/starboard/issues)
- **Website:** [get-starboard.app](https://get-starboard.app)

Real-world compatibility reports are hugely valuable - please make use of the in-app feedback system!

## Credits

Starboard stands on a lot of community shoulders. Huge thanks to:

- [**PortMaster**](https://portmaster.games) - the ports themselves, and the community that builds and tests them. Starboard is an independent, unofficial project; not affiliated with or endorsed by PortMaster.
- [**proot**](https://proot-me.github.io) - userspace chroot, no root required.
- [**SDL2**](https://www.libsdl.org), [**Mesa / OSMesa**](https://www.mesa3d.org), [**ALSA**](https://www.alsa-project.org) - the Linux media stack many games are built against.
- [**Debian**](https://www.debian.org) - the rootfs base.
- **Every game's authors** - game ports belong to their respective authors and retain their original licences.

## Support The Project

Starboard itself is built by one person on nights and weekends, around a full time job and a family. If you'd like to help feed my caffeine addiction, the tip jar is at [**ko-fi.com/davestephens**](https://ko-fi.com/davestephens) - entirely optional and hugely appreciated.

## Licence

The Starboard APKs distributed from this repo are free to download and use, but the application remains proprietary: the source is not public, and all rights are reserved. You may not redistribute, modify, decompile, or repackage the APK.

The Linux runtime image build is open at [get-starboard/starboard-runtime](https://github.com/get-starboard/starboard-runtime).

Third-party components bundled inside the APK retain their original licences; full attributions ship inside the app under "About → Third-party notices."
