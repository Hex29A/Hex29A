# Hi, I'm Martin 👋

Self-hoster in Malmö, Sweden. I build the tools I wish already existed, mostly for Axis cameras and my own home lab.
*If it has an API, it gets a CLI.*

![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/-Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

## Axis cameras

Manage, script and discover Axis devices over VAPIX, from a terminal or an AI assistant.

| Project | What it does |
|---|---|
| [vapx](https://github.com/Hex29A/vapx) | One static Rust binary, 40+ commands: firmware, PTZ, ACAP, overlays, users, security audit. Doubles as an MCP server (`vapx mcp`). |
| [vapx-scan](https://github.com/Hex29A/vapx-scan) | Finds Axis devices on the LAN via SSDP, ONVIF, mDNS and subnet scan. |

```sh
brew install hex29a/tap/vapx
```

## Self-hosting and tools

| Project | What it does |
|---|---|
| [hexnotes](https://github.com/Hex29A/hexnotes) | Note-taking with a REST API. Notes are plain `.md` files, no database. PWA and AI-agent friendly. |
| [crawldown](https://github.com/Hex29A/crawldown) | Crawls a whole website into clean Markdown, for LLM ingestion or offline archiving. Go. |
| [HexQz](https://github.com/Hex29A/HexQz) | Real-time quiz platform. Players join by QR code on their phones, no accounts. |

## Small browser tools

No server, no tracking, works offline.

| Project | What it does |
|---|---|
| [Offline-QR-Creator](https://github.com/Hex29A/Offline-QR-Creator) | QR code generator that runs entirely in the browser. |
| [Printable-QR-Labels](https://github.com/Hex29A/Printable-QR-Labels) | Design and print labels with QR codes for boxes, storage and inventory. |

## Elsewhere

- Web: [hex29a.com](https://hex29a.com)

<sub>Most of what I build runs on my own infrastructure (home lab, VPS, Cloudflare Workers), and not all of it is public.</sub>
