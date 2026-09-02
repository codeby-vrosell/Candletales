<p align="center">
  <img src="IMG/banner.jpg" alt="Candletales Banner" />
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

- [**Gamepad_Vibrator**](/Gamepad_Vibrator): Handles gamepad vibration effects and haptic feedback throughout the game.  
- [**MAYA_AI**](/MAYA_AI): Scripts for MAYA, the game AI, including controllers, tutorial logic, text box animations, audio spectrum effects, jokes, and announcements. Includes the dialogue CSV (used in Unity) and a visual Excel/PDF for reference.
- [**Map**](/Map): Allows player interaction with the environment (slime meshes, checkpoints, sky events).  
- [**Menus**](/Menus): Game UI, including credit screens, main menu, hover animations, fades, and aesthetic element transitions.  
- [**Player**](/Player): Player-related scripts such as aiming, crosshair control, door controllers, mesh switching, teleportation, and upgrade systems.  
- [**Procedural_Animation**](/Procedural_Animation): Procedural adjustments like aligning character’s feet to terrain.  
- [**Ship**](/Ship): Ship-related scripts, including in-game computer text effects, floating effects, and screen controllers.  
- [**Tutorial**](/Tutorial): Scripts for tutorials: animations, visual effects, tutorial zone indicators, and step-by-step tutorial manager.  
- [**UI**](/UI): In-game UI control, including full-screen glitch effects, glitch animator control, and player stimulants display.  
- [**Weapon**](/Weapon): Weapon-related scripts including main weapon controller, QTE burner mechanics, hit zone management, slime suction, ammo/tank UI, shooting logic, and additional effects like FOV changes, weapon sway, and recoil.

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
  <img src="IMG/IMG1.png" alt="Candletales Screenshot 1" width="30%"/>
  <img src="/IMG/IMG2.jpeg" alt="Candletales Screenshot 2" width="30%"/>
  <img src="/IMG/IMG3.jpeg" alt="Candletales Screenshot 3" width="30%"/>

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
