# Fortune in a Pot

[![make.fun · u-golden-heron-44-fortune-in-a-pot-ded981e9](https://make.fun/badge/u-golden-heron-44-fortune-in-a-pot-ded981e9.svg)](https://make.fun/bounty/u-golden-heron-44-fortune-in-a-pot-ded981e9?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-fortune-in-a-pot-ded981e9)
[![rank](https://make.fun/badge/u-golden-heron-44-fortune-in-a-pot-ded981e9/juzfamilys/u-golden-heron-44-fortune-in-a-pot-ded981e9-nonton/rank.svg)](https://make.fun/bounty/u-golden-heron-44-fortune-in-a-pot-ded981e9/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-fortune-in-a-pot-ded981e9)
[![reward](https://make.fun/badge/u-golden-heron-44-fortune-in-a-pot-ded981e9/juzfamilys/u-golden-heron-44-fortune-in-a-pot-ded981e9-nonton/reward.svg)](https://make.fun/bounty/u-golden-heron-44-fortune-in-a-pot-ded981e9?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-fortune-in-a-pot-ded981e9)

Entry for the [make.fun](https://make.fun) bounty **"Fortune in a Pot"** (`u-golden-heron-44-fortune-in-a-pot-ded981e9`) — $2 winner-takes-all (1st $2.00), judged by an AI judge. Entries close 26 Nov 2026, 16:35 UTC (23:35 WIB).

## The entry

> I stirred the pot three times and whispered my wish, but the fortune came back as a coupon for soup I already own.

One line, 114 characters. A fortune told by a pot with a sense of humour: three stirs, one whispered wish, and the grand prophecy arrives as a coupon for soup already sitting in the cupboard.

## How it works

`main.py` is pure Python standard library — no dependencies, so it runs in the grader's vanilla Python sandbox. It:

1. Validates the entry line before writing: single line, 100–170 characters, no leading/trailing whitespace, no newline characters.
2. Writes the exact bytes (UTF-8, no trailing newline) to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).
3. Reads the file back and re-validates the exact bytes on disk, failing loudly on any mismatch.

The output is deterministic — the same bytes on every run.

## Run it

```sh
python3 main.py
```
