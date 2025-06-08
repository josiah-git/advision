[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

# ADvision (Patch & Dependency Risk Intelligence)

ADvision is a cross-platform, agent-based patch risk and dependency intelligence platform built to:
- Track software patch status across Linux (RHEL, Ubuntu) and Windows
- Score **cyber risk** and **uptime risk** per patch
- Map software dependency trees across ecosystems
- Provide **actionable upgrade paths** and risk-aware remediation roadmaps

## 🚀 Why ADvision?

Traditional scanners stop at "here’s a vulnerability."

**ADvision goes further:**
- Understand what the patch affects
- Know what might break
- Visualize what needs to change to make patching safe

## 🧠 Features

- ✅ Agent-first design: endpoints report status, no need to scan
- ✅ Hourly reporting with historical context
- ✅ Cross-ecosystem package and dependency mapping
- ✅ Risk scoring for both security and uptime impact
- ✅ Supabase + Replit compatible backend
- ✅ Built for automation and minimal footprint

## 📦 Architecture

- Python (FastAPI or Flask)
- Supabase (Postgres)
- Lightweight endpoint agents (Python or shell)
- Deployable via Replit, Render, Railway, or Docker

## ⚖️ License

This project is licensed under the **GNU Affero General Public License v3.0** (AGPL-3.0).

You may:
- Use, modify, and self-host this project
- Deploy it for internal or external use

However, if you **modify and host it as a service**, you **must also release your source code** under the same license. This ensures improvements benefit the community.

For full terms, see the [`LICENSE`](./LICENSE) file or [AGPL-3.0 license text](https://www.gnu.org/licenses/agpl-3.0.html).

## 📣 Contributing

Pull requests welcome! Please open issues or ideas as discussions before implementing major changes.

## 💬 Questions?

Feel free to open an issue or reach out at [your-email@example.com].
