# Certified Bops

Certified Bops is the **all-killer, no-filler** playlist in the Shared Music project.

It is not a chart, a time capsule, or a list of songs we merely respect. It is a collection of songs Aaron and Mitch genuinely want to hear again and again.

## What Belongs

A Certified Bop should be:

- Highly replayable
- Instantly recognizable or instantly lovable
- Fun, energetic, emotionally satisfying, or otherwise difficult to skip
- Strong enough to justify its place every time the playlist comes around

Popularity and critical acclaim are optional. Replay value is not.

## Sequencing Philosophy

The playlist should feel like a deliberately arranged set rather than a shuffled archive.

- Avoid back-to-back songs by the same lead artist.
- Preserve variety across genres, eras, moods, and production styles.
- Let energy rise and fall naturally instead of remaining pinned at maximum intensity.
- Avoid abrupt genre changes unless they create a useful surprise.
- Do not cluster songs from the same album without a specific reason.
- Protect strong openings, transitions, and closers.

## Source of Truth

`master.csv` is the canonical playlist file.

Current columns:

- `Artist`
- `Title`
- `Energy` — reserved for manual rating

When the playlist changes, update the CSV and preserve the commit history so additions, cuts, and sequencing decisions remain traceable.

## The Test

When a song comes on, are we happy it is there?

When the answer repeatedly becomes no, the song has probably stopped being a Certified Bop.