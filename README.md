# CherryBlossoms

For the final project, I will be creating a procedurally generated cherry blossoms. The inspiration is taken from spring time on Bryn Mawr College campus:


<img width="389" alt="Screen Shot 2021-05-10 at 10 39 16 PM" src="https://user-images.githubusercontent.com/79232961/117749976-a0976880-b1e0-11eb-9579-1350bda2700b.png">



When using this program in a windows computer, input the following command inside the terminal after entering the project directory: g++ branch.cpp -o branch -lopengl32 -lglew32 -lfreeglut -lglu32 -pthread -fconcepts
This command is also present in the "Build CMD.txt" file.

## Commands:
PRESS ESC - quit

PRESS x to pan camera in phi

PRESS X to pan camera out phi

PRESS c to pan camera in theta

PRESS C to pan camera out theta

PRESS z to zoom in

PRESS Z to zoom out

PRESS a,A,s,S,d,D to move location of camera focus

PRESS , to turn on/off point of camera focus

PRESS `[` or `]` to increase/decrease autozoom 

## Demo



There are two demo videos. The demo video with the red tree is there to demonstrate the camera commands. The green tree is a demonstration of the program after making the program procedurally generate the tree while the red tree is when the program did not have the feature to procedurally generate the tree adn so, the following commands were used to generate the tree manually: Space to play/pause and . to generate new branches. To make the program procedurally generate the tree, the use of timercpp.h (open source) was used which causes the program to lag a lot. Because of this, using the camera commands with the program that procedurally generates the tree is difficult. 


https://user-images.githubusercontent.com/79232961/119075700-3be9c400-b9bf-11eb-90b8-312b3a30f0d9.mov


https://user-images.githubusercontent.com/79232961/119075713-40ae7800-b9bf-11eb-8468-2e0596a1ca00.mp4






