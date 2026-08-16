# Maxwell Corwin

CS student at the University of South Carolina, class of 2028. Co-founder and lead engineer at **Bloxnetic** (sold). XR developer at USC's Emergent Information Technology Lab.

I build simulation engines, backend systems, and full stack products. Most of my work lands somewhere between games and data.

## Code you can read

- **[MaxOS](https://github.com/mcorwin17/MaxOS)** is an x86 operating system written from scratch in assembly and C. It boots from its own 512-byte boot sector into a userspace shell, with everything in between built by hand: paging, preemptive scheduling across 4 CPUs, ring-3 processes with fork/exec/wait and copy-on-write, signals, pipes, a FAT16 filesystem it can read, write and format, a TCP/IP stack that works against real hosts, a 1024x768 framebuffer, and AC97 audio. About 9k lines, 20 automated test targets.

  My favorite part is that nothing grades its own homework: pixels get read out of QEMU screendumps, TCP checksums get recomputed from packet captures, disk writes get parsed out of the raw image, and audio gets measured from the rendered waveform.

- **[SmartRoute](https://github.com/mcorwin17/KTP-Hackathon)** turns messy inspector emails and OCR'd attachments into normalized records with action routing, using regex first and an LLM only where regex runs out. Scores 92 to 97% exact match on key fields against a 500 message eval harness. FastAPI, Pydantic, pytest, CI. Built at KTP's hackathon, which is why the repo has that name.

- **[Reading Assistant](https://github.com/mcorwin17/readerhelper)** is a Chrome extension that answers questions about the page you're reading, backed by OpenAI or a local Ollama model.

## Shipped

- **[Bloxnetic](https://www.bloxnetic.com)** was an AI market intelligence SaaS for Roblox developers, with 300+ registered. It ran Monte Carlo campaign forecasts against 100k simulated player personas. Next.js, FastAPI, PostgreSQL, Redis, Stripe. We sold it, so the live site isn't mine anymore.

- **Roblox live ops, 2017 to 2022.** Co-led development on titles with over 100M combined visits, including [Ro Evolution Soccer](https://www.roblox.com/games/82059022/Ro-Evolution-Soccer) (12M+ visits, 4k+ MAU, 2k+ peak concurrents).

## In progress

- **Football manager simulation engine** (Luau, private repo). A seeded, server authoritative match engine with an expected goals model. Every match can be replayed deterministically from a single RNG seed. About 50k lines across 22 services.

- **XR research at EITL.** An educational VR simulation on Roblox with a privacy focused learning analytics pipeline (Luau and Python over Open Cloud), built for a provost funded study.

## Stack

`Python` `TypeScript/JavaScript` `Luau/Lua` `C` `C++` `x86 assembly` `SQL`

`React` `Next.js` `Node.js` `FastAPI` `PostgreSQL` `Redis` `Prisma`

`Docker` `pytest` `QEMU` `Rojo/Lune`

## Contact

maxcorwin86@gmail.com
