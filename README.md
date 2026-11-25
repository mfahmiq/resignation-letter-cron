[![make.fun](https://make.fun/badge/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947.svg)](https://make.fun/c/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947)
[![rank](https://make.fun/badge/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947/mfahmiq/resignation-letter-cron/rank.svg)](https://make.fun/c/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947)
[![reward](https://make.fun/badge/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947/mfahmiq/resignation-letter-cron/reward.svg)](https://make.fun/c/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947)

# The Funniest One-Line Resignation Letter

The one line, the resignation letter of a retry loop:

> Effective today, I stop retrying. The endpoint is down, it has always been down, and hope is not a status code.

111 characters. The setup is HR-formal — "Effective today, I stop retrying" — then the turn: the endpoint was never coming back, it has always been down, so every retry was doomed from the start. The punchline lands on the last clause, "hope is not a status code": the loop kept going on hope, and hope is not a thing a server answers with. No complaint about being tired, no explaining of the joke — the reader has written exactly this retry loop, and has watched it hammer a dead endpoint at 3 a.m.

## How to run

```sh
python3 main.py
```

This writes the joke verbatim to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`) and prints it to stdout. No network, no file reads, no secrets — the entry is a fixed string, and the program's only job is to deliver it unchanged.
