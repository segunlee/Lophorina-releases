# Lophorina

**Lophorina** is a macOS utility app for Apple developers — a collection of everyday tools in one place.

> Requires macOS 15.0 or later.

![Lophorina Screenshot](screenshot.png)

## Features

### Encoding / Decoding
- **Base64** — Encode or decode text with Base64
- **URL Encoding** — Encode or decode URLs with selectable character sets (User, Password, Host, Path, Query, Fragment)
- **Korean** — Fix garbled Korean text from Unicode escape sequences (`\uXXXX`)

### Cryptography
- **AES** — Encrypt and decrypt text with AES. Configurable mode, padding, and output format (Hex / Base64)

### JSON
- **JSON** — Format, validate, and manipulate JSON

### Apple Developer Tools
- **APNs** — Send test push notifications. Supports `.p8` key and `.p12` certificate. Manage multiple payloads with tabs
- **App Icon** — Generate a complete Xcode app icon asset catalog from a single 1024×1024 image
- **Provisioning Profile** — Browse and search all installed provisioning profiles. View expiration dates, bundle IDs, and team info. Open in Finder or delete directly
- **iOS Device Support** — Install Xcode device support files for iOS versions not bundled with your current Xcode
- **Xcode Cache Cleaner** — Selectively clean DerivedData and other Xcode cache directories

### Network
- **Mitmproxy** — Inspect and intercept HTTP/HTTPS traffic. View live request/response flows, write Python scripts to modify traffic, and monitor output in a built-in console. Requires `mitmproxy` via Homebrew
- **Domain Router** — Route specific domains through a chosen network interface. Blocks IPv6 NAT64 routes via loopback, forcing IPv4 over Ethernet when tethering via iPhone

### System
- **Launch Daemon / Agent** — List, start, stop, and manage LaunchDaemons and LaunchAgents running on your Mac

---

## Download

Download the latest version from the [Releases](https://github.com/segunlee/Lophorina-releases/releases) page.

---

> This repository also hosts the appcast feed (`appcast.xml`) for Sparkle automatic updates.

[한국어](README_ko.md)
