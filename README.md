<div align="center">

# hahaahhdev

**Cyber Security Engineer**

I build security tooling: pentesting and OSINT utilities, license compliance scanners, and ransomware detection.
Small, focused, offline-first tools that do one job properly.

</div>

---

## Tech

**Supreme**: Python

**Master**: C · C++ · Java · JavaScript · TypeScript · React · HTML · CSS · PostgreSQL · SQLite

**Fluent**: MongoDB · Flask

---

## Projects

### [Rexor](https://github.com/HahaAhhDev/rexor) &nbsp;`Python` · `MIT`

Pentesting, OSINT, and network reconnaissance toolkit. Single terminal application with 26 stress-testing methods, OSINT gathering, and live-updating attack statistics.

> For educational purposes and authorized testing only.

### [Secular](https://github.com/HahaAhhDev/secular) &nbsp;`TypeScript` · `v1.3.2`

Automatically scans entire repositories for license violations. Fingerprint-matches against the full SPDX catalog, parses dependency manifests, and applies a compatibility rules engine, with optional AI adjudication for custom licenses. Outputs terminal, JSON, Markdown, or SARIF reports with a 0–100 compliance score.

📖 [Docs](https://hahaahhdev.github.io/secular/)

```bash
curl -fsSL https://raw.githubusercontent.com/HahaAhhDev/secular/master/install.sh | bash
secular scan .
```

### [Sentinel](https://github.com/HahaAhhDev/sentinel) &nbsp;`Python 3.10+` · `MIT` · `v0.5.0`

Tiny folder watchdog that spots ransomware-like behavior and blocks it. Baselines a directory, watches for live hits, and can kill the offending process. Keeps a vault of clean copies so `protect --restore-clean all` restores pre-hit content, not post-hit junk. No server, no signup. Files stay local. Linux and Windows.

📖 [Docs](https://hahaahhdev.github.io/sentinel/)

```bash
pip install sentinel-watch
sentinel init ~/Documents
sentinel watch ~/Documents --response auto
```

---

## Contact

I take on custom work: tools, websites, apps, automation, security tooling. Reach out if you've got something in mind.

**I only take crypto.**

[Discord](https://discord.com/users/1538663018718691409)

---

<div align="center">
<sub>Built for authorized testing and defensive security.</sub>
</div>
