# 3BX Tech Solutions — Official Website & Product Portfolio

Modern, high-performance, and responsive showcase website advertising **3BX Tech Solutions** and its suite of 5 flagship mobile applications.

## 🚀 Featured Products

1. **Smart Notes (Calculator Vault)**: Clean note-taking organizer disguising a secret PIN-protected multi-tab workspace with 30+ built-in social & web platforms.
2. **MediaVault**: Ultra-fast sub-second offline encryption for personal photos, videos, and audio using AES-256-CTR and PBKDF2 partial header encryption.
3. **NetDiscovery**: Advanced Wi-Fi & LAN network scanner with live radar visualization, OUI hardware vendor identification, port analyzer, and mDNS/UPnP probing.
4. **RemoteTV**: Universal smart TV controller for Android TV, Google TV, Roku, Samsung, and LG featuring zero-latency mDNS discovery, TLS pairing, and Wake-on-LAN.
5. **OmniReader**: Universal technical document viewer for TXT (up to 50MB), PDF, Markdown, Draw.io diagrams, and live Mermaid.js charts with Notepad++ style regex search.

## 📁 Repository Structure

```text
3bx/
├── index.html                  # Main responsive showcase landing page
├── README.md                   # Project documentation
├── website-assets/
│   ├── brand/
│   │   └── logo.svg            # 3BX geometric brand logo
│   └── products/
│       ├── smart-notes/        # Icon, feature graphic, and UI screenshots
│       ├── mediavault/         # Icon, feature graphic, showcase, and screenshots
│       ├── netdiscovery/       # Icon, feature graphic, and radar screenshots
│       ├── remotetv/           # Icon, feature graphic, and controller screenshots
│       └── omnireader/         # Icon, feature graphic, and diagram screenshots
```

## 💻 Local Preview

Run any local HTTP server or open directly in your browser:

```bash
# Python HTTP Server
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

## 🌐 Deployment

The website is completely static with zero build dependencies, making it 100% compatible with:
- GitHub Pages
- Cloudflare Pages
- Vercel
- Netlify
- AWS S3 / Firebase Hosting
