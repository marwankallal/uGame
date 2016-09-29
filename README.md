# uGame
Game engine from scratch 

Compiling
=========
This one's easy: `make`

You'll then find the executable in `bin/ugame` and can run it from there.


Running
=======
Also easy: `./ugame [.ug file]`


uGame Files
===========
uGame runs on `.ug` files. The file structure and usage can be found in 
`doc/UG.md`. Common filetypes for game assets will also be supported.


"From Scratch"
==============
Not really. You can't beat OpenGL and SDL for graphics and managing 
windows/input, and this project isn't about writing drivers. However, 
it is about writing a game engine from the lowest possible level. 
For that reason, I will try to limit the use of external libraries to the above.

If at some point this project reaches a stage where the engine runs well,
I may consider writing the rendering myself (for a small subset of devices).
