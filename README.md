# Vivian Giacobbi's Portfolio

Technical designer and programmer with 6+ years of experience seeking senior-level design position on action-oriented and sandbox games.

## Gameplay Scripting

### Core Combat Loop

https://github.com/VivianGiacobbi/portfolio/assets/57081585/0d499505-7b00-4e55-b80e-f75d809aefff

The core combat loop of Playable World's untitled MMO took inspiration from fast-action arcade games of the 1980s and 1990s. Player characters can freely run, fly, and dodge to counter enemies. My primary goal was to capture a feeling of speed and reactivity long absent in major MMOs, and to reward players with skillful aim who participate in combat. However, we also took care to balance for more casual players, with homing and AOE weapons to reward alternate, less precise playstyles.

https://github.com/VivianGiacobbi/portfolio/assets/57081585/aaf8578c-ba27-45d4-ad2a-f31c346caebd

As technical designer, I led development on the core combat functionality. I also personally owned and created the powerups system (seen above), resource tables, and item collection to highlight and reward active gameplay.

### Aggro Tooling

https://github.com/VivianGiacobbi/portfolio/assets/57081585/caf2ebe3-7d56-4a19-b140-2f51b69cd58c

This is developer tooling I created  in-engine at Playable Worlds in order to debug enemy aggression in combat. As product owner of our game's combat, I oversaw constant iteration of how enemies perceived players in our living world and wanted to provide other developers easy visibility on how enemies make combat choices. In this system, players are dropped aggro at a certain distance and after they've last procced aggro. The tool shows the player's position in an enemy's list of threats, as well as the distance and idle period remaining for a player to be completely forgotten.

### Procedural Boss Encounters

https://github.com/VivianGiacobbi/portfolio/assets/57081585/0a799879-b952-4945-aa6d-ef938b91a5db

To fulfill our mission statement of "creating the most living world in gaming", I experimented with boss encounters to capture the feeling of MMO raid mechnics while allowing us to procedurally spawn them upon creating new worlds. Not only do the enemy spawners act to sustain the ecology of a world by creating new inhabitants, they are also dangerous foes themselves. Players must discover them, fend off guarding sentries, and coordinate to hack outlying weak points that power their shields. 

As lead on these encounters, I built these bosses with accessible data knobs so designers could tune and test them for quick iteration. Spawners can spawn varying numbers of hackable points, create variable size waves of defending enemies when threatened, cloak themselves, and even fire their own procedurally generated attacks at players.

### Crafting Loop

https://github.com/VivianGiacobbi/portfolio/assets/57081585/f962a5a0-8318-42ca-945a-34e2b95de8ec

https://github.com/VivianGiacobbi/portfolio/assets/57081585/5696ce2c-34fc-41bd-a5c3-b518eb978302

Resource collection and crafting are core tenants of Playable World's MMO, and nearly every surface and object in the world is harvestable for resource units. Leveraging our proprietary technology, I created player harvesting tools to tunnel through the world and terraform planets to the players' whims.

https://github.com/VivianGiacobbi/portfolio/assets/57081585/450e6cfe-34b8-44b2-b0e8-370d6cc6b31b

Our simulated world enabled players to collect more distinct props such as trees, which share resource tags with terrain to make them as reactive to player actions. I created and owned systems to simulate tree growth, allowing them to evolve from seedling to sapling to mature adult, spread new saplings at maturity, and be harvested for wood with another player tool.

https://github.com/VivianGiacobbi/portfolio/assets/57081585/babd0fab-dac3-4066-b644-c15f908f484b

I also assisted in design of our crafting system, from its initial spec all the way to the data and scripting needed to make it player facing. All materials that the player collects can be used in a crafting system to provide them stronger tools, more interesting gameplay mechanics, and collectables to help sustain them in combat.

## Downloadable Prototypes

// to be updated
## 🚀 About Me
I'm Vivian Giacobbi, a technical designer based out of Nashville, Tennessee. My primary experience lies with networked action games and single-player puzzle games.

