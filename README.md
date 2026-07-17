# Certified Bops

A version-controlled master playlist for Aaron and Mitch.

## Source of truth

`data/master.csv` is the canonical playlist database.

Current columns:

- `Artist`
- `Title`
- `Energy` — intentionally blank for manual rating

## Rules

1. Never treat a chat response as the master list.
2. Every playlist edit must update `data/master.csv`.
3. Every export must be generated from the master file.
4. Preserve commit history so additions, cuts, and sequencing changes remain traceable.

## Current status

Initial seed: 65 songs.

Next milestone: expand to 100 curated songs without duplicates, then hand-sequence the result.
