- COMP313
- Caylum Blenkhorn
- Assignment 1
- Game name: Dawn
- Video Gameplay : BLENKHCAYL-gameplay.mp4

Controls:
	LMB - Select object (star, planets, ship)
	RMB - Hold to rotate camera
	ESC - open Pause menu
	ENTER - move ship to selected object
	SPACE - Destroy object

Description: 
	The primary objective of the game is to destroy all the planets, doing so will result in a win
	
	I would say the most difficult part of creating this short game was making a custom game controller
	that uses the mouse cursor, and having the cursor be able to both click on moving objects in the 
	game, and move the camera while holding the right mouse button down.

	Personally I quite like that each time the game is played, the solar system created is always different,
	though this doesn't really effect the gameplay at present. All you need to do to create a fully random
        new solar system is to simply place in a 'SolarSysDynamic' Actor. This actor then proceeds to generate 
	a sun at it's center of random size and colour, then generates a random number of planets each with
	varying sizes and distances from said sun.
	

