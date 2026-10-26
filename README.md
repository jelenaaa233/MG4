# MG4
## Devlog
The FloatAnimation script enables fish food to continuously bob up and down. In the Start() method, a 3-second timer is initialized when the game begins. The Update() method updates the position of the fish food each frame, using Time.deltaTime to manage both the movement and the timer. A boolean variable, up, determines whether the fish food moves upward or downward. When the timer reaches zero, it resets to 3 seconds, and the state of the up variable toggles—causing the fish food to move up and down repeatedly.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)
