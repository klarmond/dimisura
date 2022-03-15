A procedurally generated 2D platforming game developed using the GODOT game engine. The procedural generation algorithm is used to multiply and manipulate sets of black walls. This manipulation allows for the walls to continuously spawn upwards and shift along the x axis, allowing for random structures to be made that the player has to climb to gain points. Climbing is done by jumping from wall to wall. A player cannot jump up the same wall twice in a row, so for every jump they much jump off the opposite wall before jumping on the other. In air, the player has mid-air jumps that they can utilize, this number can be increased temporarily to as much as 5 if the user collects powerups in the game (still being properly implemented). The farther up the player is able to climb to, the higher their score will be. If the user falls down a certain distance (if their position goes down by 300 y units lower than their highest distance) the user will lose the game and be prompted to return to the home screen where they will have the chance to start a new game or look at the controls. 
![start_screen](https://i.gyazo.com/b88def354fa7a42e9abe50df2ff8dad0.jpg)



![controls](https://i.gyazo.com/2b1b6e4ac132d542c2d3b7bb21dc48b3.png)


![player_screen](https://i.gyazo.com/ef2bb60993390d44521b6ed0890f4787.png)
