# Home SOC Lab (Alex)

A hands-on home lab for learning SOC analyst and blue team skills, built while studying for CompTIA CySA+ (CS0-004). This repo documents the build process, study notes, and day-to-day progress.

Inspired by (and built alongside) my brother Tyler's lab: [tylerja425/homesoc-lab](https://github.com/tylerja425/homesoc-lab).

## Who's working on this

Alex Jackson (IT Support Specialist, Security+/Network+/A+/ITF+ certified), studying toward CySA+ (CS0-004).

## Goal

Build practical, documented experience with SOC tooling (SIEM, log analysis, detection writing) to support a move into a SOC analyst role, alongside earning CySA+.

## Lab environment

- Hypervisor: Proxmox VE, shared host (`SV1`) with Tyler
- SIEM / NSM platform: Security Onion (Tyler's instance, VM 101 — shared, not rebuilt from scratch)
- My VMs: `kali-attacker-alex` (106), `metasploitable-alex` (107)
- Network: own IP range on the shared host (`10.10.20.x`, to be confirmed with Tyler before first boot)

See `docs/` for full setup details as each piece comes online.

## Repo structure

- `docs/` — Finished writeups of what's been built: setup guides, architecture, configuration decisions.
- `notes/` — Study notes organized by CySA+ CS0-004 exam domain.
- `journal/` — Dated, running log of work sessions: what was done, what broke, what was learned.

## Status

Just getting started. GitHub + note-taking workflow set up. Kali Linux installer ISO confirmed present on `SV1` local storage. Next: create VM 106 (`kali-attacker-alex`).

## Disclaimer

This is a personal learning lab. Nothing here reflects production security practices or represents any employer's systems or data.
