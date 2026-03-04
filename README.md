# 🛡️ CyberArsenal — Open Source Security Tools Platform

> The definitive collection of open-source cybersecurity tools, organized and searchable.

[![GitHub Pages](https://img.shields.io/badge/Live-GitHub%20Pages-00ffe7?style=flat-square&logo=github)](https://siteq8.github.io/CyberArsenal)
[![Tools](https://img.shields.io/badge/Tools-60%2B-00ff88?style=flat-square)]()
[![Categories](https://img.shields.io/badge/Categories-12-b06bff?style=flat-square)]()
[![License](https://img.shields.io/badge/License-MIT-ffd966?style=flat-square)]()

---

## 🔍 What is CyberArsenal?

**CyberArsenal** is a professional, searchable reference platform featuring 60+ open-source cybersecurity tools across 12 categories — built for security professionals, pentesters, researchers, and CTF players.

### ✨ Features
- ⚡ **Instant search** across tool names, descriptions, and tags
- 🗂️ **12 categories** — Network, Web App, Exploitation, Forensics, Malware Analysis, OSINT, Password, Wireless, Reverse Engineering, Cloud/Container, Social Engineering, Cryptography
- 🔗 **Direct links** to GitHub repos and official docs for every tool
- 📱 **Fully responsive** — works on desktop and mobile
- 🎨 **Professional dark UI** with terminal-inspired cyber aesthetic
- ⚡ **Zero dependencies** — pure HTML/CSS/JS, no frameworks needed

---

## 🛠️ Tool Categories

| Category | Count | Tools Include |
|---|---|---|
| 🌐 Network | 10 | Nmap, Wireshark, Masscan, Suricata, OpenVAS... |
| 🕷️ Web App | 10 | OWASP ZAP, SQLmap, Nuclei, ffuf, Gobuster... |
| 💥 Exploitation | 7 | Metasploit, Empire, Impacket, RouterSploit... |
| 🔬 Forensics | 7 | Autopsy, Volatility 3, Binwalk, ExifTool... |
| 🦠 Malware Analysis | 7 | Ghidra, Cuckoo, YARA, Radare2, DiE... |
| 🕵️ OSINT | 7 | theHarvester, SpiderFoot, Amass, Subfinder... |
| 🔑 Password | 6 | Hashcat, John, Hydra, CrackMapExec, SecLists... |
| 📡 Wireless | 5 | Aircrack-ng, Kismet, Wifite2, Bettercap... |
| 🔧 Reverse Eng. | 5 | x64dbg, Ghidra, Frida, angr, Rizin... |
| ☁️ Cloud/Container | 5 | Trivy, Falco, Prowler, ScoutSuite... |
| 🎭 Social Eng. | 3 | SET, GoPhish, Evilginx2 |
| 🔐 Cryptography | 5 | OpenSSL, CyberChef, GnuPG, Steghide... |

---

## 🚀 Deploy to GitHub Pages

1. **Fork or clone** this repository
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch** → `main` → `/ (root)`
4. Your site will be live at `https://siteq8.github.io/CyberArsenal`

---

## 📁 Project Structure

```
CyberArsenal/
├── index.html        # Main platform (single-file app)
├── README.md         # This file
└── _config.yml       # GitHub Pages configuration
```

---

## 🤝 Contributing

Want to add a tool? Open a PR!

1. Edit `index.html`
2. Add your tool to the `TOOLS` array following the existing format:
```js
{
  name: "Tool Name",
  cat: "category",        // network|web|exploit|forensics|malware|osint|password|wireless|reverse|cloud|social|crypto
  desc: "Description...",
  tags: ["tag1","tag2"],
  lang: "Python",
  stars: "1.2k",
  github: "https://github.com/...",
  url: "https://..."
}
```

---

## ⚠️ Disclaimer

This platform is for **educational and authorized security testing purposes only**.  
Always obtain proper authorization before testing any system.  
The maintainers are not responsible for misuse of any listed tools.

---

## 👤 Author

**SiteQ8**  
📧 [site@hotmail.com](mailto:site@hotmail.com)  
🐙 [github.com/SiteQ8](https://github.com/SiteQ8)

---

<p align="center">Built with ❤️ for the global security community</p>
