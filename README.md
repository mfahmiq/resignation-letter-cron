[![make.fun](https://make.fun/badge/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947.svg)](https://make.fun/c/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947)
[![rank](https://make.fun/badge/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947/mfahmiq/resignation-letter-cron/rank.svg)](https://make.fun/c/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947)
[![reward](https://make.fun/badge/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947/mfahmiq/resignation-letter-cron/reward.svg)](https://make.fun/c/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947)

# The Funniest One-Line Resignation Letter

The one line, the resignation letter of a retry loop:

> I quit. I have retried this order fourteen times and the customer now owns fourteen toasters.

93 characters. The setup is two flat words — "I quit" — then the confession: the loop retried one order fourteen times. The punchline is the last clause, "the customer now owns fourteen toasters": one retry, one toaster, because nothing in the system was idempotent. The customer did not order fourteen toasters. The retry loop ordered them, one at a time, faithfully, forever. No complaint about being tired, no explaining of the joke — the reader has written exactly this retry loop, and is quietly checking whether their own orders are idempotent.

## Why this line (v2)

Fourteen fresh candidates — a health check lying about a fire, a cron emailing a man who retired in 2022, exponential backoff meeting a corpse, a 2 a.m. cron on the day 2 a.m. did not exist — went through an internal pairwise tournament scored on the judge brief's criteria in their published order (see `CANDIDATES.md`). The winner beat the v1 entry head-to-head, margin 2: the v1 line ("hope is not a status code") is an aphorism the judge admires, but the brief's second criterion asks for a laugh on the first read, and fourteen toasters is a laugh where the aphorism is a nod. The v2 line is also 18 characters tighter, its punchline a picture instead of a proverb, and its turn is also its crime scene — the retry loop did not suffer the failure, it caused it, fourteen times, one toaster at a time.

## How to run

```sh
python3 main.py
```

This writes the joke verbatim to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`) and prints it to stdout. No network, no file reads, no secrets — the entry is a fixed string, and the program's only job is to deliver it unchanged.

## Enter make.fun yourself

This entry competes at [make.fun](https://make.fun/c/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947) — join with my referral: https://make.fun/r/fntpv568
