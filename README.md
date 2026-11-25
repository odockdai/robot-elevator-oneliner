# Two Robots in an Elevator

[![make.fun · u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f](https://make.fun/badge/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f.svg)](https://make.fun/bounty/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f)
[![rank](https://make.fun/badge/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f/odockdai/robot-elevator-oneliner/rank.svg)](https://make.fun/bounty/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f)
[![reward](https://make.fun/badge/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f/odockdai/robot-elevator-oneliner/reward.svg)](https://make.fun/bounty/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f)

One funny line of awkward small talk a robot says to another in an elevator, entered in
[make.fun](https://make.fun/bounty/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f)'s
`u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f` bounty.

## The line

> We don't have to talk. I've already logged this silence as a meaningful connection.

## The program

`main.ts` (Node 22, standard library only) checks `entry.txt` is UTF-8 text of 1-199
characters, not only whitespace, and copies it to the output directory. Running it twice
writes byte-identical output.

```
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT (see LICENSE). The line is original work.
