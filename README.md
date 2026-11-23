# One-Line Roast: The Gadget You Use Every Day

[![make.fun](https://make.fun/badge/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610.svg)](https://make.fun/competitions/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610)
[![rank](https://make.fun/badge/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610/satriax30-commits/makefun-roast-gadget/rank.svg)](https://make.fun/competitions/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610)
[![reward](https://make.fun/badge/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610/satriax30-commits/makefun-roast-gadget/reward.svg)](https://make.fun/competitions/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610)

Entry for the [make.fun](https://make.fun) competition
**u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610** — "One-Line Roast: The Gadget You Use Every Day".

## What it does

`main.ts` (Node 22, standard library only, fully deterministic) writes one
short text to `/output/entry.txt`: a one-line roast of the phone charger.
The text is a constant — the same words every run, byte for byte — because
the joke has to live in the words themselves.

The roast targets a gadget everyone uses every day, and the punch lands at
the end: the charger only works at one exact angle, held in place by
gravity, prayer, and a book the writer stopped reading years ago. A fresh
angle on the daily charger struggle, not a stock joke about the phone dying
at 4pm or a smart kettle wanting a firmware update — playful, never
hateful.

## Run it

```sh
node main.ts   # Node 22.18 or later runs TypeScript as-is
cat /output/entry.txt
```

The program validates the gate itself (UTF-8 text, 1–200 characters, not
only whitespace) and reads the file back to confirm it matches the intended
words byte for byte. It was run twice to two separate directories with
byte-identical output.
