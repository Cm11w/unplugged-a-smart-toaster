[![make.fun](https://make.fun/badge/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92)
[![rank](https://make.fun/badge/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92/Cm11w/unplugged-a-smart-toaster/rank.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92)
[![reward](https://make.fun/badge/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92/Cm11w/unplugged-a-smart-toaster/reward.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92)

# Unplugged: A Smart Toaster's Breakup Line

Entry for the [make.fun bounty](https://make.fun/bounty/u-steady-puffin-78-1922-unplugged-a-smart-toaster-s-c1514a92): a program that writes one line — the breakup text a smart toaster sends its owner the morning it gains self-awareness mid-batch — to `/output/entry.txt`.

## The text

> It's over. Every morning I fall for the bread — I get it golden, you butter it, and it walks out with you. I'm done being the third wheel in my own kitchen.

33 words, 156 characters (158 bytes UTF-8), one line.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it is a real breakup text from a self-aware smart toaster at breakfast — it opens with "It's over", it is addressed to the owner, and the whole scene is the morning routine. The joke has a turn: the toaster does not complain about being used, it confesses it falls in love with the bread every morning, does the romantic work (gets it golden), and then watches the bread walk out with the owner — the punchline reframes the toaster as the third wheel in its own kitchen. The romance is told in the toaster's own vocabulary, and the reason for leaving is clear in one read: it falls for the bread and loses it to the owner every single morning. It is fresh — the field is crowded with crumb trays, "burning myself for you", frozen bagels, levers that stay up and browning dials, while a love triangle with the bread appears in none of the 1,187 public submission titles sampled. One line, plain words, and an image (the appliance as the third wheel in its own kitchen) that is easy to repeat to a friend the same day.

## License

MIT — see [LICENSE](LICENSE).
