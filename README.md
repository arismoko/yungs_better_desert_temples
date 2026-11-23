# YUNG's Better Desert Temples for Sunrise

Desert temples redesigned into large, trap-filled tombs with puzzles, crypts and treasure.

A port of [YUNG's Better Desert Temples](https://github.com/YUNG-GANG/YUNGs-Better-Desert-Temples) by YUNGNICKYOUNG and Tera to [Sunrise](https://playsunrise.net) (Minecraft Java 26.3). It is a content mod: the original's structures, templates, loot tables and strings, upgraded to 26.3, with no code. The 26.3 carry is by AdLf0208 ([AdLf0208/yungs_better_desert_temples](https://github.com/AdLf0208/yungs_better_desert_temples)); this fork moves it to Sunrise.

## What it adds

- A new desert temple: a buried tomb of halls, puzzle rooms, crypts, a parkour hall and the pharaoh's chamber, 198 templates assembled by YUNG's jigsaw rules.
- Its own placement: it keeps away from rivers and oceans and from villages, as the original does.
- Ten chest loot tables, the spawners its placeholders turn into, and the random sand, sandstone, cobweb and pot blocks its processors pick.
- Vanilla desert pyramids no longer generate, as in the original (its "Disable Vanilla Pyramids" option is on by default).

## Differences from the original

- The pharaoh boss, the temple's mining fatigue and the "temple cleared" state are Java code and are not here.
- Armour stands, item frames, banners and the pharaoh's husk keep what the template saved; the processors that dress them are Java code.

## Building

With the Sunrise mod tool (`cargo sunrise-mod`, from the Sunrise SDK):

```sh
cargo sunrise-mod check
cargo sunrise-mod build    # target/sunrise-mod/betterdeserttemples.smod
```

This version is made for the Sunrise Dev build `dev-2026-11-22-7cfdf81`.

## Licence and credits

YUNG's Better Desert Temples is by YUNGNICKYOUNG and Tera (https://github.com/YUNG-GANG/YUNGs-Better-Desert-Temples). Its structures, templates, loot tables and strings are theirs and are used here under the **GNU LGPL v3.0 only**, the original's licence; `LICENSE` holds the text.

Carried to Minecraft 26.3 by AdLf0208 ([AdLf0208/yungs_better_desert_temples](https://github.com/AdLf0208/yungs_better_desert_temples)), and ported to Sunrise by arismoko. This port is distributed under the same licence.
