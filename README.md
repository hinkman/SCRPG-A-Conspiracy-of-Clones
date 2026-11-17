# SCRPG A Conspiracy of Clones

Unofficial Foundry VTT module for the Sentinel Comics RPG adventure issue **A Conspiracy of Clones** (core book pp. 269–289). Requires the [scrpg-foundry](https://github.com/hinkman/SCRPG-foundry) system. A copy of *Sentinel Comics: The Roleplaying Game* is required. This module does not replace the rules.

Structured like [SCRPG Battle of the Bands](https://github.com/hinkman/SCRPG-Battle-of-the-Bands).

## Contents

### A Conspiracy of Clones Scenes (Foundry Scene pack)
Import these into the **Scenes** sidebar:
- **Who Are You And What Have You Done With The Mayor?**
- **The Center for Advanced Genomic Research**
- **The Argaeus Tower**

### A Conspiracy of Clones Actors (Actor pack)
Organized by scene name, then by object type (Scene Trackers, Environments, Minions, Lieutenants, Villains).

> Note: Foundry’s Scenes directory only accepts native Scene documents. SCRPG’s mechanical scene tracker is an Actor subtype (`scene`) and lives in the Actors pack as “\* Tracker”.

## PDF status

Adventure content in `src/data/a-conspiracy-of-clones.json` is filled from book pp. 269–289 (zone-colored environment twists, minions, lieutenants, Biomancer issue sheet including masteries on p.283).

**Die glyphs:** the text extract omitted printed die art. Minion/lieutenant/environment trait die sizes are curated placeholders — confirm against the book art if a table disagrees.

## Install

Foundry 14 and `scrpg-foundry` 0.9.15 or newer. Install from:

`https://raw.githubusercontent.com/hinkman/SCRPG-A-Conspiracy-of-Clones/main/module.json`

Shared test world: Foundry host `services.hinkman.com:30000`, world `sc2` (same instance as Battle of the Bands).

## Rebuild the packs

```bash
npm install
npm run pack
```

Edit `src/data/a-conspiracy-of-clones.json`, then run `npm run pack`.
