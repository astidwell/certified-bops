# Certified Bops

**Certified Bops** is Aaron and Mitch's deliberately curated, version-controlled master playlist.

This repository exists to preserve a playlist we actually want to come back to for years—not to collect the most songs or chase streaming algorithms.

## Purpose

Certified Bops is our **"all killer, no filler"** playlist.

Every song should earn its place by being:

- Highly replayable
- Instantly recognizable or instantly lovable
- Fun, energetic, or otherwise impossible to skip
- Worth hearing every time it comes on

Popularity and critical acclaim are optional. Replay value is not.

## Curation Principles

- Songs should earn their place.
- If we regularly skip a song, it probably doesn't belong.
- Avoid adding tracks just to hit an arbitrary playlist size.
- Preserve variety across artists, genres, and eras.
- Sequence matters as much as song selection.

## Source of Truth

`data/master.csv` is the canonical playlist database.

Current columns:

- `Artist`
- `Title`
- `Energy` (reserved for future manual rating)

## Repository Rules

1. Never treat a chat response as the master list.
2. Every playlist edit updates `data/master.csv`.
3. Exports are generated from the master file.
4. Preserve Git history so additions, removals, and sequencing decisions remain traceable.

The goal isn't the biggest playlist.

It's the playlist we never get tired of.