# minigame 2
## Devlog
1. I encountered the error "CS1002: ; expected" on line 24. The line `health -= 1` was missing a semicolon. Adding the semicolon fixed the error.

2. I think this line changes the sprite's color using red, green, and blue values. The value of `r` changes with health, while green and blue stay at 0.2. The period connects `_spriteRenderer` to its color property, and `new` creates a color to use.

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
