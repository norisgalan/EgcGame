# 🔦 GrandpaMaze

## "Can you escape the Maze?" 

## GrandpaMaze is a survival-horror experience built in Unity. The player is spawned into a grim, claustrophobic maze with one goal: find the hidden key and escape before being caught by the chainsaw-wielding zombie that haunts the corridors.

# 🎮 Gameplay & Mechanics
As outlined in the Game Design Document, the game focuses on resource management and environmental awareness:

## Primary Objective: Search the maze for the exit key hidden within various chests.

## Interaction System: The standard crosshair changes to a hand icon when near a chest. Press "E" to open it and collect items automatically.

## Limited Combat: You may find a Glock pistol. It contains a single magazine of 15 bullets. Once empty, you must rely on stealth to survive.

## Permadeath: If the zombie touches you, the game ends immediately.

# Controls
## W, A, S, D - Character Movement 
## Mouse - Camera Look
## Left Shift (Hold) - Sprint / Run
## E - Interact (Open Chest)
## Left Click	- Fire Weapon

# 🧟 Enemy AI (The Chainsaw Zombie)
## The antagonist is modeled with a specific state-based AI system:
## Patrol State: The zombie moves between established waypoints throughout the maze. You will hear a repetitive chainsaw-starting sound.
## Chase State: If you enter the zombie's detection range, it will begin to sprint toward you. The audio cues will change to a high-revving chainsaw sound.

# 🛠️ Project Structure
## This repository includes the core elements required for the game build:
## Assets: All scripts, 3D models, and audio files.
## ProjectSettings: Configuration for inputs (WASD, E) and physics.
## Documentation: The official Game Design Document (GDD) follows the required outline, addressing everything from Game Flow to Puzzle Structure.
