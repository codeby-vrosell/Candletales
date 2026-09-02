<p align="center">
  <img src="/Assets/banner.jpg" alt="Candletales Banner" />
</p>

# Candletales

## Project Overview

This repository contains all the custom C# scripts developed by the author for **Candletales**.    
These scripts cover procedural grid generation, turn-based mechanics, UI updates, visual effects, dynamic weather systems, player interactions, and other core functionalities.

## Important Disclaimer

This repository does **NOT** contain the complete game project.  
Assets, scenes, and other game elements are **not included**. Only the scripts developed by the author are present.

**Please note:** Scripts for certain game mechanics are also **not included**, as they were created by other developers and are outside the scope of this repository.

## Scripts Organization

Scripts are grouped by functionality:

- [**Bonfire**](/Bonfire): Manages the bonfire interaction logic and progression or checkpoint mechanics.  
- [**BossInvoker**](/BossInvoker): Handles the sequence, chain animations, and prefab mapping for summoning bosses.  
- [**Camera**](/Camera): Controls dynamic camera behaviors like parallax scrolling and impact shake effects.  
- [**Cursor**](/Cursor): Manages custom cursor visuals, hold-to-fill progress, and layer-specific interaction states.  
- [**DevTools**](/DevTools): Provides a debugging panel interface for testing and adjusting game variables at runtime.  
- [**EntityScript**](/EntityScript): Governs general entity behaviors like procedural falling animations upon spawning.  
- [**FloatingNumber**](/FloatingNumber): Controls the instantiation and animation of floating combat text or damage numbers.  
- [**Gamefeel**](/Gamefeel): Centralizes visual impact effects, hitstops, and global particle systems to enhance combat weight.  
- [**Ilustrations**](/Ilustrations): Manages the display and animation sequences for 2D illustrative UI assets.  
- [**InspectorEditors**](/InspectorEditors): Contains custom Unity Editor scripts to streamline the configuration of biomes, stages, and tile types.  
- [**Lights**](/Lights): Handles environmental lighting behaviors such as procedural flickering and motion logic.  
- [**MarineAnimals**](/MarineAnimals): Controls the spawning, management, and behaviors of ambient marine entities.  
- [**Outline**](/Outline): Manages the dynamic coloring and rendering of visual outlines for hovered or selected grid objects.  
- [**Pathfinder**](/Pathfinder): Computes shortest-path navigation for entities across the procedural grid.  
- [**Player**](/Player): Orchestrates the core cinematic sequences for the player's initial spawn and death transitions.  
- [**ProceduralGeneration**](/ProceduralGeneration): Drives the core grid layout, biome seeding, cell state tracking, and dynamic border generation.  
- [**Slime**](/Slime): Controls the interactive slime hazard that swallows, empowers, and violently launches player dice.  
- [**Splines**](/Splines): Translates external JSON data into procedural Unity splines and manages the animation of dynamic chains.  
- [**Stages**](/Stages): Defines the data structures and progression logic for biome transitions and enemy wave configurations.  
- [**StainedGlass**](/StainedGlass): Manages the animations and behavioral states for the stained glass eye entities.  
- [**TileType**](/TileType): Provides the foundational ScriptableObject data templates for grid tiles and multi-tile collision shapes.  
- [**Totems&Candles**](/Totems&Candles): Controls the specific cinematic falling animations for the environmental props during the spawn sequence.  
- [**Totems**](/Totems): Manages the mechanical state and progress bar UI updates for the totem entities.  
- [**UI**](/UI): Handles interface elements including health bar interpolations, UI animations, and 3D billboarding logic.  
- [**Waypoints**](/Waypoints): Manages player-placed grid markers, their physical animations, and off-screen UI pointer targeting.  
- [**Weather**](/Weather): Controls randomized atmospheric particle systems based on cooldown timers and time-of-day constraints.

Each script contains inline comments explaining complex parts and an optional **header README** describing its functionality and responsibilities.

## How to Use

1. Add the scripts to your Unity project under `Assets/Scripts/`.  
2. Assign required references (e.g., `GridManager`, `SplineContainer`, `TextMeshProUGUI`, `ParticleSystem`) in the Inspector.  
3. Configure public settings for procedural generation rules (spawn weights, multi-tile configurations), grid mechanics, and animation durations. 
4. Ensure that core dependent managers (e.g., `GridManager`, `TurnCycleManager`, `WaypointManager`, `WeatherManager`) are present in the scene.  
5. Review script-specific READMEs for detailed usage notes.

## Notes & Recommendations

- Some scripts assume specific GameObject names in the scene (e.g., `"Player"`, `"GridManager"`, `"FloatingNumberManager"`).  
- Scripts have been tested on Unity 6 (6000.3.8f1) with HDRP. Adaptation may be required for URP, Built-in pipeline, or other Unity versions.
- This repository focuses on gameplay scripting and does not include 3D models, textures, audio files, or scenes.  
- Some mechanics rely on external scripts not included in this repository.
  
## Watch Candletales

The following screenshots display BIOLEECH gameplay and environments:

<p align="center">
  <img src="/Assets/IMG1.png" alt="Candletales Screenshot 1" width="30%"/>
  <img src="/Assets/IMG2.png" alt="Candletales Screenshot 2" width="30%"/>
  <img src="/Assets/IMG3.png" alt="Candletales Screenshot 3" width="30%"/>

The official Candletales trailer is available on:

- **Youtube:** [Candletales Trailer](https://www.youtube.com/watch?v=4m0XaohYrC4)

</p>

## Play Candletales

Candletales is available for download on the following platform:

- **Steam:** Coming Soon.

## Collaborators

While this repository contains only the scripts developed by the author, **Candletales** is a collaborative project with contributions from other developers, artists, and designers.  

For more information and links to the team, visit the official Desalichao Studio Linktree:

- **Linktree:** [Desalichao Studio](https://linktr.ee/desalichaostudio)

## Author & Contact

**Author:** Víctor Rosell Gascó

- **Gmail:** codeby.vrosell@gmail.com  
- **Portfolio:** [codebyvrosell.com](https://x.com/codeby-vrosell)   
- **Twitter:** [@codeby_vrosell](https://x.com/codeby-vrosell)  
- **GitHub:** [@codeby-vrosell](https://github.com/codeby-vrosell)  
- **LinkedIn:** [in/v-rosell](https://linkedin.com/in/v-rosell)

## License

All rights reserved.

You may not use, reproduce, modify, or distribute the code in this repository, in whole or in part, without the express written permission of the author.

**Please note:** If you are interested in using any of these scripts in your own projects, you must contact the author directly to request formal authorization.
