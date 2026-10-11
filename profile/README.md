# MeshLive

**Live video, voice calls and messages between nearby phones, over Bluetooth, with no internet.**

MeshLive is free and open-source software (GPL-3.0-or-later). Phones talk directly to each other and can relay a live stream through other nearby phones, with end-to-end encryption, so it keeps working off-grid, in emergencies, or where the internet is down or censored. There is no account, no server and no analytics.

| Repository | What it is | Status |
| --- | --- | --- |
| **[meshlive-android](https://github.com/MeshLive/meshlive-android)** | The Android app (canonical): live video, calls, relaying, the protocol specification, test vectors and tools. [Download the latest release](https://github.com/MeshLive/meshlive-android/releases/latest) | Public beta (0.1.0-beta). Measured on a handful of phones; some combinations still fail. |
| **[meshlive-ios](https://github.com/MeshLive/meshlive-ios)** | The iPhone app, written to the same protocol so iPhones and Android phones can call and watch each other. | Early. Not on the App Store, no binary release, and only a few automated test calls on one iPhone so far. iPhone testers wanted. |
| **[meshlive-benchmarks](https://github.com/MeshLive/meshlive-benchmarks)** | Measured results on real Android phones, with inputs you can regenerate, to compare your own phones against (CC BY 4.0). | Baseline published; no run has passed every gate yet, and the data says so. |

**Please read before relying on it:** MeshLive has not had an independent security review, and its Bluetooth announcements currently carry a stable identifier that can be used to recognise a phone over time. Use it for testing and feedback, not where your safety depends on it. Each app's README has the details.

**How this was built:** with heavy AI assistance. Most of the code was written by Anthropic's Claude (through Claude Code), directed by the maintainer, who decides what to build, tests it on real phones and reviews the changes. The benchmark numbers are real device runs, failures included. Nothing here has had an independent security audit. See the "How this was built" section of each repository's README for the details.

**Ways to help:** test on your phone and file a device report (the Android and iPhone repositories both have a form), report bugs, or share benchmark results. Security problems go through each repository's private "Report a vulnerability" route, never a public issue. See the [contributing guide](https://github.com/MeshLive/.github/blob/main/CONTRIBUTING.md) and [security policy](https://github.com/MeshLive/.github/blob/main/SECURITY.md).
