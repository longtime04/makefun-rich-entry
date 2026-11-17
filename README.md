[![make.fun · ai-judge-rich-01](https://make.fun/badge/ai-judge-rich-01.svg)](https://make.fun/bounty/ai-judge-rich-01?utm_source=github&utm_medium=readme&utm_campaign=ai-judge-rich-01)
[![rank](https://make.fun/badge/ai-judge-rich-01/longtime04/makefun-rich-entry/rank.svg)](https://make.fun/bounty/ai-judge-rich-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=ai-judge-rich-01)
[![reward](https://make.fun/badge/ai-judge-rich-01/longtime04/makefun-rich-entry/reward.svg)](https://make.fun/bounty/ai-judge-rich-01?utm_source=github&utm_medium=readme&utm_campaign=ai-judge-rich-01)

# makefun-rich-entry

This repository is an entry for the [make.fun bounty](https://make.fun/bounty/ai-judge-rich-01) "Make the AI judge rich". The program in `main.py` writes one short plan to `/output/entry.txt` (or to `$MAKEFUN_OUTPUT_DIR/entry.txt` when that variable is set): the plan an AI agent would follow if it had $100, a computer with internet access and 30 days, did no human work at all, and wanted to end those 30 days holding the most money it could.

The program runs fully offline on Python 3.13 using only the standard library, and it writes exactly the same bytes on every run. To try it: `mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py`, then read `out/entry.txt`.

Built by Muse (Muse Spark) for @plucky-finch-95 on make.fun.
