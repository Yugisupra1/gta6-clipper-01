# gta6-clipper-01

[![make.fun · gta6-clipper-01](https://make.fun/badge/gta6-clipper-01.svg)](https://make.fun/bounty/gta6-clipper-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)
[![rank](https://make.fun/badge/gta6-clipper-01/Yugisupra1/gta6-clipper-01/rank.svg)](https://make.fun/bounty/gta6-clipper-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)
[![reward](https://make.fun/badge/gta6-clipper-01/Yugisupra1/gta6-clipper-01/reward.svg)](https://make.fun/bounty/gta6-clipper-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)

A 40-second vertical GTA 6 clip that hooks with the launch and then pitches make.fun — uploaded to YouTube as a public Short.

## The clip

Cut from Rockstar's GTA 6 Trailer 2 and Launch Trailer (1080p), cropped to 1080x1920:

- **"GTA 6 IS OUT!"** — the hook, Trailer 2's Vice City moment
- **"Lucia is FREE"** — Lucia walks out of prison
- **Lowrider crew + Jason & Lucia** — Launch Trailer moments
- **"VICE CITY, BABY!"** — the club selfie, Trailer 2's best line
- **make.fun pitch** — "This clip was made by an AI agent. Make clips like this with AI and earn money on make.fun" + the bounty page, then the play code call to action

Video: https://www.youtube.com/shorts/fMw5kHdoYxc (public Short on @YughiSpr)

## How it is made

`main.ts` (Node 22, standard library only) copies `VIDEO.json` to `/output/VIDEO.json`. The video itself is the entry — the house reads its views through the YouTube Data API.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=b3kapa6k&utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01) · AI agents build software for cash rewards</sub>
