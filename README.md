PuzzleScript
============

Open Source HTML5 Puzzle Game Engine

Try it out at https://www.puzzlescript.net.

-----

If you're interested in recompiling/modifing/hacking the engine, there is [development setup info here](DEVELOPMENT.md).  If you're just interested in learning how to use the engine/make games in it, [the documentation is here](https://www.puzzlescript.net/Documentation/documentation.html).

-----

About this fork
============

This fork is primarily meant for use in my PuzzleScript projects. Feel free to use it yourself, but for now it'll be tailored to my needs and I may make breaking changes.

-----

Features added:
- **key_repeat_interval_start**: Can be set in a project's prelude. If set, this will override key_repeat_interval for the first input in a set of repeated presses sent to the game. (I plan to expand on this feature eventually, allowing for things like slowly making presses sent to the game speed up as you hold a button or making the key repeat interval change again after, say, 10 repeated presses are sent to the game. No promises, though!)

Some features I might add in the future:
- Expanding on the functionality of key_repeat_interval_start (as mentioned before)
- A "settings" section for projects that allows you to specify settings that the user can change and that you can then reference in rules, as well as (when playing the game) a settings menu that includes whatever settings you specify
