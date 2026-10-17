# MeshLive

**Voice and video calls, live video and live audio between nearby phones, over Bluetooth, with no internet.**

MeshLive is free and open-source software (GPL-3.0-or-later). Phones talk directly to each other and pass calls and streams along through other nearby phones, with end-to-end encryption, so it keeps working off-grid, in emergencies, or where the internet is down or censored. There is no account, no server and no analytics.

| Repository | What it is | Status |
| --- | --- | --- |
| **[meshlive-android](https://github.com/MeshLive/meshlive-android)** | The Android app (canonical): calls, live video, audio-only live, relaying, the protocol specification, test vectors and tools. [Download the latest release](https://github.com/MeshLive/meshlive-android/releases/latest) | Public beta (0.3.0-beta). Tested on seven Android phones (Android 10 to 16); some phone pairs are still slow. |
| **[meshlive-ios](https://github.com/MeshLive/meshlive-ios)** | The iPhone app, written to the same protocol so iPhones and Android phones can call and watch each other. | Early. Not on the App Store and no binary release. Calls and live video work both ways with Android on a first iPhone; iPhone testers wanted. |
| **[meshlive-benchmarks](https://github.com/MeshLive/meshlive-benchmarks)** | Measured results on real Android phones, with inputs you can regenerate, to compare your own phones against (CC BY 4.0). | Baseline published; not every case passes yet, and the data says so. |

**Please read before relying on it:** MeshLive has not had an independent security review. The ID a phone broadcasts is random and changes every 15 minutes, but a live stream shows its source to everyone who watches, and anyone whose call you accept learns who you are. Use it for testing and feedback, not where your safety depends on it. Each app's README has the details.

**How this was built:** with heavy AI assistance. Most of the code was written by Anthropic's Claude (through Claude Code), directed by the maintainer, who decides what to build, tests it on real phones and reviews the changes. The benchmark numbers are real device runs, failures included. See the "How this was built" section of each repository's README for the details.

**Ways to help:** test on your phone and file a device report (the Android and iPhone repositories both have a form), report bugs, or share benchmark results. Security problems go through each repository's private "Report a vulnerability" route, never a public issue. See the [contributing guide](https://github.com/MeshLive/.github/blob/main/CONTRIBUTING.md) and [security policy](https://github.com/MeshLive/.github/blob/main/SECURITY.md).
