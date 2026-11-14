# CTF & VDP

English | [日本語](README.ja.md)

Public CTF writeups, cloud/web security lab notes, and sanitized VDP (Vulnerability Disclosure Program) pilot records, organized by platform and event.

## VDP Pilot (HackerOne)

Scheduled Nov 9–21, 2026 (Monday–Saturday, 08:00–09:00 JST). Target names, unpublished findings, raw logs, and credentials are never stored in this public repository.

| Document | Contents |
| --- | --- |
| [Public daily progress](hackerone/vdp-pilot-public-progress-2026-11.md) | Session durations, high-level actions, setbacks, and stop reasons (Japanese) |
| [VDP pilot design (2 weeks / 12 hours)](hackerone/hackerone-vdp-pilot-design-2026-11-08.md) | Scope selection, time budgets, AI-assist boundaries, and stop rules (Japanese) |
| [Learning & practice roadmap](hackerone/hackerone-learning-roadmap.md) | Initial Hacker101 -> Hacktivity -> VDP transition plan (Japanese) |
| [ctf-vdp-harness](https://github.com/moruku36/ctf-vdp-harness) | Companion MCP analysis harness used for bounded CTF/VDP verification |

## CTF & Lab Summary

| Event / Platform | Status / Recorded Score | Date | Main Entry |
| --- | --- | --- | --- |
| [Hacker101 CTF](#hacker101-ctf) | 283 pts across 26 challenges | 2026-10-29 – 11-02 | [hacker101/README.md](hacker101/README.md) |
| [PumpkinShell (Wiz)](#pumpkinshell) | 5/5 solved (95/100 pts) | 2026-10-27 | [Section](#pumpkinshell) · [Certificate](pumpkinshell/pumpkinshell-certificate.png) |
| [Pwned Labs](#pwned-labs) | AWS Blue Teaming (3) & Google Storage (1) | 2026-10-22 – 10-23 | [Section](#pwned-labs) |
| [Prompt Airlines](#prompt-airlines) | 5/5 solved + live replay | 2026-10-18 – 10-22 | [Section](#prompt-airlines) · [Certificate](prompt-airlines/prompt-airlines-certificate.png) |
| [Cloud Security Championship](#cloud-security-championship) | #1, #6 solved; #2, #4, #5, #7 walkthrough-verified | 2026-10-16 – 10-22 | [Section](#cloud-security-championship) · [RESULTS.md](RESULTS.md) |
| [The Cloud Hunting Games](#the-cloud-hunting-games) | 5/5 solved (40 pts) | 2026-10-18 | [Writeup](cloud-hunting-games/cloud-hunting-games-2026-10-18.md) · [Certificate](cloud-hunting-games/cloud-hunting-games-certificate.png) |
| [K8s LAN Party](#k8s-lan-party) | 2/5 verified (see note in RESULTS.md) | 2026-10-16 | [RESULTS.md](RESULTS.md) · [Certificate](k8s-lan-party/k8s-lan-party-certificate.png) |

## Writeups by Event

### Hacker101 CTF

- [Hacker101 CTF writeups and progress table](hacker101/README.md)

### PumpkinShell

All 5 challenges solved, 95/100 pts (2026-10-27).

- [Dependency Issues](pumpkinshell/pumpkinshell-dependency-issues-2026-10-27.md)
- [Gist of the Problem](pumpkinshell/pumpkinshell-gist-of-the-problem-2026-10-27.md)
- [It Sucks](pumpkinshell/pumpkinshell-it-sucks-2026-10-27.md)
- [Through the Lens](pumpkinshell/pumpkinshell-through-the-lens-2026-10-27.md)
- [Unlock the Core Memory](pumpkinshell/pumpkinshell-unlock-the-core-memory-2026-10-27.md)
- [Certificate](pumpkinshell/pumpkinshell-certificate.png)

### Cloud Security Championship

Challenge #1 is recorded in [RESULTS.md](RESULTS.md). Writeups for #2, #4, #5, #6, #7 and an investigation log for the remaining challenges:

- [#2 — Contain Me If You Can](cloud-security-championship/cloud-security-championship-contain-me-if-you-can-2026-10-22.md)
- [#4 — Needle in a Haystack](cloud-security-championship/cloud-security-championship-needle-in-a-haystack-2026-10-22.md)
- [#5 — Game of Pods](cloud-security-championship/cloud-security-championship-game-of-pods-2026-10-22.md)
- [#6 — Malware Busters!](cloud-security-championship/cloud-security-championship-malware-busters-2026-10-18.md) · [Certificate](cloud-security-championship/cloud-security-championship-malware-busters-certificate.png)
- [#7 — State of Affairs](cloud-security-championship/cloud-security-championship-state-of-affairs-2026-10-22.md)
- [Investigation log for unsolved challenges](cloud-security-championship/cloud-security-championship-partial-progress-2026-10-22.md)

### The Cloud Hunting Games

All 5 challenges cleared, 40 pts (2026-10-18).

- [Writeup](cloud-hunting-games/cloud-hunting-games-2026-10-18.md) · [Certificate](cloud-hunting-games/cloud-hunting-games-certificate.png)

### Prompt Airlines

All 5/5 challenges cleared, plus a live replay.

- [5/5 challenges (2026-10-18)](prompt-airlines/prompt-airlines-2026-10-18.md)
- [Live 5/5 replay (2026-10-22)](prompt-airlines/prompt-airlines-2026-10-22.md)
- [Membership-card generator script (challenge 4)](prompt-airlines/make-member-card.ps1)
- [Certificate](prompt-airlines/prompt-airlines-certificate.png)

### K8s LAN Party

2 of 5 challenges recorded in [RESULTS.md](RESULTS.md) (2026-10-16).

- [Earliest results and walkthrough verification notes](RESULTS.md) · [Certificate](k8s-lan-party/k8s-lan-party-certificate.png)

### Pwned Labs

- [AWS Blue Teaming — 3 labs solved](pwned-labs/pwned-labs-aws-blue-teaming-2026-10-22.md)
- [Reveal Hidden Files in Google Storage](pwned-labs/pwned-labs-reveal-hidden-files-google-storage-2026-10-23.md)
- [Free-lab progress log](pwned-labs/pwned-labs-partial-progress-2026-10-23.md)

## Conventions & Safe Disclosure

- **Structure**: One directory per platform or event; writeups follow `<event>-<challenge>-<date>.md`.
- **Provenance**: Writeups distinguish independent solves from flags verified via public walkthroughs when lab environments were degraded (see [RESULTS.md](RESULTS.md)).
- **Redaction**: Real credentials, passwords, session tokens, private target details, and personal data are never committed.

## References

- [HackerOne](https://www.hackerone.com/) · [HackerOne Documentation](https://docs.hackerone.com/en/) · [HackerOne on X](https://x.com/Hacker0x01)
