# Project Name
MSCH-C220 Final Project

## Theme
How you thought about or interpreted the theme
    I thought about the many dinosaur movies and how the person always has to avoid the dinosaurs to escape so I made it into a game.

## Game Play
Objective 
    Make it to the Helicopter while avoiding the Dinosaurs
Game-play instructions
    Press W to move forward and avoid the dinosaurs

## What did you 
Struggles or surprises you encountered during the development of the game
    1. I struggled to get on enter collider to work for detecting if the player gets hit by a dinosaur so Instead I used raycasting with a very short distance. This also gave the effect of allowing the player to just barely make it in front of a dinosaur without getting hit.
    2. nav mesh can be quite hard to use especially when trying to get the speed of a nav mesh unit

## Implementation
Features
    3d main menu screens that are animated and reflect how the player is doing and show score and high score
    My own nav mesh agent movement system for the player.
    A Nav mesh movement system for the enemy dinosaurs
    Music I played on my guitar for the menus and sound from the 3rd person character for footsteps for my character
    Animations, models, and textures I found for the terrain, enemy dinosaurs, and the character
    Made sure animations change based on speed (Players is a little clunky)
    Collision detection based on short range raycasting
    The level in which the player has to cross the dinosaur paths and make it to the Helicopter.
    The cliffs I made were probuilder cubes that I then mainipulated to make more ragged and cliff shaped so the texture I applied looked better


Assets, or resources used
    All Assets and textures I used are in the references
## Special Focus
What is your special focus? What did you do for it? How would you rate your own effort? 1-5. (I will agree or disagree with this sentiment, but I want to know what you thought)
I spent a lot of time on the mechanics. I made a nav mesh agent based movement system that goes to an invisible sphere and then creates a new one 5 meters away. This allowed for me to move the 3d character with only one button. I also made sure that the player could not break it by pressing the W key a lot as it prevents activation of the setting the path until the character has reached its current destination. I also added a camera that follows the player at an angle a lot like the road crossing games. Then for the dinosaurs I made a nav mesh agent that goes to a point and then teleports back to where it started to repeat the motion again much like in road crossing games. I also wanted to make sure that all the lanes of dinosaurs were not constantly going so they only make a new path when an invisible ball over the lane is in view of the camera. Considering I spent probably around 10 hours on just the movement for both the enemies and the player (combined not both 10 hours) I'd says I put decent effort into the movement mechanics and just the mechanics in general. For instance it took me a few hours to finally get the collision to work for when a player gets hit / runs into a dinosaur. So I will give myself a 4/5 for my special focus since I could always do better and theres no special or revolutionary mechanics.

## References
Trex-
    "Looping Animation of T- Rex Dinosaur Model" (https://skfb.ly/o9UpX) by LasquetiSpice is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
    "Animated Tyrannosaurus Rex Dinosaur Running Loop" (https://skfb.ly/o9nF6) by LasquetiSpice is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
    "Animated Dinosaur Attacks Human Character Loop" (https://skfb.ly/o9BoT) by LasquetiSpice is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).

Trees-
    "Trees Low Poly" (https://skfb.ly/6YpAS) by Igor_K. is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).

Helicopter-
    "Bell Huey helicopter" (https://skfb.ly/6vLEC) by Duane's Mind is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).

Stegosaurus-
    "STEGO" (https://skfb.ly/oM76p) by seth the yutyrannus is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).

Triceratops-
    "Triceratops from unity" (https://skfb.ly/oMBSx) by dead tubby's is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).

Pachycephalasaurus-
    "PBR Pachycephalasaurus (Animated)" (https://skfb.ly/oHptR) by Ferocious Industries is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).

Swat Character and animations-
    https://www.mixamo.com/#/

Music recorded on-
    https://www.soundtrap.com/

Terrain Textures-
    https://freepbr.com/
## Future Development
Possibly add more/harder levels

# Created by: Clayton Matthias
