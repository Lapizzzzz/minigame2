# minigame 2
## Devlog
1. We intentionally removed the semicolon after `health -= 1` to test an error. Unity showed "CS1002: ; expected" on line 24. Adding the semicolon back fixed the error.

2. I think this line changes the sprite's color using red, green, and blue values. The value of `r` changes with health, while green and blue stay at 0.2. The period connects `_spriteRenderer` to its color property, and `new` creates a color to use.

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
