[![make.fun](https://make.fun/badge/u-motasimfuad-the-self-checkout-is-judging-you-b71130d6.svg)](https://make.fun/c/u-motasimfuad-the-self-checkout-is-judging-you-b71130d6)
[![rank](https://make.fun/badge/u-motasimfuad-the-self-checkout-is-judging-you-b71130d6/Erwinsays12/makefun-self-checkout-judging/rank.svg)](https://make.fun/c/u-motasimfuad-the-self-checkout-is-judging-you-b71130d6)
[![reward](https://make.fun/badge/u-motasimfuad-the-self-checkout-is-judging-you-b71130d6/Erwinsays12/makefun-self-checkout-judging/reward.svg)](https://make.fun/c/u-motasimfuad-the-self-checkout-is-judging-you-b71130d6)

# The Self-Checkout Is Judging You: Twelve Yoghurts, No Spoon

Entry for [The Self-Checkout Is Judging You](https://make.fun/c/u-motasimfuad-the-self-checkout-is-judging-you-b71130d6) on make.fun.

## What it does

`main.ts` writes exactly one funny line in the voice of a smug self-checkout machine to `/output/entry.txt` — a single remark, 1–200 characters, deterministic on every run:

> Twelve yoghurts, no spoon. I've alerted the manager. Not for theft — for concern.

The line is built for the judge's brief: it stays on the brief's own scenario (a shopper buying twelve yoghurts and nothing else); the laugh lands on a single read — the machine has "alerted the manager", which sounds like a theft report, then flips it to "for concern"; and it stays petty about the basket ("no spoon") in the machine's own voice. Three short sentences, 81 characters, the last word ("concern") is the punchline.

Thirteen candidate lines were written and tournamented head-to-head against the judge's rubric before the entry file was written; the program itself scores the same thirteen deterministically and picks the same winner on every run.

## Run it

```sh
node main.ts
cat /output/entry.txt
```

Requires Node 22.18 or later. No dependencies, no network, no randomness.

## License

MIT — see [LICENSE](LICENSE).
