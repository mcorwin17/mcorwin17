<p align="center">
  <img src="https://raw.githubusercontent.com/mcorwin17/mcorwin17/main/boot.svg" alt="MaxOS boot log - Maxwell Corwin, computer science at South Carolina" width="880">
</p>

I'm **Maxwell Corwin**, a computer science student at the **University of South Carolina**. I build backend systems, simulation engines, and web apps. I co-founded and sold Bloxnetic, and I currently develop VR learning software at USC's Emergent Information Technology Lab.

[Email](mailto:maxcorwin86@gmail.com) · [MaxOS](https://github.com/mcorwin17/MaxOS) · [Bloxnetic](https://www.bloxnetic.com)

## Selected work

### [MaxOS](https://github.com/mcorwin17/MaxOS)
*C · x86 Assembly · QEMU*

A 32-bit x86 operating system that started as a class project at GSSM. I kept going until it could boot into its own userspace shell, load programs from FAT16, and run pipelines. The boot log above is real output.

It has demand paging, copy-on-write fork, kernel scheduling across four CPUs, and a TCP/IP stack. I also built checks outside the VM to inspect disk writes, verify packet checksums, and measure graphics and audio output. Getting it to work was one challenge; proving it worked was another.

### [Bloxnetic](https://www.bloxnetic.com)
*Co-founder & primary engineer · Next.js · TypeScript · Python · FastAPI*

A market research and advertising planning platform for Roblox developers. It tracked roughly **1,000 live games**, forecast ad click-through rates and revenue using Monte Carlo simulations of **100,000 player personas**, and included AI tools for creating advertising content.

I built the frontend, backend, game discovery crawlers, forecasting engines, and Stripe subscription and credit billing. The platform served **10–20 paying customers per month** before I sold it.

### Roblox multiplayer games
*Development & live operations · 2017–2026 · Luau/Lua*

I got started with Old Football Legends and went on to co-lead games with **100M+ combined visits**, including [Ro Evolution Soccer](https://www.roblox.com/games/82059022/Ro-Evolution-Soccer) at **12M+ visits**. My work covered gameplay updates, persistent player data, and production fixes during peaks of **2,000+ concurrent players**.

### [USC Seat Watcher](https://github.com/mcorwin17/usc-seat-watcher)

A small tool that polls Banner every 15 minutes for open course seats and creates a GitHub issue when one opens. GitHub notifications handle the email. Ran it for four days, got the seat, turned it off.

## What I'm working on

- **VR education at EITL:** A learning simulation for a provost-funded study, with server-authoritative quizzes, motion-controller interactions, and a research analytics pipeline that hashes participant identifiers before export.
- **Football manager simulation engine:** A Luau backend with reproducible seeded matches, asynchronous PvP, and 22 server-side services. Private repository. Apparently, I haven't stopped making football games.

---

**Languages:** C, C++, x86 Assembly, Python, TypeScript/JavaScript, Luau/Lua, SQL  
**Tools:** Next.js, FastAPI, PostgreSQL, Git, Docker, Linux, QEMU, pytest
