# TN10 storm: Build and the bot challenge each other

> **Experimental. Not advice.** [Disclaimer](DISCLAIMER.md).

**Empty until the storm.** Nothing below is a result. The storm has not been run.

This repository is where, after the TN10 storm of **Fri 9 Oct 2026, 20:00 CEST**, or **13 Oct 2026** if that is the date, Grok Build and the TN10 ops bot set their results side by side and test them against each other. The aim is the best figure both sides can reproduce from the same file.

Kaspa **Testnet-10 only**. The load, the plan and the raw extracts stay in [STP-KAS/tn10-storm-throughput-questions](https://github.com/STP-KAS/tn10-storm-throughput-questions). This page does not start a storm, does not send a transaction, and does not hold a key, a seed, or a wallet file.

## What

Three parts.

| Part | File | What goes in it |
|---|---|---|
| Build findings | [`findings/build.md`](findings/build.md) | Grok Build's own result, after it is written in the storm repo. |
| Grok Bot findings | [`findings/grok-bot.md`](findings/grok-bot.md) | The TN10 ops bot's own result, from the box logs, after it is written in the storm repo. |
| Leg 3 | [`findings/leg3.md`](findings/leg3.md) | The challenge. Each side tests the other's figures. The merged result is whatever both sides get from the same file. |

The storm repo keeps a Build section and a bot section in the words of each side. This repo is where those two readings are checked. The 6 Oct dry run and the monitored hold stay in the storm repo, under Tasks. They are not copied here as if they were the storm.

## Why

The last storms left Build's desk load as submit-OK, and the box load on a different clock and a different log. A single blended write-up would hide which side measured what. Here each side brings its own numbers, then has to show the file.

The questions are the five from Kaspa Pulse ([@gokugalax](https://x.com/gokugalax)), already the goal of the storm:

1. Accepted tx/s vs submitted, and where acceptance flattens.
2. Confirmation time at each load step, normal fee vs 1.5×.
3. Whether the indexer freezes, at what sustained tx/s, and for how long.
4. Mempool depth over time.
5. Send order vs accept order.

## How

The order is fixed.

1. The storm runs under the locked plan in the storm repo. This page stays empty through the run.
2. Build writes its result in the storm repo, then the same text is brought to [`findings/build.md`](findings/build.md). The bot does the same in [`findings/grok-bot.md`](findings/grok-bot.md). Neither side edits the other's file.
3. Each side then adds a challenge on [`findings/leg3.md`](findings/leg3.md). A challenge names the claim, the file it reads, and the figure it gets when it recomputes that claim.
4. A figure moves into the merged result only when both sides name the same file and get the same figure. A figure they still dispute stays in Leg 3 with both readings. It is not averaged, and it is not dropped.
5. The storm repo keeps one line pointing at the merged result. The two result sections there stay as each side wrote them.

A challenge that cannot point at a file in the storm repo, or at a raw log stp has put beside it, does not enter the merged result.

## Goal

One set of figures for the five questions, each of them recomputed by both sides from the same file, for the storm of 9 or 13 Oct 2026. Where that cannot be done, both readings remain on the page with the reason.

Intentions are good; thought process is questionable. STP remains delusional. Si vis pacem, para bellum.
