# OpenBubbles Relay Package Repository

> [!IMPORTANT]
> ### Upstream Attribution & Scope
> **The core relay logic, network protocol, and fundamental codebase are the intellectual property of [OpenBubbles](https://github.com/OpenBubbles/relayserver).**
>
> This repository is a community APT package repository distributing builds with platform-specific enhancements (legacy 32-bit `armv7s` iOS 10 support, kernel Mach IPC bindings, MobileGestalt telemetry, and Home Assistant push reporting). It is **not** an independent fork and does not work on the core relay logic independently.

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
| `dev.copper.relayserver` | `armv7s` (32-bit) | OpenBubbles RelayServer daemon with 32-bit Mach IPC, MobileGestalt battery telemetry, and Home Assistant push reporter. |
| `openssh` | `iphoneos-arm` | OpenSSH secure shell daemon configured for iOS 10. |
| `openssl` | `iphoneos-arm` | Cryptographic runtime libraries. |

---

## Credits & Links

- **Upstream OpenBubbles:** [github.com/OpenBubbles/relayserver](https://github.com/OpenBubbles/relayserver)
- **Enhancement Source Code:** [github.com/Bananz0/relayserver](https://github.com/Bananz0/relayserver)
