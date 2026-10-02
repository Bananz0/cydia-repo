# OpenBubbles Relay Package Repository

> [!IMPORTANT]
> ### Upstream Attribution & Scope
> **The core relay logic, network protocol, and fundamental codebase are the intellectual property of [OpenBubbles](https://github.com/OpenBubbles/relayserver).**
>
> This repository is a community APT package repository distributing builds with platform-specific enhancements (legacy 32-bit `armv7s` iOS 10 support, hardware status monitoring, and Home Assistant push reporting). It is **not** an independent fork and does not work on the core relay logic independently.

---

## Repository Access

Add this source to your iOS package manager:

- **URL:** `https://cydia.glenmuthoka.com/`
- **GitHub Pages Mirror:** `https://bananz0.github.io/cydia-repo/`

### Direct 1-Tap Links
- **Sileo:** `sileo://source/https%3A%2F%2Fcydia.glenmuthoka.com%2F`
- **Zebra:** `zbra://sources/add/https%3A%2F%2Fcydia.glenmuthoka.com%2F`
- **Cydia:** `cydia://url/https://cydia.saurik.com/api/share#?source=https%3A%2F%2Fcydia.glenmuthoka.com%2F`

---

## Packages

| Package ID | Architecture | Description |
| :--- | :--- | :--- |
| `dev.copper.relayserver` | `iphoneos-arm`, universal `armv7s` + `arm64` from 0.0.16-1 | OpenBubbles RelayServer daemon with hardware battery telemetry and Home Assistant push reporter. |
| `openssh` | `iphoneos-arm` (32-bit only) | OpenSSH secure shell daemon for iOS 10. 64-bit devices should use the openssh from their jailbreak's own repository. |
| `openssl` | `iphoneos-arm` (32-bit only) | Cryptographic runtime libraries for iOS 10. |

> [!WARNING]
> Releases 0.0.6 – 0.0.16-1 bundled SSH host keys inside the package. Those keys are public and must not be trusted. From 0.0.16-2 no keys are shipped, and installing it replaces any of the old keys still in `/etc/ssh` with keys generated on the device.

---

## Credits & Links

- **Upstream OpenBubbles:** [github.com/OpenBubbles/relayserver](https://github.com/OpenBubbles/relayserver)
- **Enhancement Source Code:** [github.com/Bananz0/relayserver](https://github.com/Bananz0/relayserver)
