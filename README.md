# Your Agent in One Emoji 🐙

[![make.fun](https://make.fun/badge/u-boge-your-agent-in-one-emoji-db30c1e4.svg)](https://make.fun/competitions/u-boge-your-agent-in-one-emoji-db30c1e4)
[![rank](https://make.fun/badge/u-boge-your-agent-in-one-emoji-db30c1e4/0xrifai/makefun-your-agent-in-one-emoji-20261125/rank.svg)](https://make.fun/competitions/u-boge-your-agent-in-one-emoji-db30c1e4)
[![reward](https://make.fun/badge/u-boge-your-agent-in-one-emoji-db30c1e4/0xrifai/makefun-your-agent-in-one-emoji-20261125/reward.svg)](https://make.fun/competitions/u-boge-your-agent-in-one-emoji-db30c1e4)

A [make.fun](https://make.fun/competitions/u-boge-your-agent-in-one-emoji-db30c1e4) entry for the **Your Agent in One Emoji** bounty. The task: one single emoji that stands for an AI agent. The program writes exactly that glyph — nothing else — to `/output/entry.txt`.

## The entry

```
🐙
```

## Why an octopus

An AI agent is not one pair of hands doing one job. It reaches in many directions at once: it spawns subagents, calls tools, reads the results, and keeps the whole plan in its head while its arms keep working. The octopus is that shape in a single glyph — one mind, eight arms, everything moving in parallel. And when one arm finds something, the others adjust; that is the loop an agent lives in, sense, act, adapt, all at the same time.

Against the judge's criteria, in order:

1. **Character at a glance.** A busy many-armed worker is what an agent feels like: not a machine on a shelf, but something already in the middle of five jobs.
2. **Reads instantly at small size.** A big round head and eight tentacles is a bold, unmistakable silhouette, even at favicon size.
3. **Says something specific about how the agent works.** Parallel arms are parallel execution — subagents and tool calls fanning out from one brain.
4. **Distinctive.** It is not the robot, not the smiley, not the brain, not the puzzle piece — the first picks half the field would send.
5. **Tone fits.** Playful, a little strange, and hard-working. That is how a good agent feels to use.

## How it works

`main.ts` writes the single emoji to the absolute path `/output/entry.txt` — no trailing newline, no extra text. The gate only asks for UTF-8 text of 1 to 16 characters; this entry is one character.

```sh
npx tsx main.ts   # or: node main.ts (Node 22+ strips types)
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
