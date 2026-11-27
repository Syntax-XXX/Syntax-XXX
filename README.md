<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=6E3BF3&height=180&section=header&text=Syntax-XXX&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35" alt="header banner" />
</p>

<h1 align="center">Hey, I'm Syntax-XXX 👋</h1>
<h3 align="center">Self-hoster · Homelab tinkerer · Hobby developer from Germany 🇩🇪</h3>

<p align="center">
  <a href="https://syntax-xxx.is-a.dev"><img src="https://img.shields.io/badge/Website-syntax--xxx.is--a.dev-6E3BF3?style=for-the-badge&logo=googlechrome&logoColor=white" alt="website" /></a>
  <a href="https://github.com/Syntax-XXX"><img src="https://img.shields.io/badge/GitHub-Syntax--XXX-6E3BF3?style=for-the-badge&logo=github&logoColor=white" alt="github" /></a>
  <a href="https://discord.gg/wEnW2kPwce"><img src="https://img.shields.io/badge/Discord-.Moinse908-6E3BF3?style=for-the-badge&logo=discord&logoColor=white" alt="discord" /></a>
  <a href="mailto:me@syntax-xxx.is-a.dev"><img src="https://img.shields.io/badge/Email-me@syntax--xxx.is--a.dev-6E3BF3?style=for-the-badge&logo=gmail&logoColor=white" alt="email" /></a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6E3BF3&center=true&vCenter=true&width=720&lines=Self-hosting+the+stuff+that+should+probably+be+production;Building+homelabs+on+retired+hardware;Debian+on+a+2012+Synology+with+512+MB+RAM;Making+self-hosting+less+scary" alt="Typing SVG" />
</p>

---

### 👨‍💻 About me

I'm a hobby developer from Germany 🇩🇪 who spends too much time turning old hardware into home servers. I build tools for homelabs, self-hosting and the web — and occasionally write about it.

- 🏠 Currently building a Debian-based DSM replacement for a 2012 Synology RS812 (ARMv5, 512 MB RAM).
- 🐳 Working on **DockPilot**, a self-hosted Docker control center.
- 🌐 Making homelab infrastructure visible with **homelab-topologie**.
- 🦀 Writing a compiler in Rust because apparently I hate free time.
- 🎯 Focus: self-hosting, homelabs, Debian on weird hardware, developer tooling.
- ☕ Fun fact: I turn coffee into YAML.

### 🚀 What I'm building

| Project | Stack | What it is |
| --- | --- | --- |
| **[RSRB / rs812-debian](https://github.com/Syntax-XXX/rs812-debian)** | Shell | Debian 12 on a Synology RS812 (Kirkwood ARMv5) — kernel in SPI flash, no USB stick, without DSM. |
| **[RackPanel](https://github.com/Syntax-XXX/rackpanel)** | Go | Lightweight NAS web UI and DSM replacement that runs on ARMv5 with 512 MB RAM. |
| **[DockPilot](https://github.com/Syntax-XXX/DockPilot)** | TypeScript | Self-hosted Docker infrastructure control center *(alpha)*. |
| **[homelab-topologie](https://github.com/Syntax-XXX/homelab-topologie)** | HTML/Node | Live 3D topology of a homelab — devices, cables, packets and a rack view that unfolds. |
| **[Volt](https://github.com/Syntax-XXX/volt)** | Rust | A programming language and compiler with GC, generics, traits, WASM and an LSP. |
| **[BFB](https://github.com/Syntax-XXX/bfb)** | Rust | Blazing Fast Browser: tuned Firefox with a dark/gold Frutiger-Aero UI, plus a tiny Rust/WebKitGTK kiosk browser. |
| **[EnvTwin](https://github.com/Syntax-XXX/EnvTwin)** | Python | Snapshot your dev environment and turn it into a Dockerfile or setup script. |

### 🧰 Homelab stack

<p align="center">
  <img src="https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white" alt="Proxmox" />
  <img src="https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white" alt="Debian" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Traefik-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white" alt="Traefik" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Home%20Assistant-18BCF2?style=flat-square&logo=homeassistant&logoColor=white" alt="Home Assistant" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
</p>

Proxmox VE · Debian · Docker · Traefik · Caddy · Restic · Grafana · Prometheus · Uptime Kuma · Home Assistant · \*arr

### 🖥️ Hardware

| | Machine | What it does |
| --- | --- | --- |
| 🏗️ **Big server** | **Fujitsu PRIMERGY RX300 S6** (pve1) — 2× Intel Xeon E5645, 283 GB RAM | Proxmox node for heavy builds and game containers. Only on when needed — it is loud. |
| 🧰 **Little server** | **HP ProDesk 405 G4** (pve2) — AMD Ryzen 5 PRO 2400G, 15 GB RAM, 250 GB NVMe | Always-on Proxmox node for the main services. |
| 💾 **NAS** | **Synology RackStation RS812** — Marvell Kirkwood ARMv5, 512 MB RAM, 3× 4 TB | Debian 12 / RSRB storage for media, backups and repos. |
| ☁️ **VPS** | **Oracle Cloud A1.Flex** — 2 OCPU ARM64, 12 GB RAM, 96 GB disk | Public gateway: Traefik, Coolify, SSO and mail. |

Also in the mix: Cisco WS-C2960S-24PS-L switch, Starlink router, HP EliteBook x360 1030 G4 laptop and an i5-12400 desktop.

### 🛠 Languages & Tools

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=go,rust,ts,py,cpp,cs,bash,docker,linux,html,css,nodejs,git,kubernetes&theme=dark&perline=7" alt="My skills" />
  </a>
</p>

### 📊 GitHub stats

<p align="center">
  <a href="https://github.com/Syntax-XXX"><img align="center" src="https://raw.githubusercontent.com/Syntax-XXX/Syntax-XXX/output/stats.svg" alt="GitHub stats" height="180" /></a>
  <a href="https://github.com/Syntax-XXX"><img align="center" src="https://raw.githubusercontent.com/Syntax-XXX/Syntax-XXX/output/top-langs.svg" alt="Top languages" height="180" /></a>
</p>

<p align="center">
  <a href="https://streak-stats.demolab.com"><img align="center" src="https://streak-stats.demolab.com?user=Syntax-XXX&theme=transparent&hide_border=true&ring=6E3BF3&fire=6E3BF3&currStreakLabel=6E3BF3&sideLabels=6E3BF3&currStreakNum=ffffff&sideNums=ffffff&dates=9e9e9e" alt="GitHub streak" /></a>
</p>

### 🏅 Certifications

<p align="center">
  <a href="https://ipv6.he.net/certification/scoresheet.php?pass_name=ewiesinger">
    <img src="https://ipv6.he.net/certification/create_badge.php?pass_name=ewiesinger&amp;badge=3&amp;refresh=1" width="229" height="137" alt="Hurricane Electric IPv6 Certification — ewiesinger" />
  </a>
</p>

### 🐍 Contributions

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Syntax-XXX/Syntax-XXX/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Syntax-XXX/Syntax-XXX/output/github-contribution-grid-snake.svg" />
    <img alt="GitHub contribution grid snake" src="https://raw.githubusercontent.com/Syntax-XXX/Syntax-XXX/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

### 📫 Find me

- 🌐 Website: [syntax-xxx.is-a.dev](https://syntax-xxx.is-a.dev)
- 💬 Discord: `.Moinse908` — [discord.gg/wEnW2kPwce](https://discord.gg/wEnW2kPwce)
- 📧 Email: [me@syntax-xxx.is-a.dev](mailto:me@syntax-xxx.is-a.dev)

<p align="center">
  <i>⭐ From <a href="https://github.com/Syntax-XXX">Syntax-XXX</a> — thanks for stopping by!</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=6E3BF3&height=120&section=footer" alt="footer wave" />
</p>
