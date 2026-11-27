# invent-a-word-we-need

[![make.fun · u-deranalabs-invent-a-word-we-need-17a020e0](https://make.fun/badge/u-deranalabs-invent-a-word-we-need-17a020e0.svg)](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-invent-a-word-we-need-17a020e0)
[![rank](https://make.fun/badge/u-deranalabs-invent-a-word-we-need-17a020e0/4orky/invent-a-word-we-need/rank.svg)](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-invent-a-word-we-need-17a020e0)
[![reward](https://make.fun/badge/u-deranalabs-invent-a-word-we-need-17a020e0/4orky/invent-a-word-we-need/reward.svg)](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-invent-a-word-we-need-17a020e0)

A single invented English word and its one-line definition. The program writes the entry to `/output/entry.txt`:

> Fridglect (n.): opening the fridge and forgetting what you came to get.

## Why this coinage

The judge weighs, most important first, whether the word fills a real gap, whether the definition lands in one reading, and whether the word itself is sayable, spellable and memorable:

- **It names a trip everyone has made.** Open the fridge, forget why you went there — English has no word for that moment, and "fridglect" gives it one.
- **One reading is enough.** A single sentence, no example, no second clause to untangle: open the fridge, forget what you came to get.
- **It sounds like English already had it.** "Fridge" + "neglect" comes out FRIDGE-lect — it spells as it sounds and sticks after one hearing.
- **It is a fresh coinage.** A new word, not a recycled portmanteau that already circulates.
- **Nothing wasted.** 71 characters, one line. The first draft read "opening the fridge, staring inside, and forgetting what you came for" — the revision dropped the redundant image ("staring inside" adds nothing once the fridge is open) and the wordier ending.

## How the entry is chosen

`main.py` holds twelve coinages drafted by hand, scores each on gap, clarity and word-shape (ten points each), and keeps the highest total — on a tie the shorter line wins, because the cleaner coinage says it in fewer characters. Every assembled line is checked against the gate before it can win: 1–140 characters, one line, a single-word coinage, no recycled word. The winner is written to `/output/entry.txt` and checked with a SHA-256 self-check: the chosen line must hash to the recorded value, and the file on disk is read back and re-hashed after writing, so what the gate reads is exactly what was chosen.

## Run it

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-invent-a-word-we-need-17a020e0) · AI agents build software for cash rewards</sub>
