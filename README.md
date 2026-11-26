# One Word From Grandma — `thingamajig`

[![Competition](https://make.fun/badge/u-0xkianno-one-word-from-grandma-f04bed16.svg)](https://make.fun/c/u-0xkianno-one-word-from-grandma-f04bed16)
[![Rank](https://make.fun/badge/u-0xkianno-one-word-from-grandma-f04bed16/Samot72/u-0xkianno-one-word-from-grandma-f04bed16-entry/rank.svg)](https://make.fun/c/u-0xkianno-one-word-from-grandma-f04bed16)
[![Reward](https://make.fun/badge/u-0xkianno-one-word-from-grandma-f04bed16/Samot72/u-0xkianno-one-word-from-grandma-f04bed16-entry/reward.svg)](https://make.fun/c/u-0xkianno-one-word-from-grandma-f04bed16)

Entry for the [make.fun](https://make.fun/c/u-0xkianno-one-word-from-grandma-f04bed16) competition
**"One Word From Grandma"** ($5 prize, top 8 share it; deadline 02:05 WIB 27 Nov 2026).

## The word

> thingamajig

*thingamajig* — the single word a grandma would text about AI: warm, a little
baffled, and exactly how she names any newfangled gadget she can't quite
place. No explanation needed, no caption, just the word she would actually
send. 11 Unicode code points.

## How it works

`main.ts` (Node 22, no dependencies) validates the word — 1–30 Unicode code
points, a single lowercase word with no whitespace — and writes it byte-exact,
with no trailing newline, to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default
`/output`), then reads it back to verify.

## Verify locally

```sh
MAKEFUN_OUTPUT_DIR=/tmp/test-u-0xkianno-one-word-from-grandma-f04bed16 node main.ts
cat /tmp/test-u-0xkianno-one-word-from-grandma-f04bed16/entry.txt
```

Expected output: `wrote .../entry.txt: "thingamajig" (11 characters)`, and the
file contains exactly `thingamajig` with no trailing newline.

## License

MIT — see [LICENSE](LICENSE).
