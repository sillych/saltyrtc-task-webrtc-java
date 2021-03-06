# Changelog

This project follows semantic versioning.

Possible log types:

- `[added]` for new features.
- `[changed]` for changes in existing functionality.
- `[deprecated]` for once-stable features removed in upcoming releases.
- `[removed]` for deprecated features removed in this release.
- `[fixed]` for any bug fixes.
- `[security]` to invite users to upgrade in case of vulnerabilities.


### v0.3.2 (2016-11-29)

- [added] Add `clearMessageHandler` method

### v0.3.1 (2016-11-14)

- [added] Make handover optional (#6)
- [changed] Update saltyrtc-client to v0.7.+

### v0.3.0 (2016-10-27)

- [changed] Update saltyrtc-client to v0.6.+

### v0.2.2 (2016-10-25)

- [changed] Add latest libjingle build

### v0.2.1 (2016-10-20)

- [fixed] Update libjingle builds

### v0.2.0 (2016-10-20)

- [changed] Update saltyrtc-client to v0.5.0

### v0.1.9 (2016-10-19)

- [fixed] Downgrade libjingle builds

### v0.1.8 (2016-10-19)

- [fixed] Fix path to arm native libraries

### v0.1.7 (2016-10-19)

- [changed] Update saltyrtc-client to v0.4.0
- [fixed] Fix candidates message handling
- [fixed] Fix bug in task data
- [fixed] Send proper max packet size
- [fixed] Fix boolean check in sendSignalingMessage
- [added] Added WebRTC PeerConnection (libjingle) builds for `arm` and `x86`

### v0.1.6 (2016-10-06)

- [changed] Update saltyrtc-client to v0.3.0

### v0.1.5 (2016-10-06)

- [changed] Update saltyrtc-client

### v0.1.4 (2016-10-06)

- [added] Handle close messages

### v0.1.3 (2016-10-06)

- [changed] The peer connection must now be passed to the `handover` method, not to the constructor.

### v0.1.2 (2016-10-06)

- [changed] The sendXXX methods now only throw `ConnectionException`

### v0.1.1 (2016-10-06)

- [changed] Make `SecureDataChannel` class public

### v0.1.0 (2016-10-06)

- Initial release
