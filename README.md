# Physball Prototype 1

Physball is a simple physics game about rolling a ball around on platforms, solving puzzles.

## Game Mechanics Guide

You can use the WASD keys to move around. 'W' makes you move forward, 'S' makes you move backward, 'A' makes you move to the left, and 'D' makes you move to the right. You use the mouse to look around. Moving the mouse makes you look in the direction you moved the mouse. You can use the 'Space' key to jump. However, all player movement is rotation-based. This means that when you are in the air, you cannot change the direction you are moving, only the direction you are rotating.

## Demo Video

You can watch the demo video here: https://youtu.be/RtaWSMp208s

## Prototype Download

You can download the prototype for MacOS, Windows, and Linux here: https://github.com/Kneelawk/physball/releases/tag/prototype-1-3

# Design Doc

## Elevator Pitch

Do you like puzzle games? Do you like physics games? Do you like exploration games? My game Physball combines these aspects into cohesive level-based experience. Physball is a physics-based puzzle game written in Rust using the Bevy engine. Roll a marble around a game world, solving puzzles, and collecting powerups, and work to complete each level! The game will even have a dynamic level system, allowing players to create their own levels and share them with their friends.

## Game Synopsis

Physball is a physics puzzle game about rolling a ball around a floating obstacle course, solving puzzles to reach the end of each level. Levels are generally supposed to be simple bite-sized puzzles, though some may be quite complex.

## Game Objective

The objective of this game is to complete each level by moving a ball from a starting platform to a finishing platform by solving puzzles along the way.

## Game Mechanics

Level puzzles are generally supposed to be a combination of maneuvering the ball through the level while trying not to fall off and completing different object-relationship puzzles like putting a cube on top of a button or pushing a ball through a tube. Some levels may involve giving the player various abilities like super speed, flight, or a laser gun.

## Example Mockup

![Screen Layout](https://raw.githubusercontent.com/Kneelawk/CSS385/refs/heads/project-proposal/screen-layout.png)
![Example Level](https://raw.githubusercontent.com/Kneelawk/CSS385/refs/heads/project-proposal/example-level.png)
