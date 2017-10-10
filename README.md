# Project-01
Trace Ball

<h1> User stories <h1>
<h3> As a player I would like to play this game in my browser (cross platform) <h3>
<h3> As a player I would like to see the UI (new game/quit game) <h3>
<h3> As a player I would like to move my character in a 2 dimensional environment <h3>
<h3> As a player I would like a clear definition of player and NPC <h3>
<h3> As a player I should get feedback when I get hit/lose life <h3>
<h3> As a player I want to define the level's boundaries <h3>
<h3> As a player I want to know when I have won/lost the game <h3> 
<h3> As a player I should choose where to start or to change the difficulty <h3>


<h1> Flow chart <h1>
![flowchart](https://github.com/Oliver-Slape/Project-01/blob/master/TraceBall.png)


<h1> Design Documentation <h1>
<h2> Process of implementation:<h2>

<h3> Drawing the canvas:<h3> <h4> "function canvasDraw() {
  			ctx.fillStyle = "grey";
  			ctx.fillRect(0, 0, canvas.width, canvas.height);
  			ctx.fillStyle = "#00ff00";"
<h4> 

<h3> Drawing the NPC <h3> <h4> "function NPC() {
					ctx.fillRect( rX, rY, 30, 30);
					ctx.fill();
					ctx.fillStyle= "#FE0000";"
<h4>

<h2> IDE use and features: <h2>

<h3> Notepad was used as the IDE its a simple text program with no added features. <h3>

<h2> Debugging process: <h2> 

<h3> For debugging the IDE did not have any features so the console from the platform was used. This was Google Chrome. <h3>

<h2> Coding Standards: <h2>

<h3> Indentation 
function start() {
			// set a radius for the circle
			const RADIUS = 20;
<h3> 

<h3> Spaces before and after Operators 
x += e.movementX;

<h3>

<h2> Evaluation <h2>

<h3> Debugging helped find and locate the errors in the code and improve the functionality of the program. <h3>
