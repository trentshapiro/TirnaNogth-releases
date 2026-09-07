# Changelog

All notable, player-facing changes to Tir-na Nog'th are recorded here. The format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/). Versions match the git tags.

The release workflow reads the section whose version matches the pushed tag and uses it as
that release's notes, so write each entry for a player, not a developer.

## [Unreleased]

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
