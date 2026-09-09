# Maxwell Corwin

CS at the University of South Carolina, class of 2028. Co-founder and lead engineer at Bloxnetic (sold). XR developer at USC's Emergent Information Technology Lab.

Simulation engines, backend systems, full stack products. Most of my work lands somewhere between games and data.

### projects

**[MaxOS](https://github.com/mcorwin17/MaxOS)** — x86 operating system, boot sector up. Paging, preemptive scheduling across 4 CPUs, ring-3 processes with fork/exec and copy-on-write, FAT16, pipes, TCP/IP, framebuffer, AC97 audio. Boots into its own userspace shell. ~9k lines, 20 test targets.

Everything is checked from outside the VM. Pixels come out of QEMU screendumps, TCP checksums get recomputed from packet captures. The guest doesn't grade its own work.

```c
/* This was missing for months. It went unnoticed because the RAM
 * underneath happened to be zero, until an array landed past the end
 * of the loaded image and came up holding 0xf000fea5. */
for (char* p = bss_start; p < bss_end; ++p) *p = 0;
```

**[SmartRoute](https://github.com/mcorwin17/KTP-Hackathon)** — extraction engine for inspector emails and OCR'd attachments. Regex first, LLM only where regex gives up. 92-97% exact match on a 500 message eval set. FastAPI, Pydantic, CI.

**[Reading Assistant](https://github.com/mcorwin17/readerhelper)** — Chrome extension that answers questions about the page you're on, and cites the spans it pulled from. OpenAI or a local Ollama model.

### shipped

**[Bloxnetic](https://www.bloxnetic.com)** — AI market intelligence for Roblox developers. Monte Carlo campaign forecasts against 100k simulated player personas. 300+ registered. Next.js, FastAPI, Postgres, Redis, Stripe. Sold.

**Roblox live ops, 2017 to 2022** — co-led titles totalling 100M+ visits. [Ro Evolution Soccer](https://www.roblox.com/games/82059022/Ro-Evolution-Soccer) did 12M visits, 4k MAU, 2k peak concurrents.

### now

**Football manager simulation engine.** Seeded and server authoritative, so any match replays exactly from one RNG seed. Expected goals model. ~50k lines, 22 services. Private repo.

**XR research at EITL.** Educational VR sim on Roblox with a privacy-focused learning analytics pipeline, built for a provost-funded study.

---

`python` `typescript` `luau` `c` `x86 asm` `sql` · `fastapi` `next.js` `postgres` `redis` · `docker` `qemu` `pytest`

maxcorwin86@gmail.com
