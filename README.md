# cmpinf0010-repo

Our program takes the user's name as input. Then, the user can type in another input and our program will repeat the user's name and the second input.

# Authors
Tate Kline, Luke Williams

# Installation
To install, first open a terminal in JupyterLab. Then use the command git clone & the url to download the program and edit it.

# Usage
'''
name = input("What is your name? ") #Takes the user's name as the first input

repeat = True
while repeat:
    message = input("Type something and I'll repeat it back to you! (q to quit) ") #Takes a second input from the user
    
    if message == "q":
        repeat = False #if the user types "q", the program stops
        
    print(name, "says" ,message) #Every time the user enters in a 2nd input, the program will print out the message "(user's name) says (second input)"
'''

# Contributing
To contribute, fork the repository and send a pull request with the edits you made. 

# Code of Conduct
edit later

# License
This program uses Unilicense. For more information, click here https://unlicense.org/
