# Velociraptor DFIR — Interactive Guide

> An interactive, single-file reference guide for the [Velociraptor](https://github.com/Velocidex/velociraptor) open-source DFIR platform. Styled to match the Velociraptor GUI with full light/dark mode support.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Based on Velociraptor](https://img.shields.io/badge/based%20on-Velociraptor%20v0.73.x-orange)](https://github.com/Velocidex/velociraptor)
[![No dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)](index.html)

---

## Live Demo

Open `index.html` in any modern browser — no server, no build step, no dependencies.

<h3 align="center">
  <a href="https://github.com/IronBranded/Velociraptor_Initiative/" target="_blank" rel="noopener noreferrer">
    🟢 TRY THE GUIDE🟢
  </a>
</h3>

---
---

## What's Inside

A 13-section interactive reference covering the complete Velociraptor platform:

| Section | Content |
|---------|---------|
| **Overview** | Capability metrics, deployment modes, project info |
| **Quick Start** | Download, instant GUI, first VQL query with runnable demo |
| **Architecture** | Component diagram, security model, multi-frontend scaling |
| **VQL Language** | Syntax, plugins table, 3 runnable live examples, advanced patterns |
| **Artifacts** | YAML structure, all field docs, 4 types, filterable catalog (22 artifacts), writing tips |
| **Client Management** | Live client roster, per-client actions, deployment methods, search syntax |
| **Hunts & Hunting** | Step flow, targeting options, YARA hunt example |
| **Forensic Analysis** | 5 tabs: filesystem/NTFS, execution evidence, critical event IDs, memory scanning, dead-disk |
| **Live Monitoring** | CLIENT_EVENT artifacts, Sigma, ETW, server-side alerting with VQL |
| **Offline Collectors** | Use cases, output options, build/import workflow |
| **Notebooks** | Features, investigation cell flow mockup |
| **Server API** | pyvelociraptor, collection via API, ACL roles |
| **Quick Reference** | CLI commands, top 16 artifacts, official resources, 7-session training outline |

---

## Features

- **Single HTML file** — zero dependencies, zero build step
- **Velociraptor GUI color scheme** — navy sidebar, orange accents, teal highlights
- **Light / Dark theme toggle** — respects `prefers-color-scheme` on load
- **Collapsible sidebar** — more screen space for content
- **Tabbed sub-sections** — e.g. VQL has Basics / Plugins / Live Examples / Advanced
- **Runnable VQL demos** — click ▶ Run to reveal sample result tables
- **Filterable artifact catalog** — filter by Windows / Linux / Detection / Forensics
- **Expandable accordions** — artifact writing tips section
- **All syntax highlighted** — VQL code blocks with keyword/function coloring
- **External links** — to official docs, training, Discord, GitHub

---

## Based On

| Source | URL |
|--------|-----|
| Velociraptor GitHub | https://github.com/Velocidex/velociraptor |
| Official Documentation | https://docs.velociraptor.app |
| Training Course | https://docs.velociraptor.app/training |
| Training Slides | https://training.velociraptor.app |
| VQL Reference | https://docs.velociraptor.app/vql_reference |
| Artifact Exchange | https://docs.velociraptor.app/exchange |

---

## Contributing

Contributions welcome! Ideas:

- Add more sections (e.g. Sigma integration deep-dive, ETW monitoring, Orgs/MSSP)
- Keep artifact catalog up to date with new built-ins
- Add more runnable VQL examples
- Translations

```bash
git checkout -b feature/my-section
# edit index.html
git commit -m "Add: section on XYZ"
git push origin feature/my-section
# open a PR
```
---

## License

MIT — see [LICENSE](LICENSE). This guide is an independent reference project and is not officially affiliated with Velocidex or Rapid7.

Velociraptor itself is licensed under [AGPL v3](https://github.com/Velocidex/velociraptor/blob/master/LICENSE).
