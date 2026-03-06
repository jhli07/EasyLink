# ⚡ EasyLink

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/badge/version-2.0-green.svg" alt="Version">
  <img src="https://img.shields.io/badge/WebRTC-PeerJS-orange.svg" alt="Tech">
</p>

> English | [中文](./README_ZH.md)

A minimalist end-to-end file transfer tool based on WebRTC P2P transmission. No server needed, privacy guaranteed.

## ✨ Features

- 🔗 **P2P Transmission** - Data goes directly between devices, no server involved
- 📱 **Cross-Platform** - Works on all modern browsers
- 📦 **Large File Support** - Chunked transmission, theoretically unlimited size
- 🔒 **End-to-End Encryption** - WebRTC DTLS encryption
- 📱 **QR Code Pairing** - Scan to connect instantly
- 🎨 **Modern UI** - Beautiful dark theme design
- 💾 **State Persistence** - Auto-saves connection history

## 🚀 Quick Start

### Online Demo

Visit GitHub Pages:
```
https://jhli07.github.io/EasyLink/
```

### Local Development

```bash
# Clone the repository
git clone https://github.com/jhli07/EasyLink.git

# Open EasyLink.html in your browser
# Or use any static file server
npx serve .
```

## 📖 Usage

1. **Open the page** - Open EasyLink on both devices
2. **Generate Code** - Click "Refresh Code" to get a 5-digit device code
3. **Connect** - Enter the other device's code and click connect
4. **Transfer** - Select files and click send

### QR Pairing (Mobile to Desktop)

1. Open EasyLink on computer - QR code will display
2. Scan QR code with phone
3. Click connect

## 🔧 Tech Stack

- **PeerJS** - WebRTC wrapper library
- **QRCode** - QR code generation
- **Vanilla JavaScript** - No framework dependencies
- **WebRTC** - Browser native P2P communication

## 📱 Browser Support

| Browser | Version |
|---------|---------|
| Chrome/Edge | 80+ |
| Firefox | 78+ |
| Safari | 14+ |
| Mobile Browsers | Supported |

## ⚠️ Notes

- Requires HTTPS environment (or localhost)
- Some networks may need TURN relay server
- Firewall may block P2P connections

## 📄 License

MIT License - See [LICENSE](./LICENSE) for details.

---

Made with ❤️ by [Agent_Li](https://github.com/jhli07)