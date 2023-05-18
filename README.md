Supported Commands Finished functions: core functionality, improved prompts, undo last modify, list of runnable functions, help, info, switch, quick-rank, pretty recover, pretty rank, (partially done but must control c out of it and type reset into the terminal to get it to go away) visualize

help //Explains how each function works and how to use it

undo //Once modify has been run once, game2 is filled with its previous contents before it was edited, I take this data and write it back into file_to_edit which reverts it to its previous state.

rank //This is pretty-rank! This was by far the hardest thing I (Evan) worked on while doing this assignment.

functions //This command gives a list of functions that the user can input. It can be called by typing: 'functions'.

check //Takes the inputted file and gives it to ./check which checks to see if the file is valid or not

modify //Uses the file inputted at the beginning of the program and reads its data, and stores it in game2 before it's modified. If there is a given file in the arguments, we read into that file and store it in game2 then pass it into modify.

recover //Given a path to a disk image of deleted Tetris quicksaves, recover will recover all valid and deleted save files from the path given.

switch //Switch takes the current file and argv1[1] arguments and prints the switching print statement, then it sets file_to_edit to be the save file that argv1[1] is. Once this is done successfully it will print: Switched! If the file being switched is invalid then an error will print after 'Switched!' prints.

info //Gives the current savefile name, score, and lines

visualize //Outputs the game board of the current save file. Must reset terminal and close program after running visualize.

exit // Exits out of the program; returns 0
