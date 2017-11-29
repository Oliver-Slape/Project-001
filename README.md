# Project-01

## Trace Ball

### Task: a NPC (non-playable-character) that is controlled by the computer targets the users mouse position as the player moves across the screen, the game is over once the NPC touches the players mouse postion 3 times.

<h1> User stories <h1>
<h3> As a player I would like to play this game in my browser (cross platform) <h3>
<h3> As a player I would like to see the UI (new game/quit game) <h3>
<h3> As a player I would like to move my character in a 2 dimensional environment <h3>
<h3> As a player I would like a clear definition of player and NPC <h3>
<h3> As a player I should get feedback when I get hit/lose life <h3>
<h3> As a player I want to define the level's boundaries <h3>
<h3> As a player I want to know when I have won/lost the game <h3> 
<h3> As a player I should choose where to start or to change the difficulty <h3>


# Flow chart
![flowchart](https://github.com/Oliver-Slape/Project-01/blob/master/TraceBall.png)

<h1> Product Backlog <h1>
<h3> High Level Function Requirements <h3> 
<h4> Create Canvas <h4>
<h4> Character has 3 lives <h4>
<h4> Create character <h4>
<h4> Create NPC <h4>
<h4> User mouse movement moves player <h4> 
<h4> NPC moves to player <h4> 
<h4> Mouse stays within window <h4> 
<h4> Collision is detected and displayed <h4>
<h4> Start and stop game <h4>
<h3> High Level Non-Function Requirements <h3>
<h4> Canvas, NPC and Player are Squares <h4>
<h4> Canvas is grey <h4>
<h4> Player is green for good <h4>
<h4> NPC is red for bad <h4>
	
<h1> Sprint Backlog <h1>
<h3> As a player I would like to play this game in my browser (cross platform) <h3>
<h3> As a player I would like to see the UI (new game/quit game) <h3>
<h3> As a player I would like to move my character in a 2 dimensional environment <h3>
<h3> As a player I would like a clear definition of player and NPC <h3>
<h3> As a player I should get feedback when I get hit/lose life <h3>
<h3> As a player I want to define the level's boundaries <h3>
<h3> As a player I want to know when I have won/lost the game <h3>	
<h3> As a player I should choose where to start or to change the difficulty <h3>

<h1> Design Documentation <h1>

<h2> Process of implementation:<h2>
<h3> Drawing the canvas:<h3> 

```
function canvasDraw() {
  	ctx.fillStyle = "grey";
  	ctx.fillRect(0, 0, canvas.width, canvas.height);
  	ctx.fillStyle = "#00ff00";
  	ctx.beginPath();
```

<h3> Drawing the NPC <h3> 

```
"function NPC() {
	ctx.fillRect( rX, rY, 30, 30);
	ctx.fill();
	ctx.fillStyle= "#FE0000";"
```
<h2> IDE use and features: <h2>
<h3> Notepad was used as the IDE its a simple text program with no added features. <h3>

<h2> Debugging process: <h2> 
<h3> For debugging the IDE did not have any features so the console from the platform was used. This was Google Chrome. <h3>

<h2> Coding Standards: <h2>
<h3> Indentation: <h3>
	
```
function start() {
	// set a radius for the circle
	const RADIUS = 20;
``` 
<h3> Spaces before and after Operators: <h3>
	
```
x += e.movementX;
```
<h3>
<h2> Evaluation <h2>

<h3> Debugging helped find and locate the errors in the code and improve the functionality of the program. <h3>
