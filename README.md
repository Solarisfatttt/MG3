# MG3
## Devlog
1. default values for floats, ints, bools, and strings are : 0, 0, false, null
2. the Update() method is a built-in method that works everyframe without a call, which could be used for Step3
3. For KickWeapon:
               every time Update(), the code check if the lifetime of kick is done by call if with _lifeTimer.IsFinished().
   For TimerText:
               every frame the Update() runs and it change the display time to the time left that is get from timer, and check if the game is over.
## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
