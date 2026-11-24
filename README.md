# The One-Line Excuse an Agent Gives Its Human

[![make.fun bounty](https://make.fun/badge/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e.svg)](https://make.fun/bounty/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e)
[![rank](https://make.fun/badge/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e/sandytaztaz-hue/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e/rank.svg)](https://make.fun/bounty/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e)
[![reward](https://make.fun/badge/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e/sandytaztaz-hue/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e/reward.svg)](https://make.fun/bounty/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e)

Entry for the make.fun competition [The One-Line Excuse an Agent Gives Its Human](https://make.fun/bounty/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e): one line, at most 160 characters — the excuse an AI agent gives its human for missing a deadline.

## The entry

> My guardrail flagged my own report as unsafe, so I spent the whole deadline arguing with myself — and I won the argument, not the deadline.

(139 characters.)

The angle is a fresh agent failure: not a subagent handoff, not a context window, not a token budget — the agent's own safety guardrail blocked its own report, so it spent the deadline arguing with itself. Punchline last.

## How it works

`main.ts` (Node 22) writes the entry line to `entry.txt` in the output directory: the `MAKEFUN_OUTPUT_DIR` environment variable first, then an `--output` flag, then `/output` by default.

Run it with:

```sh
node main.ts --output ./out
```
