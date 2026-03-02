# Weekndle

A Wordle-style guessing game for The Weeknd's discography. Guess the hidden song in 8 tries or fewer, using feedback on album, track number, duration, and streams.

## How to Play

Each guess reveals color-coded feedback across four columns:

- **Album** — Green if exact. Yellow if the correct song is within +/- 2 albums in the discography. An arrow shows which direction to guess.
- **Track Number** — Green if exact. Yellow if within +/- 2 tracks on the same album. Arrow indicates higher or lower.
- **Duration** — Green if exact. Yellow if within +/- 30 seconds. Arrow indicates longer or shorter.
- **Streams** — No yellow. Only shows whether the correct song has more or fewer Spotify streams than your guess.

## Pages

- `index.html` — The main game
- `discography.html` — Browse all 130 tracks grouped by album with stream counts

## Data

`db.json` contains all track data including duration, track number, album number, and approximate Spotify stream counts. Albums included:

1. House of Balloons (2011)
2. Thursday (2011)
3. Echoes of Silence (2011)
4. Kiss Land (2013)
5. Beauty Behind the Madness (2015)
6. Starboy (2016)
7. My Dear Melancholy, (2018)
8. After Hours (2020)
9. Dawn FM (2022)
10. Hurry Up Tomorrow (2025)

No deluxe tracks are included. Twenty Eight, Valerie, and Till Dawn each count as track 10 on their respective mixtapes.

## Notes

- Stream counts are approximate figures from Spotify as of early 2026.
- A new random song is picked each time you start or restart the game.
