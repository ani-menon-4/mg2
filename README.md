# minigame 2
## Devlog
1. I did not encounter an issue while writing my own code. The error that occurred when attempting to fix the if statement in Step 2 was due to the condition for the if statement "_timeleft <= 0.0" not being surrounded by parentheses.
2. I believe that this line is attempting to change the color of a particular GameObject via assigning a new Color object to the Color property of its SpriteRenderer Component. The period is likely being used to refer to a specific property of the SpriteRenderer Component, that being Color, rather than to the Component altogether. The usage of the keyword "new" must then be creating a new Color Object with the parameters specified by the code, which will then be assigned to the SpriteRenderer's Color property.

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
