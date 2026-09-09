# Changelog

All notable, player-facing changes to Tir-na Nog'th. The format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/). Versions match the git tags.

The release workflow reads the section whose version matches the pushed tag and uses it as
that release's notes, so write each entry for a player, not a developer.

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
- Single-file Windows executable with all art, audio, and data embedded. Nothing to install.
- Six character classes on a shared passive tree of hand-authored nodes.
- Deep, interacting systems: seeded item drops, tier-ladder affixes, glyph and ink crafting,
  a scribe's bench, minions, auras, trigger glyphs, ailments, and hard crowd control.
- Procedurally generated maps across twelve layouts and eight biomes, with real wall collision,
  fog of war, and a minimap.
- A bestiary of twenty-six monster types, one exclusive family per biome.
- Persistent characters with a shared stash, a town, a vendor, and the Shadow-tier endgame climb.
