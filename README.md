# SolitaireSim

Important note - running this project
The solitaire crack requires that the game is run from a directory with 24 or less characters. For example, a directory like "D:\SolitaireTest" works great, but something like "D:\SuperLongPath12356789ThisIsTooLongabcdefghijk" wont work.

Download and place all the files in the same directory. Then open a command prompt with administrator access. Run `python gui.py` to start the gui along with an instance of the solitaire game. From there, either click the solve game button or the deal new hand button to interact with the game.

Files and their description:

autosolver.cpp - c++ code that implements the full automation for solving solitaire by simulating mouse clicks. Compile by running `cl /EHsc autosolver.cpp user32.lib kernel32.lib`

autosolver.exe - compiled executable version of the autosolver.cpp code

cards.dll - needed for solitaire to run

cracked_solitaire.exe - the cracked version of the solitaire executable

gui.py - implements our graphical user interface for this project

