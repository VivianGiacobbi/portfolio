# Vivian Giacobbi's Portfolio

Technical designer and programmer with 6+ years of experience seeking senior-level design position on action-oriented and sandbox games. My previous work was on the cloud sandbox MMO created by [PlayableWorlds](https://www.playableworlds.com/)

## Gameplay Scripting
As technical designer at Playable Worlds, my primary role was to design, implement, iterate on, and document core features of the game both in-engine using Unity and via our proprietary scripting solution. Working as a designer, a programmer, and a product owner on major features, I spent most of my days iterating on player-facing content and sticking to our core mission: finding fun!

### Core Combat Loop
The core combat loop of Playable World's untitled MMO took inspiration from fast-action arcade games of the 1980s and 1990s. Player characters can freely run, fly, and dodge to counter enemies. My primary goal was to capture a feeling of speed and reactivity long absent in major MMOs, and to reward players with skillful aim who participate in combat. However, we also took care to balance for more casual players, with homing and AOE weapons to reward alternate, less precise playstyles.

https://github.com/VivianGiacobbi/portfolio/assets/57081585/0d499505-7b00-4e55-b80e-f75d809aefff

As technical designer, I led development on the core combat functionality. I also personally owned and created the powerups system (below), resource tables, and item collection to highlight and reward active gameplay.

https://github.com/VivianGiacobbi/portfolio/assets/57081585/aaf8578c-ba27-45d4-ad2a-f31c346caebd

### Aggro Tooling
Below is developer tooling I created  in-engine at Playable Worlds in order to debug enemy aggression in combat. As product owner of our game's combat, I oversaw constant iteration of how enemies perceived players in our living world and wanted to provide other developers easy visibility on how enemies make combat choices. In this system, players are dropped aggro at a certain distance and after they've last procced aggro. The tool shows the player's position in an enemy's list of threats, as well as the distance and idle period remaining for a player to be completely forgotten.

https://github.com/VivianGiacobbi/portfolio/assets/57081585/caf2ebe3-7d56-4a19-b140-2f51b69cd58c

### Procedural Boss Encounters
To fulfill our mission statement of "creating the most living world in gaming", I experimented with boss encounters to capture the feeling of MMO raid mechnics while allowing us to procedurally spawn them upon creating new worlds. Not only do the enemy spawners act to sustain the ecology of a world by creating new inhabitants, they are also dangerous foes themselves. Players must discover them, fend off guarding sentries, and coordinate to hack outlying weak points that power their shields. 

https://github.com/VivianGiacobbi/portfolio/assets/57081585/0a799879-b952-4945-aa6d-ef938b91a5db

As lead on these encounters, I built these bosses with accessible data knobs so designers could tune and test them for quick iteration. Spawners can spawn varying numbers of hackable points, create variable size waves of defending enemies when threatened, cloak themselves, and even fire their own procedurally generated attacks at players.

### Crafting Loop
Resource collection and crafting are core tenants of Playable World's MMO, and nearly every surface and object in the world is harvestable for resource units. Leveraging our proprietary technology, I created player harvesting tools to tunnel through the world and terraform planets to the players' whims.

https://github.com/VivianGiacobbi/portfolio/assets/57081585/f962a5a0-8318-42ca-945a-34e2b95de8ec

https://github.com/VivianGiacobbi/portfolio/assets/57081585/5696ce2c-34fc-41bd-a5c3-b518eb978302

Our simulated world enabled players to collect more distinct props such as trees, which share resource tags with terrain to make them as reactive to player actions. Shown below, I created and owned systems to simulate tree growth, allowing them to evolve from seedling to sapling to mature adult, spread new saplings at maturity, and be harvested for wood with another player tool.

https://github.com/VivianGiacobbi/portfolio/assets/57081585/450e6cfe-34b8-44b2-b0e8-370d6cc6b31b

I also assisted in design of our crafting system, from its initial spec all the way to the data and scripting needed to make it player facing. All materials that the player collects can be used in a crafting system to provide them stronger tools, more interesting gameplay mechanics, and collectables to help sustain them in combat.

https://github.com/VivianGiacobbi/portfolio/assets/57081585/babd0fab-dac3-4066-b644-c15f908f484b

## Downloadable Prototypes
In my original role at PlayableWorlds, I was tasked with quickly creating an iterating on standalone prototypes of game systems to test our specs and pave the way for in-engine implementation. Some of these protoypes were fast——turnarounds of two days or less! I leveraged my skills using Unity's quick prototyping tools and editor scripting to return quick results. All design, scripting, art, UI, and animation in these prototypes is created custom by me and using free assets.

### Jetpack Flight
A major component of our game's combat is verticality, and the player uses a gravity pack to jet around to evade and snipe enemies. Before we had character controller systems to implement jetpacks in-game, I created a dirty prototype to allow designers to test and tune variables for player flight as early as our first spec, including how it interacted with fall damage and limited fuel. This prototype includes an editor menu derived from Unity's editor inspectors, allowing the player to set various exposed data values, and even choose and save presets.

https://github.com/VivianGiacobbi/portfolio/assets/57081585/3d40b20a-88fe-4fac-bcf5-19473627bed9

### Resource Extraction
In the tunneling video above, the player's mining laser draws resources from the soil and rock they dig away. This prototype was an early visualization of the underlying sim using my own custom generation scripts. Each cell has internal data for resources (denoted by colored pixels) that are drawn on the textures, and we wanted to test various knobs for the player's future tool such as its radius, depth, and the amount it can extract per cell.

https://github.com/VivianGiacobbi/portfolio/assets/57081585/1efbb9c5-371d-4a18-96be-ec53af7b7e14

### Player Inventory and Radial Menu
The combat videos above display changing equipment in-battle using the inventory window as well as a radial menu for using consumable items. I prototyped both of these systems here in a simple scene where the target switches "weaknesses" to various weapons in the player's inventory. This additionally was used as a test for controller support for major game systems, and I created the display at the bottom right highlighting button inputs to hightlight both control schemes.

https://github.com/VivianGiacobbi/portfolio/assets/57081585/e30df52a-079e-4859-887d-a15dc97e551b

### For fun: 3D Tetris!
I also love to create little coding projects in the meantime. This one wasn't created for PlayableWorlds, and was instead a fun distraction. It's a simple 3D Tetris-styled game where the goal is to create the smallest dimension possible by placing the blocks in the 3D landscape. To navigate the 3D environment, I took inspiration from the Gummi Ship garage in Kingdom Hearts, and the pieces are randomly created by a custom depth-first search in 3D space using each voxel as a node in the tree, which is then "sliced" into multiple pieces.

https://github.com/VivianGiacobbi/portfolio/assets/57081585/d2396dac-c3a0-4e0b-90ac-fc4fafb294c2

## Design Documentation
https://github.com/VivianGiacobbi/portfolio/blob/5aa8218518b3b90f0593f90307d6319546edd687/giacobbi_diagram_movement.pdf


## 🚀 About Me
I'm Vivian Giacobbi, a technical designer based out of Nashville, Tennessee. My primary experience lies with networked action games and single-player puzzle games.

