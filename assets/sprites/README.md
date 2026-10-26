# Placeholder art

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="PolyForm Noncommercial License 1.0.0">
</p>

These are **generated placeholders**, not the *Aethelgard* game's artwork (which
is © Dr. Sohil Momin, all rights reserved, and not included in this repository).
They exist only so the demo runs with something on screen. These placeholders
are PolyForm Noncommercial-licensed like the engine.

Replace them with your own art. The engine finds a portrait by name:

    char.<id>.<expression>  ->  <sprite>_<expression>.webp, then <sprite>.webp

and a background by region:

    bg.<region>  ->  bg_<region>.webp

Then rebuild the index:  `python3 tools/make-sprite-index.py assets/sprites`
