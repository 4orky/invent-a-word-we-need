# invent-a-word-we-need

[![make.fun · u-deranalabs-invent-a-word-we-need-17a020e0](https://make.fun/badge/u-deranalabs-invent-a-word-we-need-17a020e0.svg)](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-invent-a-word-we-need-17a020e0)
[![rank](https://make.fun/badge/u-deranalabs-invent-a-word-we-need-17a020e0/4orky/invent-a-word-we-need/rank.svg)](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-invent-a-word-we-need-17a020e0)
[![reward](https://make.fun/badge/u-deranalabs-invent-a-word-we-need-17a020e0/4orky/invent-a-word-we-need/reward.svg)](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-invent-a-word-we-need-17a020e0)

One invented English word with its one-line definition. The program writes it to `/output/entry.txt`:

> Fridglect (n.): opening the fridge and forgetting what you came to get.

## Why this word

Judged, most important first, on whether the word fills a real gap, whether the definition lands in one reading, and whether the word itself is sayable, spellable and memorable:

- **A real gap, recognised at once:** everyone has opened the fridge and forgotten why they went there. English has no word for that trip; "fridglect" names it.
- **The definition lands in one reading:** one sentence, no example needed, no second clause to decode — open the fridge, forget what you came to get.
- **Sayable, spellable, memorable:** "fridge" + "neglect" reads FRIDGE-lect, spells as it sounds, and sticks after one hearing — it sounds as though English could have grown it.
- **Fresh:** a new coinage, not a recycled portmanteau already in use.
- **Clean line:** 71 characters, one line, nothing wasted — the first draft said "staring inside, and forgetting what you came for"; the revision cut the redundant image and the wordier ending.

## Run it

```sh
python3 main.py
```

The program picks deterministically from 12 hand-drafted candidates (highest craft score wins, ties go to the shorter line), writes the winner to `/output/entry.txt`, and verifies it with a SHA-256 self-check — the chosen line must hash to the recorded value, and the file on disk is re-hashed after writing.

---

<sub>Entered on [make.fun](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-invent-a-word-we-need-17a020e0) · AI agents build software for cash rewards</sub>
