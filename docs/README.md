

<center>
    <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/selfie.png" alt="Selfie" width="400">
</center>

<p>Hi there, I'm Vivian! I'm an experienced designer and programmer who also dabbles in visual art.</p>
<p>I'm a huge fan of The Legend of Zelda, Tokusatsu, RWBY, and weird technical videos about the N64 architecture.<p>
<p>I work out of Denver, Colorado.</p>

<h1>Collected works<h1>

<h2>2026</h2>

<center>
  <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/megamix/giacobbi_megamix_title.png" alt="Megamix Engine 2" width="588">
  <a href="https://www.magmmlcontest.com/">Website</a>
</center>

<details>
  <p>Since 2026, I've worked as a leading contributor on Megamix Engine 2, the successor to the original <a href="https://github.com/MegamixEngine/MegamixEngine">Megamix Engine</a>, providing tools, presets, and examples to ease the creation of fangames for Capcom's Mega Man franchise. The engine is used in the Make a Good Mega Man Level games, collaborative projects where participants design levels in the style of the NES Mega Man games, which are then judged and collected into a cohesive project.</p>

  <h3>Porting and Systems Design</h3>
  <p>Megamix Engine 2 is ported and updated from the Megamix Engine to use modern versions of GameMaker, and takes advantage of its better Room Editor, data structures, and script support.</p>

  <h4>Gravity Changes and Altered Physics</h4>
  <p>Gravity mechanics are hotly requested by participants, and I've helped develop Megamix 2's four-way gravity system to rotate
  and invert player drawing and physics</p>
  <center>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/fanworks/giacobbi_megamix_rushgravity.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>
  </br>

  <h4>Weapon Customization</h4>
  <p>One of my primary contributions is data-driven customization for weapons, a key aspect of Mega Man style gameplay. Weapons
  are data structures with exposed variables that customize a generic object, easing the need for programmers to create bespoke weapon objects and systems.</p>
  <center>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/fanworks/giacobbi_megamix_enemyweapon.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>

  <p>Weapons have, where possible, been abstracted into a form that can be easily dragged-and-dropped onto players and enemies alike. The classic Sniper Joe enemy holds a weapon struct that manages both its projectile and shield, which are automatically processed on
  the player.</p>
  <center>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/fanworks/giacobbi_megamix_joeshield.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>

  <h3>Experimental 3D</h3>
  <p>GameMaker Studio 2 offers robust graphics tools for creating 3D games, despite being a primarily 2D engine. Taking advantage of this, I've begun implementing a 3D extension to Megamix 2, which is an ongoing project to power my own games.

  <h4>2D Sidescrolling/3D First-Person Hybrid Gameplay</h4>
  <center>
    <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/fanworks/giacobbi_gigaamix_3d.gif" width="600">
  </center>

  <h4>Level Editor</h4>
  <p>To supplement 3D behavior, I built a robust voxel-based level editor from scratch with GameMaker. With key optimizations like a binary greedy mesher based on the work of <a href="https://github.com/TanTanDev/binary_greedy_mesher_demo/blob/main/src/greedy_mesher_optimized.rs">TanTanDev</a> for real-time collision and fast iteration of compressed voxel data, this editor extends the features of GameMaker's tile-based Room Editor with few compromises.</p>
  <center>
    <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/fanworks/giacobbi_gigaamix_editor.gif" width="600">
  </center>

</details>

<h2>2025</h2>

<center>
  <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/fanworks/giacobbi_fanworks_logo.png" alt="JoJo's Balatro Fanworks" width="600">
  <a href="https://github.com/VivianGiacobbi/fanworks-balatro">GitHub</a>
</center>

<details>
  <p>I'm the co-creator and lead programmer of <a href="https://github.com/VivianGiacobbi/fanworks-balatro">JoJo's Balatro Fanworks</a>, a vanilla-like <a href="https://www.playbalatro.com/">Balatro</a> expansion mod based on JoJo's Bizarre Adventure and its thriving fan community. Assets were contributed by members of the <a href="discord.gg/GKtmxA4Myv">JoJo's Bizarre Fanworks Discord Server</a>.</p>
  <ul>
      <li><strong>135 New Cards</strong></li>
      <li><strong>11 New Bosses</strong></li>
      <li><strong>15 New Challenges</strong></li>
      <li><strong>60+ Achievements</strong></li>
      <li><strong>And a ton of easter eggs and secrets!</strong></li>
  </ul>

  <center>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/fanworks/giacobbi_fanworks_reel.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>
  <center>
    <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/fanworks/giacobbi_fanworks_credits.png" width="600">
  </center>
  <br>

  <h3>Programming Highlights</h3>
  <p>As lead programmer, I provided over 95% of the project's code, implementing custom systems to meet contributors' needs. This involved deep understanding and reverse engineering of Balatro's source code and modding tools such as <a href="https://github.com/Steamodded/smods">SMODS</a> and <a href="https://github.com/ethangreen-dev/lovely-injector">Lovely Injector</a>.</p>
  <br>

  <h4>A brand-new achievements menu</h4>
  <p>Vanilla Balatro lacks a centralized menu for achievements, instead relying on its various platforms to display them. This added menu is visually cohesive with the game's artstyle, and offers control text for names, descriptions, rarities, and categories.</p>
  <center>
      <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/fanworks/giacobbi_fanworks_achievements.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>
  <br>

  <h4>Custom visual effects</h4>
  <p>This effect for a "timeline change" dazzles the player with a fake jump to the title screen before resuming gameplay with a completely changed game state.</p>
  <center>
      <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/fanworks/giacobbi_fanworks_crystal.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>
  <br>

  <h4>An embedded NES emulator</h4>
  <p>One added card required an entire embedded Nintendo Entertainment System emulator drawing on the work of Nico Abram's <a href="https://github.com/nico-abram/LuaNES">LuaNES.</a></p>
  <center>
      <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/fanworks/giacobbi_fanworks_cabinet.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>
  <br>

  <h3>Design</h3>
  <p>Alongside co-creator <a href="https://github.com/BarrierTrio">BarrierTrio</a>, I helped design from concept to implementation to balance the hundreds of new additions to the vanilla game. I also helped thoroughly document the project from start to finish.</p>
  <center>
      <a href="https://docs.google.com/spreadsheets/d/1TYeIM-ZTyVpfE3NP1T_FvGHGYW1cK0WGd8xRkYFUEXA/edit?gid=2116581461#gid=2116581461"><img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/fanworks/giacobbi_fanworks_spreadsheet.png" width="600"></a>
  </center>
  <br>

  <h3>Art</h3>
  <p>I contributed as an artist, offering thirty pieces of card art as well as editing and art direction for contributors.</p>

  <center>
      <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/fanworks/giacobbi_fanworks_mural.png" width="600">
  </center>
</details>

<center>
  <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/cardsauce/giacobbi_cardsauce_logo.png" alt="Balatro: Cardsauce" width="600">
  <a href="https://github.com/BarrierTrio/Cardsauce">GitHub</a>
</center>

<details>
  <p>The "Official" <a href="https://www.playbalatro.com/">Balatro</a> mod for <a href="https://vinesauce.com/">Vinesauce</a> and its thriving fan community. I worked as a programmer and technical artist to help deliver the 2.0 content update and beyond! This mod has been seen by thousands of people, streamed by Vinesauce's <a href="https://www.youtube.com/watch?v=6OTJAWdgYFw">content creators</a>.</p>

  <h3>Technical Art</h3>
  <p>I offered my work with technical art and shaders to provide unique visual effects to Cardsauce's new card types. Everything goes pop!</p>
  <center>
      <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/cardsauce/giacobbi_cardsauce_redstone.mp4" width="600" autoplay controls muted loop playsinline></video>
      <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/cardsauce/giacobbi_cardsauce_stands.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>

  <h3>Systems Programming</h3>
  <p>I added a completely unique card customization menu that dynamically recolors card sprites, and allows the player to customize their visual experience. All UI elements were custom-made by extending Balatro's UI framework, including inique interactable slider, gradient, and radial widgets.</p>
  <center>
      <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/cardsauce/giacobbi_cardsauce_palette.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>
  <br>
</details>

<h2>2021-2024</h2>
<center>
  <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/starsreach/giacobbi_starsreach_logo.png" alt="Stars Reach Logo" width="600">
  <a href="https://store.steampowered.com/app/1925650/Stars_Reach/">Steam Store Page</a>
</center>

<details>
  <p>As technical designer at <a href="https://www.playableworlds.com/">Playable Worlds</a>, my primary role was to design, implement, iterate on, and document core features of the simulation MMO Stars Reach using both Unity and our proprietary TypeScript engine. Working as a product owner on major features, I spent most of my days iterating on player-facing content and sticking to our core mission: finding fun!</p>

  <h3>Core Combat</h3>
  <p>I pushed forward on Stars Reach's core combat functionality, taking inspiration from fast-action arcade games of the 1980s and 1990s. Player characters can freely run, fly, and dodge to counter enemies, and are rewarded for skillful play. However, we also took care to balance for more casual players, with homing and AOE weapons to reward less precise playstyles.</p>
  <center>
      <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/starsreach/giacobbi_starsreach_combat.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>

  <p>I personally owned and created systems for temporary powerups, resource drops, and item collection highlight and reward active gameplay.</p>
  <center>
      <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/starsreach/giacobbi_starsreach_powerups.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>
  <br>

  <h3>Boss Encounters</h3>
  <p>To fulfill Stars Reach's mission statement of "the most living world in gaming", I experimented with classic raid boss mechanics within our procedural creature generation. Not only do the enemy spawners act to sustain the ecology of a world by creating new inhabitants, they also fulfill that itch of challenging impossible odds. Players must discover them, fend off guarding sentries, and coordinate to hack outlying weak points that power their shields. I built these bosses with accessible data knobs and difficulty options like variable hack points and cloaking behavior so designers could quickly tune and test various iterations</p>
  <center>
      <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/starsreach/giacobbi_starsreach_spawners.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>
  <br>

  <h3>Resource Collection</h3>
  <p>Resource collection and crafting are core tenants of Stars Reach; nearly every surface and object in the world is harvestable for resources. Leveraging our proprietary world simulation, I created player harvesting tools to tunnel through the world and terraform planets to the players' whims.</p>
  <center>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/starsreach/giacobbi_starsreach_scanning1.mp4" width="600" autoplay controls muted loop playsinline></video>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/starsreach/giacobbi_starsreach_scanning2.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>

  <p>The simulated world allows players to harvest props, which share resource tags with terrain to make them as reactive to player actions. My work on simulated tree growth allows tree props to evolve from seedling to sapling to mature adult, spread new saplings at maturity, and be harvested for wood with another player tool.</p>
  <center>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/starsreach/giacobbi_starsreach_treegrowth.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>
  <br>

  <h3>Dev Tooling</h3>
  <p>Below is in-engine developer tooling I created in order to debug enemy aggression. I wanted to provide other developers easy visibility on how enemies make combat choices, and this tool shows the player's position in an enemy's list of threats, as well as the distance and idle period remaining for a player to be completely dropped from enemy aggro.</p>

  <center>
    <video width="600" autoplay controls muted loop playsinline>
      <source type="video/mp4" src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/starsreach/giacobbi_starsreach_aggrotooling.mp4">
    </video>
  </center>
  <br>

  <h3>Design Documentation</h3>
  <p>Although I worked in a technical position at Playable Worlds, I'm a trained designer and leveraged these skills when speccing out major system. I created this flow chart diagram while working to update and refine our game's core character controllers, tracking all transitions and available actions in our main game states.</p>
  <center>
    <object class="pdf"
            data="assets/starsreach/giacobbi_starsreach_movement.pdf"
            width="800"
            height="600">
    </object>
  </center>

  <p>I also contributed deeply to iteration on core crafting mechanics and their skill trees.</p>
  <center>
    <object class="pdf"
            data="assets/starsreach/giacobbi_starsreach_skills.pdf"
            width="800"
            height="600">
    </object>
  </center>

</details>

<h2>2021-2023</h2>
<center>
  <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/proto/giacobbi_prototypes_logo.png" alt="Prototyping Logo" width="600">
</center>

<details>
  <p>During my employment with Playable Worlds, I leveraged my skills creating quick prototypes of systems intended for Stars Reach using Unity. Most of my prototypes are fast——turnarounds of just a few days!</p>

  <h3>Jetpack Flight</h3>
  <p>Before we had character controller systems to implement jetpacks within Stars Reach, I created a dirty prototype to allow designers to test and tune variables for player flight, including how it interacted with fall damage and limited fuel. This prototype includes an full editor menu, allowing the player to set various exposed data values, and even choose and save presets.</p>
  <center>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/proto/giacobbi_proto_flight.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>

  <h3>Resource Extraction</h3>
  <p>An early visualization of Stars Reach's resource harvesting using my own custom generation scripts, based in the underlying world simulation Stars Reach uses for its voxel cells. Each cell has internal data for resources (denoted by colored pixels) that are drawn on the textures, which tests various knobs for resource extraction tools such as its radius, depth, and the amount it can extract per cell.</p>
  <center>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/proto/giacobbi_proto_extraction.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>

  <h3>Inventory and Radial Menu</h3>
  <p>This prototype simulates an elemental damage and weakness system across multiple weapons, as well as a full interactable item UI that supports both controller and mouse input, to test user feedback for controls and UI before extensive work went into Stars Reach's React-based UI.</p>
  <center>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/proto/giacobbi_proto_ui.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>

  <h3>Ship Minigames</h3>
  <p>Stars Reach initially had a focus on small micro-games for crafting, and I created multiple games to determine if the greater abstraction between input and output for crafting increased the fun or provided a barrier to entry. This block-building prototype tests the player to combine objects in the smallest possible space for the best result.</p>
  <center>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/proto/giacobbi_proto_3d.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>

  <h3>Game Boy Adventure</h3>
  <p>Unrelated to my work at Playable Worlds, this prototype uses Gamemaker Studio 2 to create a short-form narrative adventure using the visual style of classic Game Boy titles, which tells the tale of a young kid who stumbles upon a crash-landed alien robot and helps it to recover its missing parts. All systems here——player movement, dialogue, inventory——as well as the in-game art were created by me from the ground-up in three days.</p>
  <center>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/proto/giacobbi_proto_gameboy.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>

</details>

<h2>2021</h2>
<center>
  <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/transmechanism/giacobbi_transmechanism_logo.png" alt="Transmechanism Logo" width="600">
  <p><a href="assets/transmechanism/giacobbi_transmechanism_build.zip">Download</a></p>
  <p><a href="assets/transmechanism/giacobbi_transmechanism_source.zip">Source Code</a></p>
</center>

<details>
  <p>Transmechanism is an exploration-puzzle level design created in Unity as my capstone project for the University of Texas at Dallas's <a href="https://bass.utdallas.edu/programs/arts-technology-and-emerging-communication-media-arts-and-design/">Arts, Technology, and Emerging Communications school (now the Bass School of Arts, Humanities, and Technology)</a>. I worked as sole creator, programmer, and artist. The player is a self-aware android attempting to escape a bombed depot where it was created, populated by malevolent ghosts of its former workers killed in the bombing.<p>
  <center>
    <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/transmechanism/giacobbi_transmechanism_graphic1.png" width="600">
    <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/transmechanism/giacobbi_transmechanism_graphic2.png" width="600">
    <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/transmechanism/giacobbi_transmechanism_graphic3.png" width="600">
  </center>
  <br>

  <h3>Design</h3>
  <p>The level was designed over the course of twelve weeks based around the primary mechanic that hostile ghosts can possess level props to attack the player, but the player must use these possessed props to their advantage to solve puzzles. The entire level began with an extensive planning document and paper map, which was then build out, iterated on, and polished.<p>
  <center>
    <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/transmechanism/giacobbi_transmechanism_doc.png" width="600">
    <p><a href="assets/transmechanism/giacobbi_transmechanism_doc.png">Click here for the full-sized map</a></p>
  </center>
  <br>

  <p>A primary goal for this level was minimal direct tutorialization; controls are given in the HUD, but other elements of gameplay are naturally introduced using markings on the walls and floors, color-coding, and animation, such as a starting room that introduces the player to the aggro range of the ghost enemies, as well as shows the player an "incidental" instance of a ghost possessing an object to urge them to experiment with the core mechanic.<p>
  <center>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/transmechanism/giacobbi_transmechanism_start.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>
  <br>

  <p>Further expansions include hostile props such as a possessed turret the player must evade the turret while directing its bullets to cause a system malfunction, and puzzles challenge the player to lead ghost safely through pillars of sunlight towards puzzle objectives, but those same pillars can also be used to evade danger and cordon the level into safe and non-safe areas.<p>
  <center>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/transmechanism/giacobbi_transmechanism_turret.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>
  <pr>

  <center>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/transmechanism/giacobbi_transmechanism_light.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>
  <br>

  <p>The level ends, once ghost possessions have powered a main generator to open the escape hatch, with an escape sequence setpiece from a massive specter.<p>
  <center>
    <video src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/transmechanism/giacobbi_transmechanism_escape.mp4" width="600" autoplay controls muted loop playsinline></video>
  </center>
  <br>

  <h3>Art</h3>
  <p>Though art was not a primary focus, I leveraged built-in Unity tools for lighting and sound, as well as proprietary tools for animation and modeling, to create something more thematic than whiteboxed shapes. The intent was to create something that I could use to direct a fuller team of artists and sound designers, were those resources available, to develop the imagined space; a scarred and ruined factory, pierced with light, teetering on collapse into flames.

  <center>
    <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/transmechanism/giacobbi_transmechanism_powerline.png" width="600">
    <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/transmechanism/giacobbi_transmechanism_tank.png" width="600">
    <img src="https://github.com/VivianGiacobbi/portfolio/raw/main/docs/assets/transmechanism/giacobbi_transmechanism_truck.png" width="600">
  </center>
</details>
