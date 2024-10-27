Trello board for project - https://trello.com/b/qKMVaH7C/sgd240-artefact


There are two methods, one complete one incomplete.

Random Walk Generator

Map-RandomWalk

Blueprint- PrimaryPathGenerator

Select the PrimaryPathGenerator Actor in the level to view the exposed settings. Here we can change the number and type of rooms we are spawning. 
There can be issues with spawning some room types 7 and 8 at higher room counts. Run in viewport will spawn a pawn and allow you to explore the dungeon. 
Run as simulation will allow you to watch the dungeon generate room by room.

Wave Function Collapse Generator

Map- WaveFunctionCollapse

Blueprint-BP_MapGenerator

I couldn't get this one to work correctly. It will collapse the first cell, but nothing further. 
Select the BP_Generator Actor in the level to view the exposed settings. Here we can change the grid size. 
To view, open the BP_MapGenerator blueprint. Previous version was WFC_Generato
