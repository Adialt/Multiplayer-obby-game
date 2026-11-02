Task 1
The game setup is in and Obby on Roblox, an obstacle course. This game is played in Roblox, kids and adults play the game, it is a fun game because it is challenging and in Roblox you can change your avatar to have a variety of different looks. What makes this game unique that you are trying to go through these obstacle courses without dying, you want to win. 
Task 2
1.	As a player I can join an Obby game on Roblox so that I can play.
2.	As a player I can change my avatar so that I can have different hair and different clothes.
3.	As a player I can see other players in the Obby game so I can chat with them.
4.	As a player I can send and receive chat messages so that I can communicate with other players.
5.	As a player I can see other players moves so that I can have an advantage.
6.	As a player I have to avoid falling off the Obby so that I can stay alive.
7.	As a player I can be removed from the game if I fall off the obstacle course so then I am dead. 
8.	As a player I can rejoin the game if kicked out so that I can continue playing.
Task 3
The game will include obstacles, it is an Obby a game built around obstacles. The game will have walls, different types of hazards that block or slow down players but that is the purpose of the game to challenge the player. The obstacles in the game make the player wanna keep trying if they lose it becomes addictive. 
Task 4
Must : As a player I can join an Obby game on Roblox so that I can play.
Must : As a player I can change my avatar so that I can have different hair and different clothes.
Must : As a player I am able to see other players in the Obby game so I can chat with them.
Should : As a player I can send and receive chat messages so that I can communicate with other players.
Should : As a player I can see other players moves so that I can have an advantage.
Should : As a player I have to avoid falling off the Obby so that I can stay alive.
Should : As a player I can be removed from the game if I fall off the obstacle course so then I am dead. 
Could : As a player I can rejoin the game if kicked out so that I can continue playing.

Task 5
1 - The server must allow the player to join the Obby or the existing room. 
2 - The server must reject empty nicknames or nicknames that are already used by another player.
3 - The server must display a list of the connected players in the Obby war room.
4 - The server must receive movements input an update the player's position.
5 - The server must also update connected players positions as well in the same room.
6- The server must accept chat messages from connected players and deliver them to those players in the same room.
7- The server must detect that a player has disconnected unexpectedly and remove that player once they detect the player is no longer connected.
 8 - The server must maintain each player's score and send updated scores to the other players in the room.
9- The server must display the scores of each player and update the scores on the screen. 
10- The server must process concurrent actions simultaneously for movements, disconnection events so that it does not corrupt the shared game data.
11 - The server must provide a purpose for the game with prerequisites and the startup instructions. 

Task 6 
Responsiveness: Under normal conditions with up to 10 players, at least 95% of movement updates should reach the other players in the same room within 250 milliseconds.
Reliability: When a player disconnects unexpectedly, the server must remove the player from the active room within five seconds. The disconnection should not effect the remaining players from continuing their game.
Thread safety: Shared actions should not create duplicate scores, negative scores, duplicate player entries, or corrupted room data. 
Ease of Running: Someone else should be ablep to build this project, Obby and be able to star it with the steps that I’ve documented. Setup instructions must not require a paid service or database, should be free.

Task 7
1.	A player can enter a valid room code and join the game successfully.

2.	A player can select different available hairstyles and clothing options, and the changes appear on their avatar.

3.	All All players in the same room can see the other connected players in the game.
4.	All players in the same room can see the other connected players in the game.

5.	A player can send a message, and all players in the same room receive and see it.

6.	When a player moves, the other players see the movement within 250 milliseconds under normal conditions.

7.	Players can move around obstacles, and the game detects when they fall off the course.

8.	When a player falls off the obstacle course, the server registers the player as eliminated and updates the game state.

9.	A player who leaves or disconnects can rejoin the room using a valid room code and continue playing.

Task 8
Movement lag: Sending too many movement updates may cause delays, so I will limit update frequency and test the game with multiple players.
Server crashes or disconnections: Players may disconnect unexpectedly, so I will implement disconnect detection and remove disconnected players from the room.
Difficulty implementing obstacle: Collision detection and falling may take longer than expected, so I will start with simple obstacles and gradually add more challenging ones.
Chat misuse: Players may send inappropriate or excessive messages, so I will implement basic message validation and limits.
Chat misuse: Players may send inappropriate or excessive messages, so I 
Assumptions
1.	The game will use Java for the server and web technologies for the client.
2.	The project will run locally without requiring paid services or a database.
3.	Avatar customization will use a limited selection of available hairstyles and clothing options.
4.	The server will manage player movement, room information, chat, and scores.
5.	The game will be a browser-based multiplayer Obby inspired by Roblox.
6.	Each room will support up to 10 players at a time.


Out of scope
1.	User accounts, passwords, or player profiles.
2.	Integration with the official Roblox platform.
3.	Advanced avatar customization or importing Roblox avatars.
4.	Matchmaking or automatic player pairing.
5.	A database for saving player information or scores.
6.	Cloud hosting or paid deployment services.
7.	Voice chat or private messaging.
8.	In-game purchases, Robux, or advertisements.
9.	Advanced graphics, animations, or realistic physics.
