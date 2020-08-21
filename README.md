# Unreal Engine Project

This project was made in three months as part of my studies in the computer science department at
ENSICAEN, an engineering scool in Caen, Normandy, France.<br/>
It was made as a replacement of the end-of-second-year internship abroad that was canceled due to Covid-19.

This project is made with Unreal Engine 4.25.1, game engine developed by Epic Games, and uses the Steam Online Subsystem.

It was intended to create a first person shooter game with two modes :
* Solo : the player plays against an artificial intelligence
* Multiplayer : two players play together online using the Steam Online Subsystem

# Multiplayer System

This game uses the Steam Online Subsystem to play online.
Thus, this requires the free video game platform Steam.<br/>
One player have to host a game, whith a custom server name.
The other player have to clic on "Search" and find the server to join in the list.
The servers displayed will only be those of this game because the system uses a keyword to identify the game.

# Gameplay

## Rules

The goal of the game is to win six rounds.<br/>
The player win one round by killing their opponent.<br/>
There is a maximum of ten rounds. So if both of the players have five points, the game end in a draw.

## Game mechanics

### Health and Shield

The player have health and shield, both displayed on their screen. The shield reduces some of the damage received.

### Weapons

There are two different weapons :
* AK47 : a riffle that have a high firerate
* Sniper : have a scope and deals heavy damage, but have a low fire rate

### Controls

|  Input | Keyboard/Mouse | Gamepad |
|---|---|---|
| Move | Z,Q,S,D | Left Thumbstick |
| Camera Orientation | Mouse Movement | Right Thumbstick |
| Jump | Space Bar | Face Button Bottom |
| Shoot | Mouse Left Clic | Right Trigger |
| Sneak | Ctrl | Right Thumbstick Button |
| Sprint | Left Shift | Left Thumbstick Button |
| Aim | Mouse Right Clic | Left Trigger |
| Reload | R | Face Button Left |
| Select Weapon | & or é | None |
| Scroll Weapon | Mouse Wheel | Left and Right Shoulders |
| Pause | Escape or P | Special Right |

# Credits

Menu Music : Hitman by Kevin MacLeod (Available under the Creative Commons Attribution 3.0 Unported license)<br/>
Character assets : [DevSquad Learning Hub First Person Shooter Tutorial](https://www.virtushub.com/first-person-shooter)<br/>
AK47 assets : [FPS Weapon Bundle](https://www.unrealengine.com/marketplace/en-US/product/fps-weapon-bundle)<br/>
Sniper assets : [Military Weapons Dark](https://www.unrealengine.com/marketplace/en-US/product/military-weapons-dark)