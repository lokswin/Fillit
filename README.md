# Fillit
    Fillit
    Program to tile minimum possible square with given tetraminos. 
    Tetriminos is placed on their most upper-left position.

SYNOPSIS

    #include "libft\libft.h"

    ./fillit tetraminos_source_file

DESCRIPTION

    INPUT
    	File with [1 - 26] tetraminos;
	
    OUTPUT
    	Smallest square filled with given shapes.

RETURN VALUES

    Fillit return error when file not valid and filled square otherwise.

EXAMPLES
    The following is how to use fillit.

    File "tetraminos" contain:
       "....
        .#..
        ###.
        ....

        ....
        .##.
        .##.
        ....

        ....
        ....
        ###.
        ..#."

    ./fillit tetraminos
    CCC.
    BBC.
    BBA.
    .AAA
