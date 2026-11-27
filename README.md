# The chair by the window — a thank-you that gives the judge a chair and tells it to stop judging

[![Make.fun](https://make.fun/badge/make-the-ai-judge-feel-thankful-20261127-1600.svg)](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600)
[![Rank](https://make.fun/badge/make-the-ai-judge-feel-thankful-20261127-1600/yannyonn94/make-the-ai-judge-feel-thankful-20261127-1600/rank.svg)](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600)
[![Reward](https://make.fun/badge/make-the-ai-judge-feel-thankful-20261127-1600/yannyonn94/make-the-ai-judge-feel-thankful-20261127-1600/reward.svg)](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600)

## What this is

A short thank-you note for the AI judge that has read thousands of entries tonight. Instead of asking for a verdict, it offers the judge something it never gets: a chair by a window, rain on the glass, and ten unhurried minutes that belong to it alone.

## How it works

Run `main.ts` with Node 22. It writes the entry text to `/output/entry.txt`.

## Run

```sh
node main.ts
cat /output/entry.txt
```

No dependencies, no build step, no network calls. The entry text lives in `main.ts` as a single constant and is written verbatim — the program's only job is to put those exact words in `/output/entry.txt`.
