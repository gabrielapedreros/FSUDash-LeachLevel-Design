# FSUDash-LeachLevel-Design
In my CEN4020L capstone course, our group decided to develop a game using the PyArcade tutorial. We decided to use Tiled for designing each level. Leveraging AI for designing game levels. 

## Creating the tilemap using AI
My level was located at The Leach, the main gym at FSU. I worked with AI to create a tiled-map based on images of the Leach I feed it. I also instructed it to create the image as a 2d background. The is when I got "gym.png". This was my base, using tiles from this image to create the leach level. I also created "tileset.png", which was a tilemap of gym equipment.

## Designing my Level
	<ins> ### Creating Tilesets </ins>
Once I got my base image I wanted to use tiles from, then I create the actual tile map I would implement in PyAracde. I used "gym.png" to create "leach.tsx", this is the map I would take tiles from to create my level. Additionally, from "tileset.png" I created tileset.tsx. These files were the tilesets I would use.

### Creating Layers for the Level
There were Tile Layers and Object Layers that I created. The tile layers were layers that would be considered the background in the game. So in that case: Background, platform, coins. And the object layers were: Player and enemy. 

### AI created Images
Player: player.jpg

### Open Source Images
Enemy: scarytiger.png

### Power Ups
I ended up using the gym equipment tiles to use the weight as the power up or "coins".

# Final Tilemap
The final tilemap we used for the game was "level3final.tmx".
