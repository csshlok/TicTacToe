# TicTacToe
A simple tic-tac-toe game made via python 

Hello, Shlok this side...
This is one of my old projects that I am sharing so that people can learn the basics and develop programs like this on their own 

<h>Talking about the the code</h>

There are some wining combinations that I have programmed but I prefer if you first run the code on your own and feel what it's like

// For the board //

print_board():
    x=1
    for i in board:
        end = ' | '
        if x%3 == 0:
            end = ' \n'
            if i != 1: end+='---------\n';
        char=' '
        if i in ('X','O'): char=i;
        x+=1
        print(char,end=end)
        
This is the type of nest I used for printing the tac board, it's a pretty simple design and not that hard...
I could've gone with a GUI based board but, you need to realise that this code was written when I was in 7th grade soo...
        
Both the main file and the tic tac file consist of the same code.. dunno why I made them I two differnt ones?
Well that's pretty much it.. I'll try to keep uploading my old projects as they are a bunch plus uploading new and better projects in Js alongside...
