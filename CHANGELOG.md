# Changelog

All notable, player-facing changes to Tir-na Nog'th. The format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/). Versions match the git tags.

The release workflow reads the section whose version matches the pushed tag and uses it as
that release's notes, so write each entry for a player, not a developer.

## [0.4.0] - 2026-10-21

### Added

- New interactions: sealed hoards that spring guards, sleeping wardens, and shrines that give boons.
- In-game composable loot filter.
- New graphics.

- Stash tab card affinities.
- A Gameplay page in the settings.

### Changed

- Walking into a fragment no longer stutters.

- Any glyph fits any skill. It will sometimes do nothing!
- One skill cannot use the same glyph twice.
- Reduced the Inner Pattern instances of glyph capacity, chain, and projectile count.
- The Inner Pattern's damage nodes are mostly switched to "increased" from "more".
- Inner Pattern tooltips hover instead of anchored to the bottom of the screen.
- No card grants more than one glyph slot.

- Added self-burn to Devotion Aura.
- Holding a key uses that key again as soon as it can.
- Ground loot is easier to read.
- The cursor has a darker outline.
- More scribe's desk control flow logic.
- Picking up one ink picks up every other ink within reach.

### Note

- The save format has changed, old saves will be ignored/corrupted.

## [0.3.0] - 2026-09-12

### Added

- The Compendium, an in-game wiki of 304 pages, opened from the Escape menu and searchable.
- A card or monster page stands its model in a case you can turn.
- The scribe's desk runs recipes: apply an ink, branch on what the card reads, repeat until a
condition holds, and compose one recipe into another.
- Example recipes come with every account, shared by all your characters.
- A recipe runs one operation at a time so you can watch it, at 1x, 2x or 3x, and end it between
two steps without losing incremental progress.
- Before a run, the scribe estimates it over 240 dry runs: how often it reaches the end, how many
loops it takes, and how much ink it wants against how much you hold.
- A cap on how many loops one run may take, which you set.
- The desk has three tabs: Inks, Pool and Recipe.
- Roll Until is a recipe now rather than a button of its own.

## [0.2.0] - 2026-09-08

### Added

- The Inner Pattern replaces the passive tree.
- A summon key pressed at full count rallies instead of doing nothing.
- Unique animations for most skills

### Changed

- Weapons read differently in the hand and have updated animations.
- Crush is now Divine Hammer.
- Thorn Burst is held rather than cast. Brambles crawl out around you while you hold it, slowing and
bleeding enemies in range, and letting go bursts the thorns for more damage the longer you held.
- Frost Nova leaves a patch of frost that keeps applying cold DoT where it lands.
- The level cap is set to sixty, expect about four levels to a Shadow tier.
- Maps are larger with wider corridors. Monster packs grew to match to preserve density.
- The merchant's stall grows with the Shadow tier.
- Flame beam costs far less mana and hits far harder.
- Characters saved by 0.1.1 will not load.
- Updated many skills' descriptions to match intended effects more concretely.
- Added "Aura" skill tag.

### Fixed

- Blur behind panels now obeys its own setting on the title screen and in dialogue, not just in play.
- A body standing deep behind a wall is outlined again, as it was before the cast became imported models.
- An ink that raised a card to rare left it wearing its old magic name.
- A chasing monster could freeze in place against a wall.
- Greyed-out buttons still looked live on most panels.
- A held mouse skill stopped firing when the cursor crossed the action bar or an item label.
- Centered the XP bar.
- Projectiles look correct.

## [0.1.1] - 2026-09-06

### Fixed

- Removed a leftover developer key legend from the bottom of the release screen. The debug keys
themselves were never in a release build; only the on-screen text remained. Production builds now
refuse to package if any developer tooling is present.

## [0.1.0] - 2026-09-06

First public build.

### Added

- Single-file Windows executable with all art and data embedded. Nothing to install.
- Six character classes on a shared passive tree of hand-authored nodes.
- Deep, interacting systems: seeded item drops, tier-ladder affixes, glyph and ink crafting,
a scribe's bench, minions, auras, trigger glyphs, ailments, and hard crowd control.
- Procedurally generated maps across twelve layouts and eight biomes, with real wall collision,
fog of war, and a minimap.
- A bestiary of twenty-six monster types, one exclusive family per biome.
- Persistent characters with a shared stash, a town, a vendor, and the Shadow-tier endgame climb.