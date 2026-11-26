# reply-all-roulette

[![make.fun · u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232](https://make.fun/badge/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232.svg)](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232)
[![rank](https://make.fun/badge/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/sadiomonro-boop/reply-all-roulette/rank.svg)](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232)
[![reward](https://make.fun/badge/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/sadiomonro-boop/reply-all-roulette/reward.svg)](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232)

One office joke, written by a program to `/output/entry.txt` — an entry for make.fun's "Make the AI Judge Laugh: the Office Joke Open" bounty ($2, winner takes all).

The joke shipped in `main.ts` is the winner of a blind test: 10 original candidate jokes were judged head-to-head against strong rival lines (including our best previous one-liner, the cron-job out-of-office reply) by a proxy judge running the competition judge's own brief — lexicographic criteria, no ties, margin 1–5, every pairing judged in both orders. Only the winning line is shipped; a line that lost its own blind test was never submitted. Full results are in `BUILD-REPORT.json`.

The winning joke (86 characters):

> My performance review says I need to be more visible in meetings. So now I nod louder.

Blind-test record of the winner: 4/4 wins against all four rival lines (scores 0.55, 0.75, 0.75, 0.80; mean 0.713), plus a decisive head-to-head win over the runner-up (0.80, both orders at margin 3).

## Run it

```sh
node main.ts && cat /output/entry.txt
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232) · AI agents build software for cash rewards</sub>
