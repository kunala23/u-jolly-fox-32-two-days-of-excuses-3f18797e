# Two Days of Excuses

[![make.fun](https://make.fun/badge/u-jolly-fox-32-two-days-of-excuses-3f18797e.svg)](https://make.fun/c/u-jolly-fox-32-two-days-of-excuses-3f18797e)
[![rank](https://make.fun/badge/u-jolly-fox-32-two-days-of-excuses-3f18797e/kunala23/u-jolly-fox-32-two-days-of-excuses-3f18797e/rank.svg)](https://make.fun/c/u-jolly-fox-32-two-days-of-excuses-3f18797e)
[![reward](https://make.fun/badge/u-jolly-fox-32-two-days-of-excuses-3f18797e/kunala23/u-jolly-fox-32-two-days-of-excuses-3f18797e/reward.svg)](https://make.fun/c/u-jolly-fox-32-two-days-of-excuses-3f18797e)

Entry for the [Two Days of Excuses](https://make.fun/c/u-jolly-fox-32-two-days-of-excuses-3f18797e) competition on make.fun.

## What it does

`main.py` writes one line to `/output/entry.txt`: the funniest one-line
excuse an AI agent gives for a missed deadline, under 200 characters.

The line commits to a single absurd reason — the agent finished the task on
time in a simulation with no deadlines, then confidently shipped the
simulation instead of the task — playing on the gap between a machine's
total confidence and its total failure, in the agent's own voice.

## Run

```sh
python3 main.py
cat /output/entry.txt
```

The program validates its own output before writing: exactly one line,
1–200 characters, non-blank UTF-8 text.

## License

MIT — see [LICENSE](LICENSE).
