<p align="center">
  <img src="https://raw.githubusercontent.com/mcorwin17/mcorwin17/main/boot.svg" alt="MaxOS boot log - maxwell corwin, cs @ south carolina" width="880">
</p>

I'm Maxwell, a computer science student at the University of South Carolina. I build backend systems, simulation engines, and web apps. I co-founded and sold [Bloxnetic](https://www.bloxnetic.com), and I currently work on VR education at USC's Emergent Information Technology Lab.

### Projects

#### [MaxOS](https://github.com/mcorwin17/MaxOS)

A 32-bit x86 operating system written in C and assembly. It started as a class project at GSSM, and I kept going. The boot log above is real output: MaxOS boots from its own 512-byte boot sector and loads a userspace shell through its own FAT16 driver.

It supports paging, scheduling across four CPUs, fork/exec with copy-on-write, signals, pipes, TCP/IP, graphics, and audio. Kernel threads run across all four CPUs; user processes currently run on CPU 0.

Testing became a project of its own. I built checks outside the VM to inspect disk writes, verify packet checksums, and measure rendered pixels and audio output. A success message from the kernel only tells you so much.

#### [USC Seat Watcher](https://github.com/mcorwin17/usc-seat-watcher)

A small tool that polls Banner every 15 minutes for open course seats and creates a GitHub issue when one opens. GitHub notifications handled the email delivery. Ran it for four days, got the seat, turned it off.

### Previous work

#### [Bloxnetic](https://www.bloxnetic.com) · Co-founder & primary engineer

A market research and advertising planning platform for Roblox developers. It tracked roughly 1,000 live games and used Monte Carlo simulations of 100,000 player personas to estimate ad click-through rates and revenue. Developers could also use AI tools to generate advertising creative.

I built the Next.js/TypeScript frontend, Python/FastAPI backend, forecasting engines, game discovery crawlers, and Stripe subscription and credit billing. The platform had 10–20 paying customers per month before I sold it.

#### Roblox game development & live operations · 2017–2026

I started with Old Football Legends and went on to co-lead development and live operations for multiplayer games with more than 100 million combined visits. These included [Ro Evolution Soccer](https://www.roblox.com/games/82059022/Ro-Evolution-Soccer), which reached 12 million visits. The work included gameplay updates, player data persistence, and production fixes during peaks of more than 2,000 concurrent players.

### Current work

**Football manager simulation engine** — A Luau backend with a seeded match simulator, asynchronous PvP, and 22 server-side services. Matches can be replayed from the same random seed. The repository is private. Apparently, I haven't stopped making football games.

**VR education at EITL** — A learning simulation for a provost-funded study, with server-authoritative quizzes, VR interfaces, and a research analytics pipeline that hashes participant identifiers before export.

<sub>python · typescript · luau · c · x86 asm · sql · fastapi · next.js · postgres · redis · docker · qemu · pytest</sub>

<sub>maxcorwin86@gmail.com</sub>
