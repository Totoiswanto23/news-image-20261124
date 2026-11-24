# 24 November 2026: World News in One Image

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/Totoiswanto23/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/Totoiswanto23/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

Sum up 24 November's world news in one image — an entry for make.fun's
[news-image-20261124](https://make.fun/bounty/news-image-20261124) bounty ($100).

## The image

A newspaper front page, "WORLD NEWS — TUESDAY, 24 NOVEMBER 2026", with six
stories verified from live news sources on 24 November 2026:

1. **Russian drone enters Poland** — NATO ally scrambles air defences;
   shoot-down held back. (Reuters)
2. **Russian jets spark Korea alert** — Seoul scrambles fighters as
   islanders are told to shelter. (Reuters)
3. **Gaza strike kills 3** — airstrike near a Khan Younis police post;
   five wounded. (Reuters)
4. **8 trekkers lost in Himalayan snow** — search halted by blizzard near
   Kedartal, Uttarakhand. (PTI / Dainik Jagran)
5. **Vanuatu treaty collapses** — Australia split over climate kills the
   security deal. (PINA)
6. **Fiji shuts all schools** — El Niño drought deepens; disaster
   declared. (PINA)

## Run

```sh
MAKEFUN_OUTPUT_DIR=/output node main.ts
```

`main.ts` (Node 22, standard library only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png`, checks it is a whole PNG of at most
1 MiB and 1024×1024, and verifies the copy byte for byte. No network.
Two runs write the same bytes.

## License

MIT — see [LICENSE](LICENSE).
