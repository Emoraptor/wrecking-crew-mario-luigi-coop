# Wrecking Crew — Mario and Luigi Co-op Edition (RC1)

A simultaneous 2-player co-op hack of the NES version of **Wrecking Crew**.

## What this edition changes

- Mario and Luigi play **simultaneously** on the original Wrecking Crew phases.
- Player 2 uses a Luigi-style character instead of the stationary/background Spike setup.
- If one brother is knocked out, the surviving brother can continue the phase.
- Gotchawrench enemies remain active and rotate their target between the brothers.
- Fireballs can target either brother.
- The gameplay camera is fixed to a wider practical framing so both players can separate while most/all useful level space stays visible.
- Co-op starts by default from the simplified title menu.
- Custom Mario/Luigi palettes and updated title presentation.
- Intro text: **BROS! WRECK!**
- A faster "last brother standing" music cue plays after the first KO.

## Credits

1. **David / Emoraptor (Underdog Factory)** — concept, project direction, gameplay design, testing, and final decisions.
2. **ChatGPT “L”** — reverse engineering, programming, co-op integration, camera system, AI behavior, and patching tools.
3. **Gemini “N”** — visual support, ideas, and collaboration on various elements of the project.
4. **Q____ & puchiedarcy** — creators of *Wrecking Two*, the original foundation for the simultaneous 2-player concept.
5. **Marjory, Victor & Raphaël** — sources of happiness, hope, and inspiration.

**Wrecking Crew** and its characters are properties of Nintendo.

Special thanks to the original *Wrecking Two* authors. This edition restores the original phase set and substantially reworks the co-op behavior, visuals, enemy targeting, death flow, and camera.

## Applying the patch

No ROM is included.

Use an IPS patcher (for example Floating IPS / Flips) and apply:

`Wrecking_Crew_Mario_Luigi_Coop_Edition_RC1.ips`

to the exact base ROM:

**Wrecking Crew (World) [NES/iNES]**

Base ROM checksums:

- SHA-1: `31635f1a5255fe8954c5a275b067f603bb7af408`
- MD5: `b9abb75ac20aae1f6ba5a5da178d69e0`
- CRC32: `658d4fd4`
- Size: `40976 bytes`

Expected patched ROM:

- SHA-1: `52e82598afdb26fe69814df6607e2117563e0f92`
- MD5: `4ab50811a103a673c02c5c2b1093f7d6`
- CRC32: `baa7b0d9`
- Size: `40976 bytes`

## RC1 status

The core co-op system and fixed-camera presentation are working. RC1 is being tested across the full 100-phase set before the final v1.0 tag.

## Distribution

Please distribute **the patch, not a complete ROM image**.

Project status: Complete. No active development is planned. Forks, experiments and further improvements are welcome.
