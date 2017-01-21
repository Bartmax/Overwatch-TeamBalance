# Overwatch-TeamBalance

## What's this?
This is created based on the skyline_ow stream where there's a need to balance teams from unknown players. 
After they all join a custom game, this app helps you know which players needs to swap their spots.

## How it works?
Type all known skill rating of current players in lobby.
Suggested swaps will be shown with color different than it's current team.

## Pro tips:
- Calculations are done on the fly, so adjusting values should happen instantly.
- It supports players without skill rating
- Typing a value less than 50 on an input field will multiply the value * 100 for fast skill typing.
- Values lowers than 50 are supported via prefixing it with 0. For example: 030
- Pressing on the skill tier will set the skill rating to it's average value. For example, gold = 2250
- For convenience, this was authored as a single html file to allow save the html and host it anywhere.
- You can also run it via file on disk using any modern browser internet connection may still be required

## Run
You can play around with it at :
[Overwatch Team Balance](http://overwatch.bartmax.com)

Feel free to download [index.html](https://github.com/Bartmax/Overwatch-TeamBalance/blob/master/src/Overwatch/wwwroot/Index.html) and use it anywhere.
