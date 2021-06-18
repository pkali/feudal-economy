# feudal-economy
Rework of old BASIC game for Atari 8-bit

I got so hooked on an old game called "Feudal Economy" that I used to play with my friends when I was a kid. It is apparently a clone of "Hammurabi", but moved to 1400's Italy.

Holy crap, when I started to look at the code I crashed, spaghetti code turbo power, but it's not the programmer's fault, it's hard to do otherwise in basic...

Anyway, I rewrote the code to tbxl_parser of the great dmsc (https://github.com/dmsc/tbxl-parser) and with a benedictine effort I unspaghetti'ed code and deobfuscated most of the variables and procedures.

Unfortunately I didn't do without adding a bunch of bugs.

The current version is worse than the original, because I threw away most of the error handling. But in most cases it is possible to continue by typing CONT 2 times.

Second step - fixing the errors, getting the "quality" of the original, but not orthodoxly :]

Third step - rewriting to madpascal or something, this is already a task close to trivial from the current code form.

Step four - game server and support via fujinet.

In the meantime I am looking for the original game in English language, so far found only Polish and Czech versions.

## How to run
Run `feudal_tb_pl.bas` from Turbo Basic XL

## How to compile
use tbxl tool to compile `feudal_tb_pl.txt`:
`tbxl-parser/build/basicParser feudal_tb_pl.txt`

