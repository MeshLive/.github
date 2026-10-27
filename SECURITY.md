# Security policy

MeshLive is meant for places where the internet may be down or watched, so a security flaw can matter more than in
an ordinary app. We would rather hear about a problem privately and fix it than read about it in a public issue.

**Please do not open a public issue, pull request or discussion for a security problem.**

Report it privately to the repository that is affected:

| Affected | Report |
| --- | --- |
| The Android app, or the protocol itself | [meshlive-android](https://github.com/MeshLive/meshlive-android/security/advisories/new), and read its [SECURITY.md](https://github.com/MeshLive/meshlive-android/blob/main/SECURITY.md) |
| The Windows app | [meshlive-windows](https://github.com/MeshLive/meshlive-windows/security/advisories/new), and read its [SECURITY.md](https://github.com/MeshLive/meshlive-windows/blob/main/SECURITY.md) |
| The iPhone or Mac app | [meshlive-apple](https://github.com/MeshLive/meshlive-apple/security/advisories/new), and read its [SECURITY.md](https://github.com/MeshLive/meshlive-apple/blob/main/SECURITY.md) |
| The benchmark data (for example personal data that slipped into a result) | [meshlive-benchmarks](https://github.com/MeshLive/meshlive-benchmarks/security/advisories/new) |

Use the repository's **Security** tab and **Report a vulnerability**. If you cannot, open a public issue that says
only "security report", with no details, keys or proof of concept, and a maintainer will arrange a private channel.

MeshLive is a volunteer project: response times are best effort, with no bounty. We aim to acknowledge a report
within about a week and to agree a disclosure date with you, no later than 90 days after the report without a better
reason. The scope, what to include and the known limitations are in the Android policy linked above; the Windows, iPhone and Mac
apps speak the same protocol, so a protocol flaw affects all of them.
