# Maxwell Corwin

CS at the University of South Carolina, class of 2028. Built and sold [Bloxnetic](https://www.bloxnetic.com). XR stuff at USC's Emergent Information Technology Lab.

Simulation engines, backend systems, full stack products. Most of my work lands somewhere between games and data.

### projects

**[MaxOS](https://github.com/mcorwin17/MaxOS)**, an x86 operating system. Boots off its own 512 byte sector into a userspace shell that it loads through its own FAT16 driver. Paging, 4 CPUs, fork/exec with copy-on-write, signals, pipes, TCP/IP, a framebuffer, sound. About 9k lines.

Testing was the hard part, since a kernel will happily tell you it works. So the checks all run from outside the VM, screendumps for pixels and packet captures for checksums.

**[SmartRoute](https://github.com/mcorwin17/KTP-Hackathon)**, regex-first extraction for messy inspector emails, LLM only where the regex gives up. 92-97% exact match against a 500 message eval set. Built at a hackathon, hence the repo name.

**[Reading Assistant](https://github.com/mcorwin17/readerhelper)**, a Chrome extension that answers questions about whatever page you're on and cites the spans it used. Not on the store, you load it unpacked.

### before

**[Bloxnetic](https://www.bloxnetic.com)**, AI market intelligence for Roblox developers. Monte Carlo campaign forecasts against 100k simulated players, 300+ registered, then sold.

**Roblox live ops, 2017 to 2022.** Co-led a few titles that did 100M+ visits between them, biggest was [Ro Evolution Soccer](https://www.roblox.com/games/82059022/Ro-Evolution-Soccer) at 12M.

### right now

A football manager simulation engine in Luau. Seeded and server authoritative, so any match replays exactly from one RNG seed. Around 50k lines across 22 services, private repo.

VR education sim at EITL with a privacy focused learning analytics pipeline, built for a provost funded study.

python, typescript, luau, c, x86 asm, sql. fastapi, next.js, postgres, redis. docker, qemu, pytest.

maxcorwin86@gmail.com
