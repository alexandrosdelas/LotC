# Update 7 [3.0.0] (2021-05-28)
590 changes

## Campaign
### Structure
- Replaced Prologue
- Changed Chapter 2 to Chapter 1
- Changed Chapter 3 to Chapter 2
- Merged Chapters 4 and 5 into Chapter 3
- New Chapter 4
- Replaced Interlude
- Changed Chapter 6 to Chapter 5
- Merged Prologue, Chapter 1 and Chapter 7 into Chapter 6
- New Interlude
- Changed Chapter 8 to Chapter 7
- Merged Chapter 9 and Epilogue into Chapter 8
- Removed Chapter 10

### Multiple maps
#### Gameplay
- Added more enemies on Normal and Hard difficulty
- Added neutral buildings to buy abilities and upgrades
- The Tattered Cloth is now a hero ability that restores 100/150/200 mana at the expense of 50 life
- Added dynamic skillshot abilities to many enemy units
- Stasis Traps are now also targeted as ground units
- Gold, lumber and food now carry over between maps
- Thrall gains some gold and lumber when not restored from game cache
- Wand of Lightning Shield can no longer be cast on self
- Removed creep experience reduction
- Removed food cost for all non-companion units
- Events are no longer triggered by spell effects
- Clarity Potion is now combat-consumable
- Clarity Potion now requires a target
- Increased range of Clarity Potion from 0 to 500
- Increased damage of Spears from 50 to 80
- Most items now drop when the carrier dies
- Immolation no longer damages neutral units

#### User Interface
- Removed unused objects in editor
- Updated campaign preview image
- Updated score screen image
- Updated loading screens texts
- Transmissions and cinematics are now played in queues
- Changed text in some transmissions
- Updated duration of some transmissions
- Changed color and text of leaderboards
- Updated many quest descriptions
- Removed many players from score screen
- Gold Mines are no longer displayed on the minimap
- Changed player color of Durnholde/Guards from Grey to Blue
- No longer overwrites player name
- Renamed Blackmoore's Keep to Durnholde Keep
- Renamed Frost Wolf to Frostwolf
- Renamed Shimmergalze Roast to Pig Roast

#### Audio/Visuals
- Removed unnecessary duplicated custom objects
- Updated camera movement for all cinematics
- Updated music during cinematics
- Stone Walls are now visible in the Fog of War
- Removed The Prophet from most scenes
- Changed unit type of Uthul to Grunt
- Increased scale of Snowsong from 1.0 to 1.1
- Changed RGB color of Snowsong to 255/200/200
- Fixed 3D sounds
- Redesigned frostwolf camp

### Heroes
#### Thrall
- Increased maximum level from 10 to 20
- Increased hero ability level skip from 2 to 3
- Decreased acquisition range from 600 to 200
- Increased food production from 0 to 5
- Decreased agility per level from 1 to 0.5
- Decreased intelligence per level from 3 to 1.5
- Decreased strength per level from 2 to 1
- Removed all traits
- Decreased repair gold cost from 425 to 100
- Decreased revive lumber cost from 100 to 0
- Decreased revive time from 55 to 10 seconds
- Thrall can now learn upgrades to improve himself or his companions
- New hero ability Tattered Cloth: Restores mana at the expense of life
- New hero ability Power Slash: Gain chance to deal area damage
- New hero ability Haste: Increases movement speed for some time
- New hero ability Dodge: Gain chance to dodge an attack
- New hero ability Combat Aura: Increases attack speed of all nearby friendly units
- Combat abilities can now be bought and upgraded in neutral buildings
- Normal combat abilities now have 5 levels
- Ultimate combat abilities now have 3 levels
- New ability Knockback: Damages, knocks back and stuns an enemy unit
- New ability Raging Strike: Move to target area and deal damage to all units in a line
- New ability Whirlwind: Deal area damage over time
- New ability Duel: Slow an enemy unit and increase ability damage to it
- New ability Ravage: Deal damage to target units over time
- New ability Earthshock: Now damages and slows enemies in a line
- New ability Ice Shard: Deal damage and slow enemies in a small area
- New ability Challenge: Deal area damage over time
- New ability Will of the Wilds: Transform enemy units in target area into critters
* Indestructible
  - Decreased cooldown from 90 to 50 seconds
  - Decreased mana cost from 100 to 90
- Rage: Removed
- Storm Bolt: Removed
- Earthshatter: Removed
- Raging Strike: Is now stopped when hero when hero is ensnared or stunned
- Changed unit name in black armor from Far Seer to Warchief
- Changed revive hotkey to W

#### Backpack
- New hero unit that helps Thrall with non-combat abilities
- Abilities, Upgrades and Companions: Allows improving combat abilities, researching upgrades and hiring companions
- Build Fire Pit: Allows activating combat abilities, heals all nearby units, allows Cooking, burns lumber per second
- Crafting: Consumes gold and lumber to create various perishable items
- Cooking: Cooks small animals to gain temporary additional attribute points
- Looting: Increases amount of gold and lumber gained from slain enemies
- Inventory: Increases the inventory size of the Backpack

### Drek'Thar
- Decreases acquisition range from 1700 to 600
- Decreased death time from 20 to 2.1 seconds
- Decreased repair gold cost from 425 to 100
- Decreased revive lumber cost from 100 to 0
- Decreased revive time from 55 to 10 seconds
- Replaced Far Sight with Lightning Shield
- Decreased agility per level from 1.0 to 0.5
- Decreased intelligence per level from 3.0 to 1.5
- Decreased strength per level from 2.0 to 1.0
- Decreased damage of Chain Lightning from 85/125/180 to 80/120/160

### Hellscream
- Decreased agility per level from 1.75 to 0.87
- Decreased intelligence per level from 2.25 to 1.13
- Decreased strength per level from 2.0 to 1.0

### Doomhammer
- New model by Tauer
- Replaced Thorns Aura with Shockwave
- Changed hotkey of Thunder Clap from Q to W
- Increased movement speed from 250 to 300
- Resurrection no longer works on allied units
- Decreased damage of Thunder Clap from 60/100/140 to 50/80/110
- Decreased damage of Shockwave from 75/130/200 to 70/110/150
- Decreased damage increased of Battle Roar from 5/10/15 to 5/8/11
- Increased attack cooldown from 1.77 to 2.05
- Decreased agility per level from 1.75 to 0.87
- Decreased intelligence per level from 1.5 to 0.75
- Decreased strength per level from 2.25 to 1.13
- Decreased amount of resurrectable units from 6 to 5


### Units
- Slain enemies now always give gold bounty, sometimes lumber bounty
- Changed armor type of neutral buildings from Fortified to Large
- Changed life of neutral buildings to 75
- Increased inventory item capacity for veteran units from 2 to 6
- Enemy air units can now be hit by ground attacks
- Decreased attack range of enemy air units
- Veteran units can now use items
* Veteran Shaman
  - Changed hotkey of Purge from G to Q
  - Changed hotkey of Lightning Shield from L to W
  - Changed hotkey of Bloodlust from B to E
* Veteran Raider
  - Changed hotkey of Ensnare from E to Q
  - Increased armor from 0 to 2
* Dog
  - Increased hit points to 100
  - Decreased speed of Dog from 400 to 270
  - New ability Rush: Increases movement speed for a short duration
  - New ability Howl: Decreases atack damage of nearby enemies by 20%
- Gnoll: Increased hit points from 100 to 240
* Gnoll Poacher
  - Increased hit points from 100 to 240
  - Increased damage base from 10 to 12
* Gnoll Assassin
  - Increased hit points from 150 ro 320
  - Increased damage base from 15 to 20
* Gnoll Warden
  - Increased hit points from 170 ro 330
  - Increased damage base from 17 to 20
* Gnoll Brute
  - Increased hit points from 180 ro 400
  - Increased damage base from 12 to 13
* Gnoll Overseer
  - Increased hit points from 230 to 750
  - Increased damage base from 20 to 23
* Murloc Hut/Gnoll Hut
  - Changed armor type from Fortified to Large
  - Decreeased hit points from 125 to 75
- Golems are no longer immune to magic
- Removed Shadow Meld from Spearthrower
- Elite Knights now benefit from upgrades
- Increased hit points and damage of most types of enemies
- Catapults can no longer attack walls
- Changed hit visuals for Moving Fire
- Priests can no longer heal themselves
- Decreased hit points of Frostwolf from 1000 to 700
- Changed hotkey of Roar from R to Q

## Prologue
- Replaced Prologue with scenes from old Chapter 1
- Renamed to "Among the Dead"
- Death sounds are now played during cinematic

## Chapter 1
### Gameplay
- Increased map size from 96x64 to 128x96
- Decreased experience rate from 120%/75%/70% to 40%
- Increased maximum level to 4
- The glaive can no longer be selected
- Changed damage radius of glaive from 144 to 96
- Turned day/night cycle on
- Removed quest "Good, Bad and Orc"
- Added new quest "Remember the Foxtons"
- Added new quest "Remember Jaramin"
- Added new quest "Remember Sergeant"
- Added new quest "Remember the Orc"
- Added new areas for optional quests
- Removed most Question Mark items for optional quests
- Time of day will no longer change until meeting Taretha
- Taretha's Letter now increases intelligence when used

### User Interface
- New player "Vermin"
- Renamed item "Remember Jaramin Skisson" to "Remember Jaramin"
- Renamed player "Citizens" to "Durnholde"
- Renamed player "Guards" to "Alliance of Lordaeron"
- Increased level of Sergeant from 1 to 5

### Audio/Visuals
- Redesigned Durnholde
- Removed various visibility modifiers
- Reduced amount of texture flickering
- Removed some water sound regions
- Foxtons cinematic: Replaced The Prophet with additional scene
- Sergeant cinematic: Replaced War Stomp with Earthshock
- Orc cinematic: The orc now fights back

### Quests
#### Champion of the Arena
- Increased number of enemies that drop runes
- Can no longer exit a fight
- The map is now lost if Thrall dies outside the arena
- No longer creates a Tome of Experience after an optional cinematic
- Some footmen will now change positions after beating opponents
- Quest requirement is now properly marked as completed
* Soldiers
  - Changed dialog button to "Soldiers"
  - Replaced a footman with a Knight
  - Decreased base damage of footmen from 15 to 13
  - Decreased life of footmen from from 500 to 475
  - Removed Flame Strike
  - Moved Net closer to Thrall
*  Troll
  - Removed Sentry Ward, Stasis Trap Wards, Bloodlust and Trueshot Aura
  - Decrease hit points of Healing Ward from 40 to 30
  - Replaced most Trolls with Spiders
  - Added spikes that can damage any unit
  - Decreased number of charges for Spears from 4 to 3
* Bandits
  - Redesigned area
  - Giant Lizard is now vulnerable
  - Increased collision size of Giant Lizard from 0 to 60
  - Decreased hit points of Giant Lizard from 3000 to 1200
  - Replaced scripted with normal attack behaviour for Gianz Lizard
  - Removed automatic trample damage by Giant Lizard
  - Increased acquisition range of Giant Lizard from 500 to 1200
  - Increased damage base of Enforcers from 10 to 12
  - Increased hit points of Enforcers from 550 to 600
  - Must now also slay the Giant Lizard to win
  - Added an Assassin on Hard difficulty
  * Wizards
  - Redesigned area
  - Added an Elevator to reach the lower enemy
  - Replaced Dwarves with Wizards
* Ogre
  - Fixed timing of Glaive damage
  - Added Hero Glow to the Ogre Gladiator
  - Increased hit points of Ogre Gladiator from 1200/1200/1300 to 1500/1500/1700
  - Increased movement speed of Ogre Gladiator from 170 to 220
  - Increased damage base of Ogre Gladiator from 15/15/17 to 17/17/20
  - The Glaive now only drops a Rune of Lesser Healing every third time
  - Increased Glaive damage to Ogre from 0 to 30

## Chapter 2
### Gameplay
- Increased map size from 96x96 to 128x128
- Added some areas from Chapter 4
- Moved the dog northeast
- Finding the dog now unlocks a new spell for Thrall
- Moved a child southeast
- Increased maximum level from 3 to 7
- Added new quest "Scouting"
- Added new quest "Self-improvement"
- Added new quest "Smith Will Suffice"
- Added new quest "Chuck Wood"
- Decreased experience rate from 120/80/75% to 40%

### User Interface
- New player "Footer's Gang"
- New player "Murlocs"
- New player "Wildlife"
- Renamed player "Guards" to "Alliance of Lordaeron"
- Only the current active main quest is now marked as failed when the map is lost
- Renamed Woman to Villager
- Player "Civilians" is now hidden in the post-game score screen

### Audio/Visuals
- Increased time of day speed from 0% to 50%
- Added visibility modifiers around waterfalls
* Outro cinematic
  - Changed names of human soldiers
  - Changed player color of soldiers from Teal to Grey
  - Renamed Expedition Knight to Captain

### Quests
#### Escape
- Merged quests "The Gate" and "Escape"
- Thrall will no longer start with reduced health
- Moved starting area to north
- Replaced Switches with Captains
- Decreased Gold Bounty of Mortar Team
- Removed Storm Bolt hint
- Removed Cloak of Shadows
- Removed Murlocs visibility modifier
- Added Rock Chunks at Murlocs
- Scared villagers are now removed when entering a house
- Added visibility modifier to the camp exit

#### Letters for a Friend
- Changed quest requirement to "Collect Taretha's Letters"
- Replaced reward Manual of Health with Research Ultravision
- Quest now starts with 1 of 3 Collected
- Replaced experience gain of Letters with temporary movement speed bonus

#### Good Boy
- Created optional quest for the Dog
- Moved the dog north
- Finding the dog now unlocks a new companion
- Dog can now leave Durnholde

#### Into the Wild
- Renamed quest "Silence Before the Storm" to "Into the Wild"
- Removed quest requirement "Find a place to rest"

## Chapter 3
### Gameplay
- Decreased map size from 128x128 to 96x160
- Merged areas from Chapter 4
- Increased maximum level from 4 to 10
- Changed experience rate from 100%/100%/70% to 40%
- Removed quest "Silence Before the Storm"
- Removed all Line of Sight Blockers
- Added new player Civilians
- Added Spell Immunity to all peons, Kelgar, Tom and Jerry

### User Interface
- Changed player Guards to Southshore Guards
- Added player Tarren Mill Protectors
- Added player Prisoners
- Added player Clanless Orc
- Kelgar now has a unique unit name
- Removed Goblin Shipyard minimap icon
- Decreased life of Romeo and Juliet from 100 to 50

### Audio/Visuals
- Added a global rain effect
- Redesigned distraction event
- Added an excklamation mark to the Backpack
- Increased life, hit point regeneration and attack cooldown for Tom and Jerry
* Intro cinematic
  - Removed original Intro cinematic
  - Merged Rest, Mocking and Kelgar cinematics to new Intro cinematic
- Goblins cinematic: Removed Trolls sequence
- Removed cinematic mode and cameras for Blind, BlindRescue and GoblinsReturn dialogues

### Quests
#### Honorless
 - Renamed quest "Brother, Where To?" to "Honorless"
 - Renamed item "Thrall's Belongings" to "Backpack"
 - Removed Magical Runes
 - Redesigned internment camp
 - Redesigned distraction sequence
 - Removed initial Health Stone
 - Added more minimap pings for quest requirements
 - Set time of all minimap pings to 5 seconds
 - Aspect of alliance to Guards now changes when Thrall enters/exits the internment camp
 - Removed Backtrack item
 - Knight in camp no longer patrols

#### Hunger
 - Merged quests "Food" and "The Exit"
 - Replaced leaderboard for Food items with quest updates
 - Removed all Magical/Glowing Runes
 - Renamed "Water" to "Vegetables"
 - Food items no longer grant experience
 - Food items now restore 50 hit points, 25 mana and increase movement speed
 - Removed minimap pings for food items

#### Volbir and Bolvir
  - Replaced Trolls and Murlocs with Gnolls
  - Added enemy heroes

#### Revenge of the Wolves
 - Added quest update message
 - Replaced Cages with Beast Cages
 - Quest is now discovered when nearing a Beast Cage
 - Replaced trolls with humans and gnolls

#### The Blind Family
 - Can now control the Blind Woman
 - Must now use the Blind Woman to rescue the children
 - Decreased number of children from 4 to 3
 - Decreased sight range of Jimmy, Timmy, Little Daniel and the Blind Woman from 600 to 64
 - Blind children now have shared vision towards the player

#### The Dark Wizard
 - Renamed quest "The Bandit Leader" to "The Dark Wizard"
 - Changed quest requirement to "Slay the Dark Wizard"
 - Replaced bandits with undead

## Chapter 4
### Gameplay
- The interlude is now a fully playable map
- The Blood Elf becomes vunerable if he enters the Flame Strike area

### Audio/Visuals
- Changed terrain fog from Pink to Light Blue
- Outro cinematic: Hellscream will no longer drop the Tattered Cloth


## Chapter 5
### Gameplay
- Decreased map size from 192x160 to 192x128
- Redesigned map layout
- Increased maximum hero level from 6 to 14
- Increased hero level of Drek'Thar from 10 to 14
- Decreased experience gain to 75%

### User Interface
- New player Crushridge Tribe for all ogres
- New player Wildpaw Tribe for all gnolls
- Removed Tattered Cloth hint
- Renamed Baby Orc to Orc Child

### Audio/Visuals
- Replaced Grom cinematic with simple dialogue
- Replaced Taretha cinematic with simple dialogue
- Replaced all cinematics for optional quests with simple dialogues
- Restructured some cinematics

### Quests
#### Cold and Alone
- Increased Thrall's sight radius from 400 to 1800/1200
- Removed Glowing Runes
- Replaced cold weather mechanic areas that damage all units
- Removed most runes dropped by enemies

### Alterac Cubs
- Changed quest giver from Raider to Palkar
- Changed quest requirement to "Rescue all Frostwolf Cubs (x of 9 Rescued)"
- Removed quest requirement "Meet with the Raiders"
- Removed quest requirement "Enter the Gnoll Camp"
- Removed quest requirement "Two Raiders must survive"
- Removed destructible rocks
- Replaced Frostwolf Cubs with Beast Cages
- Decreased collision size of Frostwofl Cub from 32 to 8

#### Smash
- Renamed from "The Ogres" to "Smash"
- Replaced all quest requirements with "Destroy the Barracks/Blacksmith/Town Hall"
- Replaced Death Towers with Guard Towers
- Added barrels of explosives

#### The Warlock
- New main quest

#### Lord of the Alliance
- Renamed from "The Book" to "Lord of the Alliance"
- Is now an optional quest
- Changed quest requirements to "Obtain/Return the Book"
- The Book can now be dropped
- Removed minimap ping
- Replaced Grunt with Shaman
- Changed visuals for static flame traps

#### These Pigs
- Renamed from "These pigs!" to "These Pigs"
- Is now an optional quest
- Changed owner of pigs to player Neutral Passive

#### Visions
- New optional quest

#### Lumberman
- Bundles of Lumber can no longer be selected or picked up manually
- Runes of Speed no longer count towards collected Bundles of Lumber
- Increased hit points of Ogre Pinky from 400 to 800
- Increased scale of Ogre Pinky from 0.8 to 1.0
- Decreased selection scale of Ogre Pinky from 1.2 to 1.0

#### These Pigs
- Renamed from "These Pigs!" to "These Pigs"
- Is now an optional quest
- Removed quest requirement "Go to the pigs' breeding place..."
- Changed quest requirement to "Obtain the Pig Catcher"
- Changed quest requirement to "Don't let 5 pigs escape"
- Removed vision of playfield
- Pigs now share vision with the player
- Removed minimap ping
- Renamed Net to Pig Catcher
- Changed Pig Catcher description and tooltip
- The Pigs Escape music now only plays once
- A sound effect is now played whenever a pig is approaching
- Pigs now stop spawning 10 seconds before the end of the timer
- Can now be restarted when lost
- The Pig Catcher can now be dropped

#### Lord of the Alliance
- Renamed from "The Book" to "Lord of the Alliance"
- Is now an optional quest

## Chapter 6
### Gameplay
- Increased map size from 128x160 to 192x160
- Added new quest "The Spirits"
- Added new quest "Spirit of Fire"
- Added new quest "Spirit of Earth"
- Added new quest "Spirit of Air"
- Added new quest "Spirit of Water"
- Added new quest "Spirit of the Wilds"
- Added new quest "Frostwolf Exile"
- Added new quest "Frostwolf Defiance"
- Replaced all cinematics for Spirit quests with simple dialogues
- The game is no longer paused when completing a quest
- User selection is no longer cleared when completing a quest
- Increased maximum level from 7 to 16

### Interface
- Removed dialog to select a Spirit quest
- Renamed "Wandering stranger" to "Stranger"
- Renamed Rune of Lesser Resurrection to Rune of Spearthrower

### Audio/Visuals
- New model for Spirit of Air by Himperion
- New model for Spirit of Earth by Amdor
- Removed shadow from patrolling fire
- MeetFrostwolves cinematic: Durotan and Draka are no longer present outside the cinematic
- DefianceEnd cinematic: Doomhammer's Guard will no longer move

### Quests
#### The Stranger
- Renamed from "The Wandering Stranger" to "The Stranger"
- Removed items
* Stranger
  - Replaced Unholy Aura with Shockwave
  - Replaced Reincarnation with Leap
  - Decreased movement speed from 320 to 200
  - Increased attack cooldown from 2.1 to 3.2
  - Changed team color to match owning player
  - Increased level from 10 to 20

#### Gift of Fire
- Renamed from "Spirit of Fire" to "Gift of Fire"
- Changed to optional quest
- Redesigned area
- Quest no longer restarts if Thrall dies
- Removed all friendly and enemy units
- Changed quest requirement to "Obtain the Gift of Fire"
- Thrall no longer gains Immolation
- Removed area visibility
- Removed leaderboard
- Increased fire trap damage from 20/30/40 to 60/90/120
- Decreased rate of fire trap damage

#### Gift of Earth
- Renamed from "Spirit of Earth" to "Gift of Earth"
- Changed to optional quest
- Redesigned area
- Changed quest requirement to "Obtain all Gem Stones"
- Changed quest icon
- Quest no longer restarts if Thrall dies
- Replaced area visibility with shared enemy visibility
- Decreased maximum elevator height to 2
- Elevator movement is no longer random
- Decreased number of keys from 8 to 7

#### Gift of Air
- Renamed from "Spirit of Air" to "Gift of Air"
- Changed to optional quest
- Redesigned area
- Changed quest requirement to "Obtain the Gift of Air"
- Changed quest icon
- Thrall no longer gains Far Sight
- The camera will no longer pan when hit
- Removed hint
- Tornado movement is now less random
- Tornados can no longer be selected
- Decreased area visibility
- Tornados are now knocking back
- No longer resetting player units when touching a Tornado
- Torandos now deal damage
- Decreased hit box of Tornado from 144 to 96
- Decreased wait time for tornados from 3.5/5.0/6.0 seconds to 3.5/3.5/5.5 seconds
- Removed some tornados on Normal and Easy difficulty

#### Gift of Water
- Renamed from "Spirit of Water" to "Gift of Water"
- Changed to optional quest
- Changed quest requirement to "Slay all enemies"
- Changed quest icon
- Removed Fountain of Health
- Removed all items dropped by enemies
- Redesigned area
- Quest no longer restarts if Thrall dies
- Thrall no longer gains Chain Lightning
- Fixed movement of tree logs
- Decreased tree log damage from 100/150/200 to 70/110/150
- Decreased speed of tree log from 500 to 500/400/300
- Increased acquisition range of all enemies from 150 to 200
- Increased life of all enemies
- Increased damage of all enemies
- Increased time interval for tree log damage
- Replaced area visibility with shared tree log visibility
- Tree log no longer damages invulnerable units

#### Gift of the Wilds
- Renamed from "Spirit of the Wilds" to "Gift of the Wilds"
- Changed to optional quest
- Redesigned area
- Changed quest icon
- Can no longer go to the same cliff level as the stag
- Decreased scale of Stag from 2.0 to 1.5
- Stag now moves automatically when a player unit is nearby
- Quest no longer restarts if Thrall dies
- Replaced Ogre Warriors with Ogre Maulers
- Replaced area visibility with shared stag visibility
- Remove some Runes of Mana/Healing
- Changed hint text

#### Frostwolf Exile/Frostwolf Defiance
- Changed to optional quests
- Changed quest requirement to "Follow the path to Doomhammer"
- Redesigned areas
- Replaced ogres and trolls with gnolls and humans
- Replaced Electric Conduit with Howl of the Frostwolf
- Slain heroes are now resurrected automatically after some time
- Removed defeat condition
- Difficulty level now influences enemy unit spawn type at sheltered areas
- Changed quest icon
- Improved AI of Doomhammer's Guard
- Removed two sheltered areas
- Decreased time for sheltered areas by 10 seconds
- Increased scale of Gul'dan from 1.0 to 1.5
- Removed Tomes of Experience
- Changed hotkey of Breath of Frost to Q
- Changed hotkey of Mend to W
- Changed hotkey of Summon Sharptooth to E
- Decreased food cost of Sharptooth from 2 to 0
- Changed damage type of Sharptooth from Normal to Siege
- Changed Sharptooth description
- Increased damage of all trolls
- Added reincarnation to Durotan and Draka
- Collected items can now be used by Thrall
- Changed player name for trolls to Winterax Tribe
- Renamed Player 2 to Alterac
- Changed player color of Alterac to orange
- Increased starting level of Durotan and Draka from 5 to 6
- Changed levels of Exploding Trap from 0 to 1/2/3
- Increased Mend area of effect from 600 to 800
- New icon for Confuse
- Decreased stand duration of Stasis Trap from 150 to 30 seconds
- Decreased stun duration of Stasis Trap from 12 to 8 seconds
- Enemies no longer speak when dead
- Changed hotkey of Exploding Trap from W to Q
- Changed hotkey of Raging Strike from Q to W
- Removed hint to defeat all remaining units

## Chapter 7
### Gameplay
- Redesigned entire map
- New quest "Need More"
- New quest "Helping Hands"
- Increased maximum level from 8 to 18
- Decreased experience gain to 60%

### User Interface
- Renamed enemy players to "Alliance of Lordaeron"

### Audion/Visuals
- Outro cinematic: Removed Doomhammer burial scene
- Outro cinematic: Replaced foorman with Elite Knight

### Quests
#### Rebellion
- Changed quest title from "The Orcs' Rescue" to "Rebellion"
- Changed first quest requirement to "Destroy all Town Halls"
- Changed second quest requirement to "Rescue 100 Orcs"
- Changed third quest requirement to "Defeat Langston"
- Changed quest description and icon
- Hellscream is no longer present in the final fight

## Chapter 8
### Gameplay
- Added new quest "Blacmoore"
- Increased experience gain to 100%
- Removed quest "Old but Gold"
- Increased maximum level from 9 to 20
- Hellscream is no longer loaded from game cache
- Set hero level of Hellscream to 18
- Drek'Thar can now be controlled directly
- Set hero level of Drek'Thar to 18
- Increased hit points of Barracks from 1500 to 2500
- Increased hit points of Arcane Sanctum from 1050 to 2500
- Increased gold cost of all army upgrades
- Decreased lumber cost of all army upgrades
- Changed revive cost of all heroes to 100 gold
- Decreased revive time of all heroes
* Watch Tower
  - Increased hit points from 500 to 800
  - Increased hit points regeneration rate from 0 to 50
* Guard Tower
  - Increased hit points from 500 to 800
  - Increased base damage from 22 to 24

### User Interface
- Changed hotkey of Research Steel/Thorium/Arcanite Melee Weapons from M to Q
- Changed hotkey of Research Steel/Thorium/Arcanite Ranged Weapons from R to W
- Changed hotkey of Research Steel/Thorium/Arcanite Armor from A to E
- Changed hotkey of Shaman Adept/Master Training from H to A
- Changed hotkey of Research Berserker Strength from B to S
- New icon for Blackmoore by Sxar
- Updated credits
- Added credits message

### Audio/Visuals
- Removed some wait time during credits
- Updated units appearing for credits
- New model for Langston by Direfury
- Changed attack sound of Langston to Heavy Metal Bash
- Decreased movement speed of Taretha from 190 to 150

### Quests
#### Taretha
- Changed quest requirement to "Find Taretha"
- Removed quest requirement "Don't attack Durnholde"
- Removed time limit

#### Durnholde
- Added quest requirement "Defeat Langston"
- Added quest requirement "Defeat Sergeant"
- Added quest requirement "Destroy all Siege Towers"
- Added upgrade research system
- Removed Pillage upgrade for allied player
- Added Ranged Weapons upgrade for allied player
- No longer gains income from allied player
- Increased time between mimimap pings from 5 to 10 seconds
- Added more variations of towers
- Decreased food production of War Mill from 50 to 0

#### Blackmoore
- Removed a Ring of Protection from Blackmoore
- Added a Periapt of Vitality to Blackmoore