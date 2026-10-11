# Contributing to MeshLive

Thank you for wanting to help. MeshLive sends live video and voice calls between nearby phones over Bluetooth with
no internet. This is the default contributing guide for every repository in the [MeshLive organisation](https://github.com/MeshLive)
that does not have its own. You do not need to write code to help: a clear bug report or a device test result is a
real contribution.

| Repository | Contribute here when | Guide |
| --- | --- | --- |
| [meshlive-android](https://github.com/MeshLive/meshlive-android) | You use the Android app, or want to change the protocol, the Android app or the host tools | [CONTRIBUTING.md](https://github.com/MeshLive/meshlive-android/blob/main/CONTRIBUTING.md) |
| [meshlive-ios](https://github.com/MeshLive/meshlive-ios) | You have an iPhone, or want to change the iPhone app | [CONTRIBUTING.md](https://github.com/MeshLive/meshlive-ios/blob/main/CONTRIBUTING.md) |
| [meshlive-benchmarks](https://github.com/MeshLive/meshlive-benchmarks) | You want to question, reproduce or add to the measured results | [README](https://github.com/MeshLive/meshlive-benchmarks#sharing-your-results-and-citing-this-data) |

The most valuable contributions today:

- **A device test report** from your phone, tested with at least one other phone running MeshLive. Reports where
  everything worked are as useful as failures. Both app repositories have a form on their **New issue** page.
- **iPhone testing.** The iPhone app has had almost no hardware testing, so iPhone owners are especially welcome.
- **Bug reports** with both phone models, OS versions and the app version or commit.

## Ground rules

- Follow the [Code of Conduct](CODE_OF_CONDUCT.md).
- **Security problems are never public issues.** Use the repository's **Security** tab, then **Report a
  vulnerability**; see the [security policy](SECURITY.md).
- **Privacy.** Never post photos, recordings or screenshots of other people, Bluetooth addresses, device serial
  numbers, signing keys, private file paths or email addresses. Share summaries (models, versions, short hashes).
- **Evidence.** Say what you measured, on which phones, and what you expected. Unmeasured stays unmeasured, and a
  fallback is not a pass for the path that was requested.
- **Licence.** MeshLive code is GPL-3.0-or-later and the benchmark data is CC BY 4.0. Sign off commits with
  `git commit -s` (Developer Certificate of Origin 1.1).
