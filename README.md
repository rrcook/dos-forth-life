# dos-forth-life
A Conway's Life I wrote in 1985 for a IBM PC DOS forth called UNIFORTH

UNIFORTH is an original IBM PC DOS forth, I believe it was also available for Z-80 CP/M.

UNIFORTH either came with, or I found, code to manipulate the original IBM 20-bit memory model with segments and offsets, and code to change the IBM PC video modes, draw lines, etc.

My code (as best as I remember) has a 100 x 100 grid. Arrow keys move a dot around, s or S sets a dot, r or R resets a dot, B begins generations, B again pauses and lets you edit again. ESC stops the program.

For generations I used another part of the CGA video memory, built the next generation there then copied it back over into the "main" display, but in CGA mode you see both at the same time.

I used the UNIFORTH words to list the screens that have the forth code in it. 
forth-pc-graphics.txt has the code to switch CGA video modes.
forth-life.txt has my code for the life game.

Later I'll find a place to host UNIFORTH so someone can try it. In 2021 I've run it on Windows 98 and Windows XP.

I wrote the code in 1985 so my memory will be fuzzy as to how some of this works, until I have a chance to study it more.

