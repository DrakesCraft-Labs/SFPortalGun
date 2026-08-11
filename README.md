<p align="center"><img src="docs/banner.svg" alt="SFPortalGun banner" width="100%"></p>

# SFPortalGun

Linked portal and gravity tools for Slimefun. The addon turns point-to-point transport into a
crafted utility while retaining normal server-side safety checks.

## DrakesCraft edition

- Targets Java 21 and Paper/Purpur 1.21.11.
- Compiles against the DrakesCraft Slimefun compatibility namespace.
- Keeps the original item IDs and package layout stable.
- Uses current Paper APIs and maintained build repositories.

## Building

```bash
mvn -B -ntp clean package
```

Install the artifact from `target/` with
[`Slimefun4-Drake`](https://github.com/DrakesCraft-Labs/Slimefun4-Drake).

## Provenance

Integrated from [balugaq/SFPortalGun](https://github.com/balugaq/SFPortalGun).
Original authorship and the GPL-3.0 license are preserved.
