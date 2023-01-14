# BattleFleet Development

## Battle Mode

### <input type="checkbox" checked> Build functionality for progressing messages
### <input type="checkbox" checked> Show messages for repairs
### <input type="checkbox" checked> Show messages for switching
### <input type="checkbox" checked> Build functionality for docking
### <input type="checkbox" checked> Show initial message when entering Battle Mode
### <input type="checkbox" checked> Build functionality for Battle Cycles
### <input type="checkbox" checked> Build functionality for retreating
### <input type="checkbox" checked> Show message for attack used
### <input type="checkbox" checked> Show message for critical damage
### <input type="checkbox" checked> Show message for destroyed ship
### <input type="checkbox" checked> Build functionality to start with first available ship in Fleet at start of Battle
### <input type="checkbox" checked> Add Back Button for Fleet Status view
### <input type="checkbox" checked> Show messages for docking
### <input type="checkbox" checked> Show messages for retreating
### <input type="checkbox" checked> Show attack animated impact on stat bars
### <input type="checkbox" checked> Show repair animated impact on stat bars
### <input type="checkbox" checked> Create starfield particle effect
### <input type="checkbox" checked> Create placeholder Idle animation
### <input type="checkbox" checked> Show attack VFX
### <input type="checkbox" checked> Show attack VFX conditionally on if landed hit
### <input type="checkbox" checked> Show repair VFX
### <input type="checkbox" checked> Disable attacks if Weapons are disabled
### <input type="checkbox" checked> Disable retreat if Engines are disabled
### <input type="checkbox" checked> Show docking VFX
### <input type="checkbox" checked> Show ship destroyed VFX
### <input type="checkbox" checked> Fix cursor not showing up
### <input type="checkbox" checked> Build functionality for AI to switch to next ship
### <input type="checkbox" checked> Build functionality for AI to attempt repairs
### <input type="checkbox" checked> Build functionality for NPC's to build out quick fleet configurations
### <input type="checkbox" checked> Polish repair messages for partial and full repair
### <input type="checkbox" checked> Polish showing/hiding messages for AI switching
### <input type="checkbox" checked> Set Action Menu for all Human Player ships at start of Battle
### <input type="checkbox" checked> Review refactor notes
### <input type="checkbox" checked> Fix AI switch also triggering second AI switch action
### <input type="checkbox" checked> Fix AI attacking before player can switch
### <input type="checkbox" checked> Fix AI attack occuring after weapons are disabled
### <input type="checkbox" checked> Calculate shield vs hull damage
### <input type="checkbox" checked> Show VFX for shield vs hull damage
### <input type="checkbox" checked> Refactor probability for evasion to allow less punishment for players
### <input type="checkbox" checked> DO A BARREL ROLL on incoming attack
### <input type="checkbox" checked> Build system for one warning when ship is critically damaged per battle
### <input type="checkbox" checked> Weapon and Damage SFX
### <input type="checkbox" checked> Show engine damage
### <input type="checkbox" checked> Show weapon damage
### <input type="checkbox" checked> Build transition out/in of switched ships
### <input type="checkbox" checked> Model 1 ship of each type
### <input type="checkbox" checked> Refactor damage multipliers
### <input type="checkbox" checked> Refactor Attack Accuracy and Speed
### <input type="checkbox" checked> Build system for gaining experience and leveling up
### <input type="checkbox" checked> Build system for increasing stats when leveling up
### <input type="checkbox" checked> Build calculation for AI stats at level
### <input type="checkbox" checked> Build system for experience for ships engaged divided by damage inflicted/received
### <input type="checkbox" checked> Refactor messages to queue text, fire events on message consumption, and progress battle cycle on end of queue
### <input type="checkbox" checked> Remove messages in queue from destroyed ship to prevent firing after ship is destroyed
### <input type="checkbox" checked> Fix bug in "Calculate Experience for Destroyed Ship" where unable to access elements of updatedStats array
### <input type="checkbox" checked> Build experience bar
### <input type="checkbox" checked> Remove one critically damaged warning for AI
### <input type="checkbox" checked> Refactor message queue to include parameter for eventPlayerTarget
### <input type="checkbox" checked> Fix bug with fleet destroyed message not appearing
### <input type="checkbox" checked> Fix bug with FrontCam appearing inside mesh for second ship
### <input type="checkbox" > Check on FrontCam/BackCam Spring Arm collision settings
### <input type="checkbox" checked> Build system for dialogue
### <input type="checkbox" > Apply battle bonuses based on assigned officers

### <input type="checkbox" checked> Refactor HUD to be a base class for child HUDs
### <input type="checkbox" checked> Setup messages in HUD for roaming character
### <input type="checkbox" checked> Refactor AI character preview in roaming
### <input type="checkbox" checked> Refactor Players to use a base class for common logic
### <input type="checkbox" checked> Refactor Game Modes to use a base class for common logic
### <input type="checkbox" checked> Refactor non-fleet group ship to populate DT_npcships
### <input type="checkbox" checked> Fix npc using destroyed ship for next ship
### <input type="checkbox" checked> Remove defeated npc from Overspace Location spawning
### <input type="checkbox" > Fix XP bar to show current XP on load

## Roaming Mode
### <input type="checkbox" checked> Setup Basic Dialogue System for Characters
### <input type="checkbox" checked> Clean up Character HUD
### <input type="checkbox" checked> Create Basic Inventory System
### <input type="checkbox" checked> Create Inventory Category Screens
### <input type="checkbox" checked> Connect Character Preview to Character
### <input type="checkbox" checked> Save customization choices
### <input type="checkbox" checked> Setup Basic Selling/Buying System for Characters
### <input type="checkbox" checked> Setup Selling/Buying amount modal
### <input type="checkbox" > Setup getting aggregate total amount for amount modal
### <input type="checkbox" checked> Setup Currency for Characters
### <input type="checkbox" checked> Setup Crew purchasing
### <input type="checkbox" checked> Setup Officer purchasing
### <input type="checkbox" checked> Setup adding Officer to Fleet
### <input type="checkbox" checked> Setup showing assigned Officers in Fleet
### <input type="checkbox" checked> Setup swapping assigned Officers in Fleet
### <input type="checkbox" checked> Setup assigning unassigned Officers in Fleet
### <input type="checkbox" checked> Refactor Officer selection menu to show Officer Traits
### <input type="checkbox" checked> Setup unassigning assigned Officers in Fleet
### <input type="checkbox" checked> Setup repair ships in Fleet
### <input type="checkbox" checked> Setup crafting schemas
### <input type="checkbox" checked> Setup crafting multiple items from schema
### <input type="checkbox" checked> Setup procedural Character Dialogue Icons
### <input type="checkbox" checked> Fix bug with Officer outline
### <input type="checkbox" checked> Research 2 weapon parts
### <input type="checkbox" checked> Flesh out resources, parts, blueprints for 2 weapon parts
### <input type="checkbox" checked> Refactor Inventory save to only updated inventory categories
### <input type="checkbox" checked> Refactor Inventory to include Weapon category
### <input type="checkbox" checked> Setup hangar menu (weapons equip)
### <input type="checkbox" > Setup Officer assigning in hangar menu
### <input type="checkbox" > Refactor saving inventory in BP_Character to save sequential indexes (Save Inventory)
### <input type="checkbox" checked> Refactor saving inventory in W_InventoryCategory, W_FleetStatus to use Game Mode Core Logic saving inventory
### <input type="checkbox" checked> Refactor saving ships in BP_RoamingCharacter, W_FleetStatus, BP_BattlePlayer to Game Mode Core Logic saving ships
### <input type="checkbox" checked> Refactor saving officers to Game Mode Core Logic saving officers
### <input type="checkbox" checked> Refactor saving officer name to Game Mode Core Logic saving officer name
### <input type="checkbox" checked> Refactor saving customizations to Game Mode Core Logic saving customizations
### <input type="checkbox" checked> Refactor saving overspace player locations to Game Mode Core Logic saving overspace player locations
### <input type="checkbox" > Refactor removing inventory items in BP_Character to Game Mode Core Logic removing inventory items
### <input type="checkbox" checked> Setup leaving station
### <input type="checkbox" > Fix bug removing all items from category for NPC not using correct JSON syntax (extra comma)


## Overspace (Exploration) Mode
### <input type="checkbox" checked> Create pawn for overspace game mode
### <input type="checkbox" checked> Create AI pawn for overspace game mode
### <input type="checkbox" checked> Allow AI Evasion
### <input type="checkbox" checked> Allow AI to engage in Battle Mode
### <input type="checkbox" checked> Setup Station docking
### <input type="checkbox" checked> Setup saving Overspace layout to reload
### <input type="checkbox" checked> Refactor NPC Fleets to group by NPC Name
### <input type="checkbox" checked> Setup Basic NPC procedurally generated spawning
### <input type="checkbox" checked> Add radar
### <input type="checkbox" checked> Refactor BP_DockBase to not inherit from BP_CharacterCoreLogic (see BP_ExitBase)
### <input type="checkbox" checked> Add multiple types of npc fleets (Hostile/Passive/Cowardly)
### <input type="checkbox" checked> Add Friend/Enemy/Unknown HUD tagging
### <input type="checkbox" checked> Refactor radar for tracking large stationary objects
### <input type="checkbox" checked> Change radar indicators based on perceived threat
### <input type="checkbox" checked> Add scanner info for Overspace Player Target
### <input type="checkbox" checked> Add scanner schema info for scanned object
### <input type="checkbox" checked> Refactor Scanner Schema Info into Scanner Info
### <input type="checkbox" checked> Refactor Scanner Schema Info to check Codex for discovered entries
### <input type="checkbox" checked> Add Codex entry for ships after encounter with ship
### <input type="checkbox" checked> Refactor scanner to clear when scanning new target
### <input type="checkbox" checked> Refactor HUD Marker to resize on target
### <input type="checkbox" checked> Add scanner info for Overspace Docking Target
### <input type="checkbox" checked> Add Codex entry for bases after encounter with base
### <input type="checkbox" checked> Add POI Marker in Planet Menu
### <input type="checkbox" checked> Add planet menu for selecting POI
### <input type="checkbox" checked> Add planet scanning
### <input type="checkbox" checked> Add mission menu for selecting mission POI
### <input type="checkbox" checked> Add basic mission execution using mission events
### <input type="checkbox" checked> Add diminishing chance to occur for repeating mission events
### <input type="checkbox" checked> Add health for Officers
### <input type="checkbox" checked> Add event consequences
### <input type="checkbox" checked> Add event report showing summary of events and outcomes
### <input type="checkbox" checked> Refactor Add Inventory item from BP_Character to GM Core Logic
### <input type="checkbox" checked> Save mission event consequences on mission finish
### <input type="checkbox" > Add POI degredation or single attempt
### <input type="checkbox" > Add Codex entry for Codex POI
### <input type="checkbox" checked> Add Trader event to spawn trader
### <input type="checkbox" checked> Add Trade menu to Overspace player
### <input type="checkbox" > Fix intermitent Trader engaging with target
### <input type="checkbox" checked> Add Abandoned Cargo event
### <input type="checkbox" > Add Cargo Container(s) after battle

# Action Items

## Exploration
> ## Star Systems
>> ## Planets
>> ##### Bases can be located on a planet (Done)
>> ##### Explorable points of interest can be located on a planet (Done)
>> ##### Several expeditions can be located on a single planet (Done)
>>> ## Expeditions
>>> ##### Inspiration from Crying Suns away missions
>>> ##### Viewed from bridge of *flagship*
>>> ##### Monitors reports from away team (Done)
>>> ##### Field Report Scan shows items of interest in forming an away mission, including:
>>> - ###### Points of Interest in area (Done)
>>> - ###### Points of Danger in area (Done)
>>> - ###### Objectives
>>> ##### Instead of showing probabilities, focus on highlighting POIs and PODs:
>>> - ###### Mineral Deposits (POI - Geologist/Scavenger) (Done)
>>> - ###### (Medical, Military, Geological, etc.) Facility (POI/POD - Geologist/Demo/Technician/Linguist/Researcher/Scavenger/Trader/Mechanic)
>>> - ###### (Mercenary, Military, Pirate*) Forces (POD - Medic/Weapon/Scout/Linguist/Tactician/Trader)
>>> - ###### (Local, Refugee, Nomadic, Abandoned) Settlement (POI/POD - Medic/Weapon/Scout/Linguist/Researcher/Scavenger/Tactician/Trader/Mechanic)
>>> - ###### (Derelict, Damaged, Abandoned) Ship (POI/POD - Medic/Demo/Tech/Weapon/Scout/Linguist/Researcher/Scavenger/Tactician/Trader/Mechanic)
>>> ##### ~~Shows probability report on away team's success, which includes:~~
>>> - ###### ~~Officer survival chance~~
>>> - ###### ~~Resources extraction chance~~
>>> - ###### ~~Crew survival chance~~
>>> ##### Semi-random events that test away team's skillset
>>> ##### Can find the following items:
>>> - ###### New Officer to recruit
>>> - ###### New Crew to add to ship
>>> - ###### Raw resources to add to cargo hold (Done)
>>> - ###### Ship parts to add to cargo hold (Done)
>>> - ###### Ship Part blueprints to add to Starship Compendium
>>> - ###### Mission specific items to add to cargo hold
>>> - ###### Ship blueprints to add to Starship Compendium
>>> ##### Expeditions can be randomly generated or story specific
>>> ##### Up to 2 Officers can be assigned to an away mission
>>> ##### ~~Can extract away team at different expedition checkpoints~~
><br><br/>
>> ## Officers
>> ##### Aptitude (Average, Exceptional, Paragon) - max trait slots (2, 3, 4) (Done)
>> ##### Traits (Medic, Geologist, Demolition Specialist, Technician, Weapon Specialist, Scout, Linguist, Researcher, Scavenger, Tactician, Trader, Mechanic) (Done)
>> ##### Provides event successes if assigned to away party, bonuses if assigned to a ship, bonuses if assigned to a shoreleave party (Ice-box)
><br><br/>
>> ## Bases
>> ##### Inspiration from Mount & Blade towns
>> ##### Can be found orbiting Planets or other interstellar bodies
>> ##### Have alignments to different factions
>> ##### Marketplaces for resources, parts, blueprints, ships, and misc items (Done)
>> ##### Can recruit Crew and Officers (Done)
>> ##### Can roam the galley to interact with patrons (small character roamable room) (Done)
>> ##### Can change faction alignment* (Galactic Conquest Ice-box)
>> ##### Can engage in Battles* (Galactic Conquest Ice-box)
>> ##### Can generate resources for owner* (Galactic Conquest Ice-box)
>> ##### Can be upgraded by owner to generate additional resources for owner* (Galactic Conquest Ice-box)
>> ##### Can be upgraded by owner to provide additional defenses against fleets* (Galactic Conquest Ice-box)
><br><br/>
>> ## Anomolies
>> ##### Inspiration from Rebel Galaxy anomalies
>> ##### Distress signals
>> ##### Derelict ships/bases
>> ##### Secret ships/bases
>> ##### Ambushes
>> ##### Abandoned cargo
>> ##### Decrypted messages
>> ##### Nebula
>> ##### Asteroid Field
>> ##### Trader (Done)
>> ##### Space storm

References:

[Pokemon Sword and Shield](https://www.youtube.com/watch?v=TmWu-f6L0Mo)

[Star Wars Squadrons](https://www.youtube.com/watch?v=yGSkCalsisU)

[Star Wars](https://www.youtube.com/watch?v=T5W3TJtYa2E)

Species can be recruited as officers

Species can also be captured, less moral

Low moral officers can mutiny, sending ship to flee or join enemy

Antagonist: Space Vikings?