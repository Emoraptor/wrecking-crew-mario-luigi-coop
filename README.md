# Wrecking Crew — Mario and Luigi Co-op Edition (RC1)

A simultaneous 2-player co-op hack of the NES version of **Wrecking Crew**.

## Why I made this

I play retro games on a custom arcade cabinet at home, and I wanted a version of **Wrecking Crew** that my two sons could enjoy together.

The original game has alternating 2-player play, but I wanted something different:

**Mario and Luigi on screen at the same time, playing the same level together.**

This project started as a personal arcade experiment for my family, especially for my two children, **Victor and Raphaël**.

What began as a simple idea slowly turned into a full co-op conversion with new player behavior, enemy targeting, death logic, camera changes, visual tweaks, and a simplified arcade-style presentation.

The goal was never to replace the original game — just to create the version I wished existed when playing with my kids.

## What this edition changes

- Mario and Luigi play **simultaneously** on the original Wrecking Crew phases.
- Player 2 uses a Luigi-style character instead of the stationary/background Spike setup.
- If one brother is knocked out, the surviving brother can continue the phase.
- Gotchawrench enemies remain active and rotate their target between the brothers.
- Fireballs can target either brother.
- The gameplay camera is fixed to a wider practical framing so both players can separate while most or all of the useful level space remains visible.
- Co-op starts by default from a simplified title menu.
- Custom Mario and Luigi palettes.
- Updated title presentation.
- Intro text: **BROS! WRECK!**
- A faster “last brother standing” music cue plays after the first KO.
- The original Wrecking Crew phase set is preserved.

## Gameplay philosophy

The main goal of this hack is simple:

**keep both players involved at the same time.**

The camera was adjusted specifically for co-op play so Mario and Luigi can move farther apart without one player constantly losing visibility.

Enemy behavior was also adapted so the game does not simply behave as if Mario is the only active player.

The intention is to keep the original Wrecking Crew experience recognizable while making it feel natural as a simultaneous 2-player game.

## Credits

1. **David / Emoraptor (Underdog Factory)** — concept, project direction, gameplay design, testing, and final decisions.
2. **ChatGPT “L”** — reverse engineering, programming, co-op integration, camera system, AI behavior, and patching tools.
3. **Gemini “N”** — visual support, ideas, and collaboration on various elements of the project.
4. **Q____ & puchiedarcy** — creators of *Wrecking Two*, the original foundation for the simultaneous 2-player concept.
5. **Marjory, Victor & Raphaël** — sources of happiness, hope, and inspiration. I LOVE YOU SO MUCH

Special thanks to the original *Wrecking Two* authors.

Their work demonstrated the possibility of simultaneous 2-player gameplay in Wrecking Crew and provided the original foundation that inspired this project.

This edition restores the original phase set and substantially reworks the co-op behavior, visuals, enemy targeting, death flow, camera, and presentation.

## Applying the patch

No ROM is included.

Use an IPS patcher, such as **Floating IPS / Flips**, and apply:

`Wrecking_Crew_Mario_Luigi_Coop_Edition_RC1.ips`

to the exact base ROM:

**Wrecking Crew (World) [NES/iNES]**

### Base ROM checksums

- SHA-1: `31635f1a5255fe8954c5a275b067f603bb7af408`
- MD5: `b9abb75ac20aae1f6ba5a5da178d69e0`
- CRC32: `658d4fd4`
- Size: `40976 bytes`

### Expected patched ROM

- SHA-1: `52e82598afdb26fe69814df6607e2117563e0f92`
- MD5: `4ab50811a103a673c02c5c2b1093f7d6`
- CRC32: `baa7b0d9`
- Size: `40976 bytes`

## RC1 status

The core co-op system and fixed-camera presentation are working.

RC1 is being tested across the full 100-phase set before the final v1.0 tag.

## Project status

**Complete.**

This project was created primarily for my home arcade cabinet and for my two sons.

I do not currently plan active development.

The project is public so other people can enjoy it, study it, fork it, experiment with it, or improve it further.

If someone takes the idea further someday, that is perfectly fine with me.

## Distribution

Please distribute **the patch, not a complete ROM image**.

No copyrighted ROM is included with this project.

## Legal notice

**Wrecking Crew**, Mario, Luigi, and related characters and properties belong to Nintendo and their respective rights holders.

This is a non-commercial fan modification created for personal enjoyment and preservation of retro gaming culture.
