# Bounce juggling simulator

A real-physics simulation of bounce juggling cascades, built collaboratively with Claude.ai — from a single ball up to a full 7-ball pattern.

**Live demo:** (add GitHub Pages URL once deployed)

## What this is

Each ball's trajectory is computed from real projectile motion (gravity, initial velocity, launch angle) and a real floor-bounce reflection (horizontal velocity preserved, vertical velocity scaled by a restitution coefficient) — not a hand-drawn curve fitted to look plausible. Launch angle is solved numerically so every throw lands precisely in the receiving hand.

Adjustable parameters:
- Launch speed, hand spacing, restitution
- Ball count: 1, 2, 3, 5, 7, or 9 — a structured practice progression
- A collapsible "custom asymmetry" panel for exploring uneven arm reach and height

## Attribution

This project builds on decades of work by the juggling and mathematics communities:

- **Siteswap notation** — invented by Paul Klimek (1981), independently formalized by Bruce Tiemann, Joel David Hamkins, and Bengt Magnusson at Caltech, and by Mike Day, Colin Wright, and Adam Chalcraft at Cambridge (1985)
- **Allen Knutson** — wrote the first siteswap animator, 1988
- **Jack Boyce** — creator of [Juggling Lab](https://jugglinglab.org), the standard modern juggling simulator
- **Vincent Bruel** — contributed bounce/hyperlift pattern support to Juggling Lab
- **Sean Gandini & Kati Ylä-Hokkala** (Gandini Juggling) — pioneers of bounce juggling as performance art
- **World Juggling Federation** — their public siteswap simulator at thewjf.com was a visual reference during development

## Built with

Claude (Anthropic).

