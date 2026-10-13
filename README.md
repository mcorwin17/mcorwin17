<p align="center">
  <a href="https://github.com/mcorwin17/MaxOS">
    <img src="https://raw.githubusercontent.com/mcorwin17/mcorwin17/main/boot.svg" alt="MaxOS boot sequence — Maxwell Corwin, computer science at South Carolina" width="880">
  </a>
</p>

I'm **Maxwell Corwin**, a computer science student at the **University of South Carolina, class of 2028**. I build operating systems, backend services, and multiplayer games. I co-founded and sold **Bloxnetic**, a software business serving Roblox developers.

My work spans kernel internals, products with paying customers, and live games with thousands of concurrent players. I care about understanding how a system works—and having a way to verify that it does.

[Email](mailto:maxcorwin86@gmail.com) · [MaxOS source](https://github.com/mcorwin17/MaxOS) · [Bloxnetic](https://www.bloxnetic.com)

## Selected work

### [MaxOS — an operating system from the boot sector up](https://github.com/mcorwin17/MaxOS)
**C · x86 Assembly · QEMU**

A 32-bit x86 OS with its own bootloader, kernel, filesystem, and userspace. It boots into a shell that loads programs from disk and supports pipelines and output redirection.

- **Memory and processes:** demand paging, isolated ring-3 processes, copy-on-write `fork`, `exec`, signals, and preemptive scheduling.
- **Hardware and I/O:** four-CPU kernel scheduling, writable FAT16, a TCP/IP stack, framebuffer graphics, and AC97 audio.
- **Verification:** host-side checks inspect disk persistence, packet checksums, rendered pixels, and audio waveforms. Tests check observable output beyond the kernel's own logs.

[Architecture, limitations, and build instructions →](https://github.com/mcorwin17/MaxOS#readme)

### [Bloxnetic — building and selling a software product](https://www.bloxnetic.com)
**Co-founder & primary engineer · TypeScript · Next.js · Python · FastAPI**

A market-intelligence and advertising-planning platform for Roblox developers. I built the application across frontend, backend, data collection, forecasting, and billing, then sold the business.

- Served **500+ registered users**, **200+ active users**, and **10–20 paying customers per month**.
- Tracked approximately **1,000 live games** and built Monte Carlo forecasts for advertising CTR and revenue using **100,000 simulated player personas**.
- Shipped game-discovery crawlers, AI-assisted creative tools, and Stripe subscriptions and credit billing.

### Multiplayer games — development through live operations
**Luau / Lua · Gameplay systems · Persistent data · Production debugging**

I co-led development and live operations for Roblox games with **100M+ combined visits**, including [Ro Evolution Soccer](https://www.roblox.com/games/82059022/Ro-Evolution-Soccer) and Old Football Legends.

- Worked on a flagship with **12M+ visits** and **4,000+ monthly active users**.
- Shipped gameplay updates and production hotfixes during peaks of **2,000+ concurrent players**, with player data and service uptime at stake.

## Current work

**Developer at Shikari** — ecommerce software, with work on IMAP email integration, UI, and application performance.

**XR Developer at USC's Emergent Information Technology Lab** — a VR learning simulation for a provost-funded study, including server-authoritative quizzes, motion-controller interactions, and research analytics with hashed participant identifiers.

## Technical toolkit

**Systems:** C, C++, x86 Assembly, Linux, QEMU  
**Backend & data:** Python, TypeScript, Node.js, FastAPI, PostgreSQL, SQL  
**Applications & games:** React, Next.js, Luau/Lua, Roblox  
**Development:** Git, Docker, pytest, Vitest
