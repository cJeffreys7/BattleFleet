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
### <input type="checkbox" > Setup procedural Character Dialogue Icons
### <input type="checkbox" > Fix bug with Officer outline

# Action Items

## Exploration
> ## Star Systems
>> ## Planets
>> ##### Bases can be located on a planet
>> ##### Explorable points of interest can be located on a planet
>> ##### Several expeditions can be located on a single planet
>>> ## Expeditions
>>> ##### Inspiration from Crying Suns away missions
>>> ##### Viewed from bridge of *flagship*
>>> ##### Monitors reports from away team
>>> ##### Field Report Scan shows items of interest in forming an away mission, including:
>>> - ###### Points of Interest in area
>>> - ###### Points of Danger in area
>>> - ###### Objectives
>>> ##### Shows probability report on away team's success, which includes:
>>> - ###### Officer survival chance
>>> - ###### Resources extraction chance
>>> - ###### Crew survival chance
>>> ##### Semi-random events that test away team's skillset
>>> ##### Can find the following items:
>>> - ###### New Officer to recruit
>>> - ###### New Crew to add to ship
>>> - ###### Raw resources to add to cargo hold
>>> - ###### Ship parts to add to cargo hold
>>> - ###### Ship Part blueprints to add to Starship Compendium
>>> - ###### Mission specific items to add to cargo hold
>>> - ###### Ship blueprints to add to Starship Compendium
>>> ##### Expeditions can be randomly generated or story specific
>>> ##### Up to 2 Officers can be assigned to an away mission
>>> ##### Can extract away team at different expedition checkpoints
><br><br/>
>> ## Officers
>> ##### Aptitude (Average, Exceptional, Paragon) - max trait slots (2, 3, 4)
>> ##### Traits (Medic, Geologic, Demolition, Technical, Tactical, Reconnaissance, Linguistic, Researcher, Scavenger, Intuitive, Barter, Mechanic)
>> ##### Provides event successes if assigned to away party, bonuses if assigned to a ship, bonuses if assigned to a shoreleave party (Ice-box)
><br><br/>
>> ## Bases
>> ##### Inspiration from Mount & Blade towns
>> ##### Can be found orbiting Planets or other interstellar bodies
>> ##### Have alignments to different factions
>> ##### Marketplaces for resources, parts, blueprints, ships, and misc items
>> ##### Can recruit Crew and Officers
>> ##### Can roam the galley to interact with patrons (small character roamable room)
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
>> ##### Trader
>> ##### Space storm

References:

[Pokemon Sword and Shield](https://www.youtube.com/watch?v=TmWu-f6L0Mo)

[Star Wars Squadrons](https://www.youtube.com/watch?v=yGSkCalsisU)

[Star Wars](https://www.youtube.com/watch?v=T5W3TJtYa2E)

Species can be recruited as officers

Species can also be captured, less moral

Low moral officers can mutiny, sending ship to flee or join enemy

Antagonist: Space Vikings?