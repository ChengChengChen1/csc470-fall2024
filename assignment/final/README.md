Game Design Document: Path of the Knight
1. Game Overview Path of the Knight is a 3D action RPG where players control a knight, exploring the map and defeating bosses.
2. Core Mechanic: Players battle various monsters, each with unique attack styles and levels. Players must level up and defeat these monsters through melee attacks and skill use. Attacks have a 20% chance of dealing critical damage, causing a knockback effect. Similarly, monsters can also land critical hits and knock back the player.
3. Controls
* Move: Left mouse button to control direction.
* Camera: Adjust using mouse scroll wheel or A & D keys.
* Attack: Left mouse button.
* Skill: Right mouse button (tentative).
* Interact: Left mouse button.
4. Visuals
* Environment: Low-poly style. Unity Assets Store used: Low-Poly Simple Nature Pack by JustCreate for maps, and FREE Skybox Extended Shader by BOXOPHOBIC for skies.
* Character Design: Low-poly style using character assets by Dungeon Mason.
5. Audio Plan to add fitting sound effects for characters and background music (BGM).
6. UI
* Health Bar: Top-left corner displays the player's current health.
* XP Bar: Below the health bar, showing experience points.
* Text Window: Displays quest dialogue at the bottom of the screen.
7. Story/Theme The story follows Wangwang, a brave little dog knight. Once upon a time, in a beautiful kingdom, lived a courageous dog knight named Wangwang. Everyone loved Wangwang because he always helped others. One day, the kind old king told Wangwang about troubles in the kingdom—slimes and fierce orcs were attacking villagers. Wangwang set out to defeat these enemies and successfully restored peace to the kingdom.
8. Goals
* Minimum Goals:
    * Build a 3D low-poly map.
    * Set up a virtual camera to track the character and add post-processing and fog effects.
    * Implement basic character movement, animation, and camera controls.
    * Develop enemy AI with states like patrol and chase. Different enemies should have unique attacks and damage levels.
    * Implement player stats like health, defense, and attack. Include attack animations and knockback effects.
    * Create a complete game flow: defeat simple enemies before fighting the boss to win.
    * Add basic UI for health and skills.
* Expected Goals:
    * Multiple levels with unique designs.
    * Diverse enemy types and behaviors.
    * Player leveling system.
    * Scene transitions and save/load features.
    * Enhanced UI controls.
* High Goals :
    * Voiceovers for characters.
    * Inventory system for switching weapons.
9. Timeline
* Week 1:
    * Initialize project, set up Unity, and import assets.
    * Build the map with imported assets (terrain, vegetation, skybox).
    * Implement basic character movement (mouse for direction) and camera follow/adjustment (mouse scroll, A & D keys).
    * Add walking, running, and idle animations.
    * Set up player and enemy stats like health and attack power.
* Week 2:
    * Develop combat system: left-click for melee attack, right-click for skill (tentative). Add critical hit and knockback mechanics for both player and enemies.
    * Implement enemy AI with NavMesh for patrol and chasing. Include attack animations and damage calculations.
    * Design UI: health bar, XP bar, and dialogue box for quests and story.
    * Add visual effects using Cinemachine and post-processing (e.g., fog).
* Week 3:
    * Add sound effects for actions and battles. Choose background music.
    * Begin implementing scene transitions and save/load functionality.
    * Add advanced features if time permits.
