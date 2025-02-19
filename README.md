# CupLink

<div align="center">

[![Android](https://img.shields.io/badge/Platform-Android%205.0+-green.svg)](https://android.com)
[![Android Auto](https://img.shields.io/badge/Platform-Android%20Auto-blue.svg)](https://android.com/auto)

Serverless voice and video calls for local networks, powered by P2P technology
</div>

## Overview

CupLink enables direct voice and video communication without requiring internet access or centralized servers. By scanning QR codes, users can connect instantly within local networks such as:

- Community mesh networks
- Corporate networks
- Home networks

While CupLink integrates with the RiV mesh network by default for enhanced connectivity, it can operate independently in any local network environment.

## Key Features

### Core Functionality
- 🎥 High-quality voice and video calls
- 🔒 End-to-end encrypted communication
- 📱 No registration or accounts required
- 💾 Encrypted backup for settings, calls, and contacts
- 🔐 App settings and boot password protection

### Network Capabilities
- 🌐 P2P calls over Wi-Fi Direct
- 🔍 Automatic peer discovery using IPv6 multicasting
- 📡 Public peer publishing
- 🎙️ Push-to-talk support
- 🔄 Mesh network topology

## Technical Details

### Network Architecture

CupLink operates as a mesh network peer, eliminating the need for dedicated servers. Each device can:
- Act as a network node
- Redirect traffic from other peers
- Function independently within the mesh

### Connection Process

1. QR code exchange of contact details and IP address
2. Direct connection using static IPv6 addressing (no DHCP required)
3. RiV Mesh virtual static IPv6 addresses for connection establishment

## Platform Support

- Android 5.0 (Lollipop) and newer versions
- Android Auto compatibility

## Building from Source

### Prerequisites

As of version 0.4.6.x:
- WebRTC library is pre-built and available via [Maven repository](https://github.com/RiV-chain/artifact)
- Project implements [Unified Plan](https://www.callstats.io/blog/what-is-unified-plan-and-how-will-it-affect-your-webrtc-development)

For detailed WebRTC library build instructions, visit our [build guide](https://dev.to/ethand91/webrtc-for-beginners-part-55-building-the-webrtc-android-library-e8l).

## Documentation

- [Complete Documentation](docs/Documentation.md)
- [Frequently Asked Questions](docs/faq.md)

## License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">
Made with ❤️ by the CupLink Team
</div>
