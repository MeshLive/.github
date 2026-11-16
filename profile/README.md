<div align="center">

<img src="https://raw.githubusercontent.com/MeshLive/meshlive-android/main/docs/brand/meshlive-icon-1024.png" width="96" alt="MeshLive icon" />

# MeshLive

Video calls, voice calls and livestreams with people nearby, over a Bluetooth mesh.<br/>
Every phone passes it on, so you reach further than Bluetooth alone.<br/>
No internet, no SIM, no account.

<br/>

<p>
  <img alt="License GPLv3" src="https://img.shields.io/badge/License-GPLv3-FF3B30?style=flat&logo=gnu&logoColor=white" />
  <img alt="Data CC BY 4.0" src="https://img.shields.io/badge/Data-CC%20BY%204.0-FF3B30?style=flat" />
</p>

<a href="https://apps.apple.com/app/id6834136798"><img alt="Download on the App Store" src="https://toolbox.marketingtools.apple.com/api/v2/badges/download-on-the-app-store/black/en-us" height="40" /></a>
&nbsp;
<a href="https://play.google.com/store/apps/details?id=io.github.meshlive.app"><img alt="Get it on Google Play" src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" height="60" /></a>
&nbsp;
<a href="https://github.com/MeshLive/meshlive-android/releases/latest"><img alt="Get it on GitHub" src="https://raw.githubusercontent.com/Kunzisoft/Github-badge/main/get-it-on-github.png" height="60" /></a>
&nbsp;
<a href="https://apps.obtainium.imranr.dev/redirect?r=obtainium://add/https://github.com/MeshLive/meshlive-android"><img alt="Get it on Obtainium" src="https://raw.githubusercontent.com/ImranR98/Obtainium/main/assets/graphics/badge_obtainium.png" height="60" /></a>

<p><b>Downloads for every platform, demo videos and help: <a href="https://meshlive.github.io">meshlive.github.io</a></b></p>

<sub>Free · open source · <a href="https://meshlive.github.io/privacy/">Privacy policy</a></sub>

</div>

MeshLive sends voice and video calls and live video or audio directly between nearby devices over Bluetooth, and passes them along through other phones that run it. Calls and streams are end-to-end encrypted; messaging is experimental. Calls can also reach a contact who is out of range through other phones in between (beta). There is no account, no server and no analytics, so it keeps working off-grid, on a hike, at a festival, in a basement or wherever the network is down.

## Apps

One protocol, several apps: an iPhone, an Android phone and a Windows PC running MeshLive call each other and watch each other's streams.

| Platform | Repository | Status |
| --- | --- | --- |
| **iPhone** | [meshlive-apple](https://github.com/MeshLive/meshlive-apple) | **Available** (1.0) on the [App Store](https://apps.apple.com/app/id6834136798), iOS 17 or later. Calls and livestreams with Android phones and the Mac were tested on an iPhone 12. |
| **Android 10+** | [meshlive-android](https://github.com/MeshLive/meshlive-android) | **Beta** (0.5.0-beta). On [Google Play](https://play.google.com/store/apps/details?id=io.github.meshlive.app), [GitHub releases](https://github.com/MeshLive/meshlive-android/releases/latest) and [Obtainium](https://apps.obtainium.imranr.dev/redirect?r=obtainium://add/https://github.com/MeshLive/meshlive-android). The reference implementation: it holds the protocol specification, test vectors and host tools. |
| **Windows** | [meshlive-windows](https://github.com/MeshLive/meshlive-windows) | **Beta** (0.3.1). Unsigned tester zip on [GitHub releases](https://github.com/MeshLive/meshlive-windows/releases/latest). Calls with Android phones passed hands-on checks in both directions; watching and going live are experimental and off by default (see its README). Microsoft Store: coming soon. |
| **Mac** | [meshlive-apple](https://github.com/MeshLive/meshlive-apple) | **Coming soon** to the Mac App Store. A native Mac app in the same repository as the iPhone app; voice and video calls with Android phones work in both directions. Build from source meanwhile. |
| **Benchmarks** | [meshlive-benchmarks](https://github.com/MeshLive/meshlive-benchmarks) | Measured results on real Android phones, with inputs you can regenerate (CC BY 4.0). Baseline published; the data shows that not every case passes yet. |
| **Website** | [meshlive.github.io](https://meshlive.github.io) | Overview, [privacy policy](https://meshlive.github.io/privacy/) and [child safety standards](https://meshlive.github.io/child-safety/). |

Every repository's README says what has and has not been tested on its platform.

## Please read before relying on it

MeshLive has not had an independent security review, and the Android and Windows apps are beta. The ID a phone broadcasts is random and changes every 15 minutes (a Mac uses its fixed Bluetooth address; each app's privacy page says what it broadcasts), but a live stream shows its source to everyone who watches, and anyone whose call you accept learns who you are (a stranger who calls you must prove who they are before your video and audio are sent). Do not rely on it where your safety depends on it. What nearby phones can and cannot see is explained in the [privacy document](https://github.com/MeshLive/meshlive-android/blob/main/docs/privacy.md).

## Ways to help

- **Test on your phone or PC** and file a device report: the Android, Windows and Apple repositories have a form on their **New issue** page. Reports where everything worked are as useful as failures.
- **Report bugs** with both devices, their OS versions and the app version.
- **Question or reproduce the benchmark results** in [meshlive-benchmarks](https://github.com/MeshLive/meshlive-benchmarks).
- **Security problems** go through each repository's private **Report a vulnerability** route, never a public issue. See the [security policy](https://github.com/MeshLive/.github/blob/main/SECURITY.md).

Start with the [contributing guide](https://github.com/MeshLive/.github/blob/main/CONTRIBUTING.md), and please follow the [code of conduct](https://github.com/MeshLive/.github/blob/main/CODE_OF_CONDUCT.md). Questions: [SUPPORT.md](https://github.com/MeshLive/.github/blob/main/SUPPORT.md), or write to [meshlive.dev@gmail.com](mailto:meshlive.dev@gmail.com).

<sub>Apple, the Apple logo and iPhone are trademarks of Apple Inc., registered in the U.S. and other countries and regions. App Store is a service mark of Apple Inc. Google Play and the Google Play logo are trademarks of Google LLC.</sub>
