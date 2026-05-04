# HordeDefender — Unity 3D Game
## CS 325: Software Engineering | George Mason University | Group Project

A 3D Unity game where players alternate between a farm management phase and 
a wave-based battle arena. In the farm scene, players plant and harvest crops 
to earn powerups and weapons, and purchase upgrades from a shop. In the battle 
scene, players fight off waves of enemies in first-person with projectile weapons 
while surviving increasingly difficult hordes. The intended loop was 
MainMenu → Farm → Battle → Farm → Battle -> ..., though the project delivered one 
full sequence due to time constraints.

## My Contributions
Built the Battle Scene from scratch: first-person player controller with 
crosshair, projectile weapon system (bow/gun), enemy horde spawning and 
AI chase behavior, health UI, hit detection, and wave management. Fixed and 
overhauled the Main Menu scene. Implemented audio and scene transition logic 
connecting all three scenes into a playable sequence.

## Tech Stack
Unity (C#), TextMesh Pro, NavMesh, imported 3D asset packs

## How to Run
1. Clone the repository
2. Open in Unity
3. Open `Assets/Scenes/MainMenuScene.unity` to start
4. Press Play in the Unity Editor

## Features
- Main menu with difficulty selection and panoramic camera
- Farm scene: plant/harvest crops, earn powerups, buy from shop
- Battle scene: first-person combat, projectile weapons, horde enemy AI
- Wave-based enemy spawning with chase behavior
- Full scene transitions across all three phases
- Background music and sound effects
