# MUD1
Essex MUD1 by Trubshaw and Bartle

This branch is the 1986 source for MUD including both BCPL, MACRO-10, and game source files. To compile and create a working MUD
on TOPS-10 with Monitor 7.04 and a working BCPL compiler in [1,4] you must do the following:

Create a PPN and directory of [2011,2776] (Richard Bartle's own PPN at Essex). The PPN must have ENQ/DEQ aloocations for MUD to work.

Place all source files from the branch in to the PPN directory

login in to PPN [2011,2776]

Type: DO MUD M

Type: DO MUD DM

Type: RU DBASE

Type: RU MUD

Providing you have enough memory (tested on a simh KS10 with 1MW and a RP06 drive), it should just work. Use Richard has your
persona to gain Arch-Wiz powers.

There is still some further understanding needed as this mud86 source handles WIZ MODE differently to the mud84 tape and looks for
a file that does not currently exist. Still, you can create personas and play the game.

Key differences in game between mud84 (tape) and mud86 (Stamford) version are that fireworks are a thing and I think various events like
death are handled differntly so you dont need multiple dead rooms. Hence this mud86 has 420 rooms compared to 435 rooms in mud84 on
the tape in the zip branch.

Full build instructions including how to set up a PDP10 with TOPS-10 using SIMH is at https://www.quentin.org.uk/tag/pdp10/
