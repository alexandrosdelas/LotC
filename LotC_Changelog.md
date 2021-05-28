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


# Update 6 [2.2.0] (2017-12-25)
359 changes

## Campaign
### New map
- New chapter 2: "Gladiator"
- Play as Thrall during his time as a gladiator
- Relive Thrall's memories of his youth

### Multiple maps
#### Gameplay
- Heroes will now retain attribute bonuses and abilities when changing unit type
- Increased initial amount of mana for Veteran Shamans to 100%

#### User Interface
- Difficulty selection is now done with dialogs
- "Thrall must survive" is now displayed for main quests
- New text for some loading screens
- Renamed Lord Karramyn Langston to Langston
- Renamed Baby Thralls to Baby Orcs
- New icon for War Stomp by Blizzard Entertainment
- Renamed War Stomp to Earthshatter
- New icon for Draka by Alex Horley
- New icon for Doomhammer by Svetli
- Fixed scorescreen icons
- Renamed Elite Raider to Veteran Raider
- Renamed Elite Shaman to Veteran Shaman
- Renamed Elite Grunt to Veteran Grunt
- Changed hotkey of Spearthrower to P
- Added more information to the Sturdy War Axe

#### Audio/Visuals
- Removed unused imports
- Decreased scaling factor of Rage from 10/25/40% to 10/15/20%
- Changed player color of Frostwolf clan from red to light blue
- Changed weapon sound for Blackmoore from Bash to Slice
- Removed wait time for some cinematics
- Improved unit and camera movements for some cinematics
- Added some wait time before a cinematic can be skipped
- Changed duration of some transmissions
- Generated terrain shadows
- Improved terraining in some areas
- Removed blight in some areas
- Removed boundary in some areas
- Fixed water sound regions
- Changed model of Tattered Cloth to Treasure Chest
- New railroad models by xXm0rpH3usXx
- New model for Blackmoore by Sxar
- New model for Draka by PROXY
- New sound set for Draka
- New sounds for Thrall
- New model for Langston by Direfury
- New model for Elite Raider by Mister_Haudrauf
- New model for Elite Shaman by Cavman
- New model for Elite Grunt by Tauer
- Removed pupils in Thrall's portrait model
- Changed attack sound Elite Raider to Metal Medium Chop
- Changed sound set of Elite Shaman to Demoness
- ItemReceived sound effect is now played more often
- Shadow Meld is now properly disabled for cinematics
- Level up graphics are no longer visible when heroes are created

### Heroes
#### Thrall
- New ultimate ability Indestructible which increases damage and life regeneration
* New passive abilities (traits)
  - Warsong Fury: Increased movement speed and attack rate by 10% for every 10% life missing
  - Frostwolf Resilience: Heals 5% life every third time an ability is used
  - Blackrock Might: Spells cast restore up to 50% of their mana cost, based on maximum missing

### Items
- Decreased stats bonuses given by Tomes
- Increased hit points of all Ogres by around 20%
- Decreased damage bonus of Sturdy War Axe from 5 to 3
* Food
  - Now restores hit points and mana over time
  - Can now be used on allied units

## Chapter 1
### Gameplay
- Improved AI of Doomhammer's Guard
- Decreased number of enemies spawning at the sheltered areas
- Decreased experience gain from Tomes of Greater Experience from 500 to 400
- Removed a group of trolls
- Moved last helpful orc further to the north
- Now hides the dummy Slippers of Agility when loading the map

### User Interface
- Upkeep message is no longer displayed when the Intro cinematic is skipped
- Removed difficuly hint
- Quest requirement "Defend..." is now properly marked as completed
- Added transmissions when the allied orcs are attacking
- Changed name of unit-type for Draka from Warrior Mate to Warrior
- Added transmission by Doomhammer's Guard when the assassins attack
- Renamed Grunt to Doomhammer's Guard in the Outro cinematic
- Changed quest requirement to "Defend sheltered areas"

### Audio/Visuals
- Changed player color of Blackrock clan from purple to red
- Decreased walk animation speed for Durotan
- Changed player color of Tammis Foxton from Blue to Brown
- Removed all Horse sound effects in the Outro cinematic
- Added DuskWolf sound effect in the Outro cinematic
- Moved some corpses a bit closer to the center in the Outro cinematic
- The last Spearthrower is now removed for the Outro cinematic
- Confuse is now disabled for the Outro cinematic

## Chapter 3
### Gameplay
* Thrall
  - Can now be restored from game cache
  - Now starts at level 2 if not restored from game cache
  - Experience gain now stops at level 3
- New optional quest "Letters for a Friend"
- Swapped positions of a Tome of Intelligence with a Tome of Lesser Experience
- Replaced all Tomes of Lesser Experience with Thrall's Letters
- NPCs will now start patrolling at map start
- A villager will now move away from Thrall before finishing her transmission
- Replaced Sturdy War Axe with Shimmerglaze Roast

### User Interface
- Added more information to the loading screen
- The Cloak hint can no longer be displayed multiple times
- Changed image of quest "The Escape" to High Elf Female
- The StormBolt hint will now only appear if Thrall is attacked
- Removed "here" from a transmission in the Outro cinematic

### Audio/Visuals
- Modified Intro cinematic

## Chapter 4
### Gameplay
* Thrall
  - Now starts at level 3 if not restored from game cache
  - Increased experience gain at level 2 from 50% to 100%
  - Decreased experience gain at level 3 from 33% to 25%
  - Replaced temporarily dropped items with a single item
  - Fixed movement speed after entering the camp
- Removed The Prophet from map
- Removed a Tome of Strength
- Moved troll base to the west
- Moved pathing blockers to the west
- Replaced a Tome of Knowledge with a Tome of Agility
- The Goblin Shipyard can no longer sell ships
- Humans and trolls in the north will no longer be invulnerable
- Replaced Potion of Strength with Sturdy War Axe
- Replaced Tome of Agility with Food
- Can no longer kill the Blind Woman
- Fixed acquisition range of trolls

### User Interface
- Changed quest description of "Second Escape"
- Added quest requirement "Talk to the orcs" to quest "Second Escape"
- Renamed quest "Second Escape" to "Brother, Where To?"
- Changed quest requirement from "Find your belongings" to "Get Thrall's belongings"
- Removed hints about talking to orcs
- Added transmission about not leaving without items
- Added minimap pings
- Added more quest requirements to The Blind Family quest

### Audio/Visuals
- The Goblin cinematic will no longer play if a player skips directly to the Outro cinematic
- Added dialogues between imprisoned orcs and distracted guards
- The Mocking cinematic can no longer be skipped while its stopping
- Set Thrall's life to 100% for the Goblins cinematic
- The Blind children are now recreated for the BlindRescue cinematic
- Fixed music no longer playing after cinematics
- Changed music of some cinematics
- Thrall's buffs are now removed for the Blind cinematics
- Blackmoore will no longer move away in the Outro cinematic
- Added more sound effects in the Outro cinematic

## Chapter 5
### Gameplay
- Replaced a Tome of Intelligence+2 with a Tome of Agility
- Added aditional Rock Chunks
- Moved a Knight slightly to the north

### User Interface
- Added more information to the loading screen
- Changed vilage hints from "...another..." to "...different..."
- Quest requirement "Kill the Bandit Leader" is now properly marked as completed

### Audio/Visuals
- Moved Magical Rune behind Rock Chunks
- Removed Sleep effect from Thrall in Outro cinematic
- Tom and Jerry will stop fighting in the Outro cinematic

## Interlude
- The Tattered Cloth is now removed before the last scene

## Chapter 6
### Gameplay
- Frostwolves and Ogres will no longer attack each other at map start
- Thrall will no longer move if the Intro cinematic is skipped
- Moved starting position of Thrall to the north
- Moved position of Thrall after the Grom cinematic
- Moved position of Thrall after the Taretha cinematic
- Replaced Tome of Knowledge with a Manual of Health
- Thrall can no longer gain experience after gaining level 6
- Replaced Wands of Far Sight with Runes of the Watcher
- Removed Rejuvenation from Wendigo Shaman
- Replaced Mud Golems with Young Wendigos
- Replaced Mountain Giant with Wendigo Shaman on Normal and Easy difficulties
- Replaced Mountain Giant with Ancient Wendigo on Hard difficulty
- Pigs quest can no longer fail if already won
- Replaced Tomes of Knowledge with Tomes of Intelligence/Agility/Strength
- Replaced Tomes with Runes of Lesser Speed at Pigs quest
- Thrall will no longer take damage directly after being resurrected at the Book area
- Items left behind for the Book quest are now moved to Thrall when returning to the orc
- Added a Rune of Restoration at the Book area
- Replaced Belt of Giant Strength with Frostguard
- Replaced Healing Salve with Gauntlets of Ogre Strength
- Replaced Tome of Intelligence+2 with Food
- Replaced Potion of Lesser Invulnerability with Mantle of Intelligence
- Added Slippers of Agility
- Will no longer see the Pacman area when dying somewhere else
- Thrall's life and mana are now restored after the Pacman quest
- Thrall's life and mana are now restored when dying at the Book quest

### User Interface
- Increased level of Hellscream from 2 to 5
- The item "Lord of the Alliance" is now unsellable and unuseable
- Decreased time between minimap pings for some quests from 10 to 5 seconds
- Decreased level of Frostwolf Cubs from 2 to 1
- Changes to description of The Ogres quest
- Renamed Ogre Maulers to ogre Pinkys for the Pacman quest
- Added defeat condition "Thrall must survive" to The Frostwolves quest

### Audio/Visuals
- Will no longer hear a death sound at map start
- New music for the Drek'Thar cinematic
- Added more variation to music in cinematics
- Removed duplicate Frostwolf camp
- Added small delay before teleporting ensnared pigs
- Captured pigs will now longer be ensnared after being moved
- Decreased time until rescued Frostwolf Cubs are removed from 20 to 5 seconds
- Removed all buffs from Thrall in the Drek'Thar cinematic
- Raiders are now at th Rock Chunks before the RaidersMeet cinematic starts
- The Raider will no longer attack Thrall or Uthul in the Outro cinematic
- Removed all buffs from Thrall in the Outro cinematic
- Summoned units are now removed for the CubsWin cinematic
- Thrall will now always do Earthshatter in the Outro cinematic

## Chapter 7
### Gameplay
- Decreased map size from 192x160 to 128x160
- Increased experience gain at level 5 from 75% to 100%
* Fire
  - Moved position of a Spearthrower corpse
  - Added a Tome of Intelligence
  - Replaced Fire Beetles with Lava Spawns
  - Removed a Scroll of Mana
  - Removed a Wand of Chain Lightning
* Earth
  - Moved the Circle of Power to the west
  - Moved some Kobolds
  - Changed quest requirements
  - Will no longer create more enemies when going to the Circle of Power
  - Moved starting position of Thrall to the east
  - Added permanent visibility of the Iron Gate
  - Added a Tome of Strength
  - Earth Keys can now be picked up with a full inventory
  - Added 3 Kobolds
  - Increased damage and hit points of all Kobolds
  - Can no longer destroy the Earth Keys
* Air
  - Decreased speed of Hippogryphs from 400 to 150/200/250
  - Thrall will keep his abilities
  - Replaced Hippogryphs with invisible Tornados
  - Added Far Sight to Thrall
  - Removed time limit quest requirement
* Water
  - The tree logs will now move before the quest has started
  - Removed 12 Tree Logs
  - Tree Logs now move along the x-axis of the entire area
  - Increased speed of tree logs from 100 to 500
  - Position of tree logs will no longer be reset if Thrall dies
  - Slightly decreased damage area of tree logs
  - Fixed triggering of damage of tree logs
  - Added a Tome of Agility
  - Decreased number of Wands of Lightning Shield
  - Decreased number of Runes of Lesser Healing
* Wilds
- Will no longer create Tomes of Knowledge
  - The stag now moves automatically
  - Added 2 Boulder Towers
  - Added 3 Ogre Magi
  - Replaced of Runes of Restoration with Runes of Healing and Runes of Mana
  - Decreased acquisition rangeo g all Ogres to 150
  - Thrall is now invulnerable when the quest is won
* Doomhammer
  - Fixed bug preventing restart
  - Will no longer create more items at restart
  - Life and mana are now at 100% at (re)start
  - Items picked up will no longer affect the Frostwolves
  - Drek'Thar wil no longer create Healing Wards
  - Added 2 Claws of Attack+15 for Doomhammer on Hard difficulty
  - Added Ring of Protection+5 for Doomhammer on Hard difficulty

### User Interface
- Changed hotkey for quest abilities (e.g. Blink) from D to F
- "Thrall must survive" is now a proper defeat condition
- Fixed description for all Spirit quests
* Fire
  - Changed quest requirement to "Prevent the Great Hall from being destroyed"
  - Removed Envenomed Weapons and Shadow Meld from Spearthrowers
  - Added a leaderboard that shows the life of the Great Hall
  - Added hint about Immolation
* Earth
- Changed some dialogue
  - Removed hints about killing enemies and going to the Circle of Power
  - Added hint about Blink
  - Changed quest icon
- Air: Added hint about Far Sgiht and invisible Tornados
* Water
  - Renamed Log to Tree Log
  - Added hint about Chain Lightning
  - Can no longer select the Tree Logs
* Wilds
  - Removed the hint about hitting the stag
  - Changed quest requirement from "Use Feral Spirits..." to "Escort the Stag"
* Doomhammer
  - Will no longer fade out for the Doomhammer cinematic
  - Changed quest requirement to "Defeat the stranger"
  - The quest requirement will no longer be marked as completed

### Audio/Visuals
- New music for the Intro cinematic
- Snowsong and Thrall will now look at each other in the Intro cinematic
- Will no longer hide areas with visibility modifiers
* Fire
  - Fixed Spearthrower animations
  - Traps can no longer be heard during the Intro cinematic
* Earth
  - New model for Spirit of Earth by -Grendel
  - Decreased scale of some archways
  - Removed Circle of Power
  - QuestCompleted sound will no longer play twice
* Air
  - Removed special effects on Thrall in the Air cinematic
  - Thrall will no longer turn into a Tornado
- Doomhammer: Will no longer create more spectators at restart

## Chapter 8
### Gameplay
- Orcs can now be rescued by casting abilities
- Removed a Potion of Healing
- Added alternative way to discover the Elite quest
- Added multiple items as reward for completing the Elite quest
- Decreased level of Langston from 6/10/10 to 5/8/8
- New abilities for Langston
- Added some Riflemen and a Mortar Team to Thrall's Escape route
- No longer able to control Grunts after the Langston cinematic
- Reset ability cooldowns for Thrall and Hellscream after the Langston cinematic

### User Interface
- Renamed player 1 to The Horde
- Renamed player 4 to Warsong Clan
- Renamed quest "The Orcs' Rescue" to "The Green Storm"
- Changed quest descriptions for "Taretha" and "Durnholde"
- Changed owner of Drek'Thar to player 10 (Frostwolf Clan)
- Removed Barracks leaderboard
- Added more info to quest requirement "Destroy the Barracks"
- The Elite quest will now be marked as discovered properly
- Renamed quest "The Elite" to "Old but Gold"
- Changed quest requirement "Free the Elite Orcs" to "Free the Veteran orcs"

### Audio/Visuals
- Now waits 2 seconds before the first transmission in the Intro cinematic
- The Barracks is now healed after the Intro cinematic
- Langston will no longer play his death animation twice
- Removed hallucinations in the Outro cinematic
- Thrall will no longer be blocked in the Outro cinematic
- Drek'Thar will no longer cast Healing Ward in the Outro cinematic
- Decreased volume of some sound effects to 80% in the Outro cinematic
- Added some variation to the victory animations in the Outro cinematic

## Chapter 9
### Gameplay
- Drek'Thar will no longer drop the Staff of Teleportation
- Removed a Rune of Lesser Healing
- Removed a Scroll of Healing
- Gates are now invulnerable
- Added Langston to the enemy attack wave
- Added an Altar of Kings for Durnholde
- Moved the Blacksmith to the west
- Cages are now destroyed automatically in the "Getting Gladiators" quest
- Added Runes Bracers, Periapt of Vitality and Talisman of Evasion
- Removed The Prophet from the map

### User Interface
- Changed owner of Blackmoore to player 12
- Changed name of player 12 to "Lord of Durnholde"
- Renamed east Keep to Blackmoore's Keep
- Renamed optional quest "Elite Orcs" to "Getting Gladiators"
- Changed quest requirement and description for "Getting Gladiators"

### Audio/Visuals
- Changed color of player 10 (Expedition) to Dark Green
- Changed color of south Town Hall to player 9 for the Taretha cinematic
- Moved positions of Blackmoore and Langston to the south in the Intro cinematic
- Replaced Pig Farms with Farms
- Thrall is now hidden when he enters Durnholde Keep

## Chapter 10
### Gameplay
- Moved a foot switch to be unreachable by Thrall
- Increased damage base of Spiders from 9 to 12
- Decreased number of Runes dropped in the Spider area on Normal and Hard difficulties
- A gate will now close when approaching the Dark Wizard
- The Blood Mage will now become vulnerable when a sheep gets close
- Water Way Gate is no longer active until the Way Gate Control is destroyed
- Removed most Tomes of Experience
- Replaced two Tomes of Experience with Tomes of Greater Experience
- Replaced Tome of Agility with Tome of Strength
- Removed Tome of Strength
- Removed Potion of Healing
- Replaced Healing Salve with Rune of Mana
- Removed Rune of Greater Healing
- Replaced all Earth-Fury Tower items with Runes of Water Elemental
- Will no longer create multiple vision modifiers at the Sheep area
- Replaced Scroll of Protection with Rune of Restoration
- Added 4 Brigands at the Bandits area
- Moved first Sentry Wards item to the south
- First Sentry Wards item is now invulnerable
- Removed almost all Sentry Wards
- Items dropped for the Sentry Wards are now moved to the end of the Bandits area
- Sentry Wards item now has an infinite number of charges
- Increased cooldown of Sentry Wards from 0 to 10 seconds
- Increased mana cost of Sentry Wards from 0 to 25 mana
- Thrall will no longer lose his items for the end fight
- Reset ability cooldowns after the Endfight cinematic
- Thrall can no longer be damaged by fire after beating Blackmoore
- Increased spell damage blocked by Blackmoore from 33% to 50%
- Increased all attributes of Blackmoore by 2 on Normal difficulty
- Increased all attributes of Blackmoore by 5 on Hard difficulty

### User Interface
- Removed hint about using classic warrior skills
- Renamed Power Generator to Way Gate Control
- Removed the hint about Sky-Fury Towers
- Added tranmission about a deactivated Way Gate
- Removed life bars from Fires

### Audio/Visuals
- Thrall will no longer be moved at the Rock Chunks/Support Column
- Changed color of Water runes to light blue
- Changed color of Glaives runes to green

## Epilogue
- Will no longer destroy trees when razing Durnholde
- Moved all fire effects to manmande structures
- Hellscream will now move slightly when picking up the item
- Changed player color of some orcs to light blue
- Added some variation to the victory animations
- Restructured types of credits
- Updated all credits
- Added time to some cinematic fade outs
- Increased far clipping of some cameras



# Update 5 [2.1.0] (2016-05-07)
250 changes

## Campaign
### New maps
- New prologue "The Shadow Council"
- Old prologue "Live and Let Die" is now a playable map (see Chapter 1)

### Multiple maps
#### Gameplay
- Added variable difficulty levels
- Heroes now become invulnerable when a victory cinematic starts
- Increased hit points of Frost Wolves from 750 to 1000
- Removed defeat condition "Do not kill innocent people"
- Decreased stock start delay of Tome of Retraining, Scroll of Protection, and Scroll of Healing from 440 to 10 seconds

#### User Interface
- New loading screens
- Removed loading screen titles (Prologue, Interlude, Epilogue) from cinematic maps
- Changed hotkey layout for hero abilities to QWER
- Will no longer fade out when mission fails
- Decreased time between some minimap pings
- Fixed various typos

#### Audio/Visuals
- Music volume is no longer overriden via trigger
- Added more water sound effects
- New model for Durotan by Tauer
- New unit model for Thrall by Tenebrae
- New weapon model for Thrall by Sunchips
- Changed model of Tattered Cloth
- Fixed minor terrain issues
- New tracks from World of Warcraft for some cinematics
- Improved terrain and cameras for Frostwolf camp
- Improved various cinematics

### Heroes
#### Thrall
 - Decreased stun time of Storm Bolt on normal units from 5 to 4 seconds
 - Decreased stun time of Storm Bolt on heroes from 3 to 2 seconds
 - Decreased stun time of War Stomp on heroes from 2/3/4 to 1/2/3 seconds
 - Added Tattered Cloth item
 - No longer gains 100% experience from kills on every map
 - Can now learn Evasion before Chapter 9
 - Changed main attribute to Intelligence
 - Changed unit name from "Grunt" to "Gladiator"
 - Fixed description of Rage
 - Removed all buffs in some cinematics

#### Drek'Thar
- Drek'Thar: Removed inventory


## Chapter 1
### Gameplay
- Added playable content
- Play as Durotan and Draka
- New custom abilities

### User Interface
- Renamed Orc baby to Son of Durotan

### Audio/Visuals
- Different terrain and camera movement

## Chapter 2
### Gameplay
* Thrall
  - Changed starting hit points from 400 to 450/350/250
  - Will no longer stop at the Murlocs
- Added more enemies on Normal and Hard difficulty
- Removed an enemy on Easy difficulty
- The Prophet is now removed after the intro cinematic
- Increased night sight radius of Dog from 800 to 1800
- Increased movement speed of Dog from 260 to 400
- Removed most barrels and crates that do not contain items
- Vision with the dog is now shared when it tries to exit the village
- Added two Runes of Restoration
- Replaced a Tome of Experience with a Tome of Intelligence
- Replaced all Guard Towers with Scout Towers

### User Interface
- Added more info to the loading screen text
- Player 12 is now hidden in the score screen
- Renamed quest "The Escape" to "Escape"
- Removed transmission about Murlocs

### Audio/Visuals
- Replaced some trees with rocks
- Moved rain area
- Turned off day/night cycle

## Chapter 3
### Gameplay
- Added a hidden item at the start of the map
- Orcs and humans will no longer fight each other after the Kelgar cinematic
- Thrall will be moved to the secret exit after the Kelgar cinematic
- Two footmen will be ordered to attack-move into the internment camp after the Kelgar cinematic
- Thrall will now start with a Food item
- Removed some Runes
- Repositioned some enemy units and the Fountain of Health
- Removed a Forest Troll Hut
- Decreased target acquisition range of Murlocs from 500 to 200
- Replaced a Tome of Intelligence with a Tome of Agility
- Increased hit points of Timber Wolves from 300 to 400
- Bundles of Lumber are now invulnerable

### User Interface
- Thrall: Is now selected after the intro cinematic
- The final Forest Troll Warlord will no longer speak if he is dead
- Removed Thrall's transmission about an escape route
- Improved the hint after getting the objective to flee

### Audio/Visuals
- Thrall can no longer be moved at the start of cinematics
- Timber Wolves are now hidden for all cinematics
- Will no longer create a rain weather effect during the Rest cinematic
- Will now always set the time of day to 12 am when the Rest cinematic is skipped
- Time of day speed is now set to 50% and the map time starts at 8pm
- Removed untargetable Cages

## Chapter 4
### Gameplay
- Thrall: Will now start at level 4 if not restored from game cache
- Decreased experience gain from Food items from 40 to 30
- Removed True Sight from Shades
- Replaced Potions of Speed with Runes of Speed
- Replaced a Tome of Agility wih a Tome of Intelligence +2
- Riflemen and Assassins will no longer practice with the Archery Target
- Changed patrol route of a Rifleman
- Changed locations of some bandits
- Villagers no longer turn into Guards. Instead they flee from Thrall
- Armor upgrades are set to 1 for Player 9 (Guards) on Hard difficulty
- Added a Tome of Strength +2
- Replaced a Scroll of Protection with a Wand of Chain Lightning
- Trolls and humans will no longer fight each other before Thrall arrives
- Changed locations of some pathing blockers

### User Interface
- Fixed a bug that displayed the Swordsman Net tip too soon
- Added a transmission when trying to exit the village too soon
- Thrall is now selected after the cave sequence
- Renamed Bandit Leader to Rogue (transmission only)
- Player 3 (Citizens) is now hidden in the score screen
- Changed quest requirement to "Gather 10 food items"
- Added defeat condition "Thrall must survive"

### Audio/Visuals
- Changed sound effect to "failed" when Thrall dies
- Added initial fade out for Intro cinematic
- The Gate is now closed after the Rest cinematic

## Interlude
- The Grunts fighting Thrall will no longer walk away
- The Grunts fighting Thrall will face random angles when knocked out
- A Grunt will face Thrall after destroying the cage
- The Orc Warlock will no longer move to confront Thrall
- Will play a sound effect when Hellscream first appears

## Chapter 5
### Gameplay
- Thrall: Now starts at level 5 if not restored from game cache
- Changed damage to Thrall in starting area from 1 per 0.15 seconds to 6/8/10 per 1 second
- Disabled sleeping for all creeps
- Replaced Pigs in "Raiders vs Gnolls" quest with Frostwolf Cubs
- The map now ends in defeat when more than 2 Raiders die
- Replaced all Rock Golems with Elder Wendigos
- Added some Tomes to the starting area
- Decreased time for Pigs quest from 150 to 120 seconds
- Decreased number of pigs required to lose Pigs quest from 8 to 6
- Replaced the High Elven Barracks with an Orc Barracks
- When all catapults have been destroyed a new one is instantly created
- The Mountain Giant will now also drop a Rune of Restoration
- Replaced Wand of Mana Stealing with a Mana Stone
- Can no longer drop the item Lord of the Alliance
- The pigs in the breeding place are now invulnerable
- Removed a Healing Salve
- Replaced a Potion of Speed with a Rune of Speed
- Will now only remove Runes of Speed and Bundles of Lumber in the Pacman area
- Bundles of Lumber and Runes of Speed are now invulnerable
- Replaced a Scroll of Regeneration with a Tome of Intelligence +2
- Pigs' guard position is now ignored
- Decreased collision size of Spirit Pig from 16 to 1.5
- Increased life of Spirit Pig from 120 to 999
- Pigs entering hay area are now removed after 2 seconds

### User Interface
- Is now accessible by completing Chapter 4 as well as the Interlude
- New backstory for "Raiders vs Gnolls" quest
- Renamed quest "Raiders vs Gnolls" to "Alterac Cubs"
- Removed duplicate minimap pings
- Cubs Leaderboard now starts at 14 and counts down for each rescued cub
- Pillage is now disabled
- Removed the hint about repairing catapults
- Changed Pigs timer window title from "Help" to "Time Remaining"
- The item Lord of the Alliance is no longer marked as usable or sellable
- Renamed Pacman Ogre Maulers to Ogre Bashers
- Added a hint for the Pacman quest: There is no need to right-click each item
- Decreased selection scale of Spirit Pig from 2 to 1
- Pigs now belong to Player 3 (Pigs)
- Fixed bug mixing some names in cinematic transmissions

### Audio/Visuals
- Removed way to the Ogre camp
- Removed some blocking elements from the Ogre quest area
- Removed some Rock Chunks
- Replaced a Forest Troll Hut with an Ice Troll Hut
- Renamed Pacman Ogre Maulers to Ogre Bashers
- Added a hint for the Pacman quest: There is no need to right-click each item
- Will no longer show an Exclamation Mark on Uthul
- Blackmoore will now be removed when the intro cinematic is skipped
- Fixed bug when Thrall lost an item during the Frostwolf cinematic
- Thrall will no longer remain invulnerable during the Frostwolves cinematic
- Fixed a bug preventing the map from ending when skipping the Outro cinematic
- The fake Thrall in the MeetFrostwolves cinematic will now be properly removed
- Will now play normal game music when skipping the MeetFrostwolves cinematic
- Fixed Raiders ensnaring Cubs in CubsWin cinematic
- Fixed a bug ordering Ogres to run away in OgreTowers cinematic
- Will no longer reveal an area of the map after the Frostwolves cinematic
- Can no longer play the Outro cinematic twice
- Fixed sound regions
- Decreased height of Frost Traps

## Chapter 6
### Gameplay
- Thrall: Now starts with Evasion if not restored from game cache
- Replaced Grunts with Spearthrowers in Fire quest
- Removed some wait times when winning a Spirit quest
- Treelogs will now move immediately when the Water quest starts
- Removed wait time when Thrall dies during the Wilds quest
- Increased fire trap damage from 25 to 20/30/40
- Added some items for Doomhammer on Normal and Hard difficulties
- Removed Player 3 (Teal)
- Fixed a bug that caused the Elevator in the Fire quest to always cause damage
- Fixed a bug that prevented Thrall from being resurrected
- Changed locations of some enemies in the Fire quest
- Replaced all items in the Doomhammer fight with Runes of Healing/Mana
- Doomhammer will now try to pick items up instead of destroying them
- Increased time between item spawns in Doomhammer fight from 4 to 7 seconds
- Decreased time until Doomhammer tries to interact with an item from 4 to 2 seconds
- Removed damage effect from Fire elevator
- Can no longer fail the Air quest once Thrall has reached the target
- Moved starting positions of Thrall and Doomhammer in the fight
- Added some blocking elements to the Water quest

### User Interface
- Changed map title from "The Path of the Shaman" to "Path of the Shaman"
- Thrall (Tornado): Renamed Tornado to Thrall
- Quest Failed message will no longer appear multiple times when Thrall dies
- Changed hint to "The treelogs can damage Thrall when he gets too close."
- Changed hotkey for all unique Spirit abilities to "D"
- Removed level information from Chain Lightning and Feral Spirit
- Removed number of enemies in the Spirit of Water quest requirement
- The Earth Key Leaderboard will now appear 2 seconds earlier
- Changed Earth Hint to "...Go to the Circle of Power in the east to open the gate."
- Changed Water Leaderboard Value from "Left" to "Alive"

### Audio/Visuals
- Changed some snow cliffs to grass cliffs
- Replaced Summoner in Water cinematic with an Sea Elemental
- Removed all remaining Summoners
- All items on the ground will be removed when the Outro cinematic starts
- Removed Mission Failed sound effect
- Fire Elevator sound effect will no longer play after the Fire area is completed

## Chapter 7
### Gameplay
* Thrall
  - Now starts at level 6 if not restored from game cache
  - Attack is now ranged
- Orcs are now rescued by attacking their guards
- Removed some enemies on the way to the elite orcs
- Changed owner of the Town Hall to Neutral Passive
- Added defeat condition "Thrall must survive"

### User Interface
- Changed map title from "The End of a Legend" to "The Horde Awakens"
- Thrall: Decreased revive cost from 425 to 100 gold
- Thrall: Decreased revive time from 55 to 10 seconds
- Doomhammer: Changed display order of abilities
- Drek'Thar: Decreased target acquisition range to 200
- Renamed player Camp Guards to Guards
- The optional quest is now discovered 20 seconds after the Gate was destroyed
- Added a hint that Thrall can be revived at the Altar of Storms after the Gate was destroyed

### Audio/Visuals
- Replaced invulnerable trees with rocks
- All summoned units are now removed for the outro cinematic
- Removed a superfluous Drek'Thar in the outro cinematic

## Chapter 8
### Gameplay
- Game will no longer wait for enemy buildings to dissipate to complete the quest requirement
- Shared vision with Keep as soon as the quest requirement is active

### User Interface
- Changed map title from "The Green Storm" to "Siege of Durnholde"

### Audio/Visuals
- All buffs are now removed from Thrall for the Taretha cinematic
- Changed owner of the Keep to Neutral Passive

## Chapter 9
### Gameplay
* Blackmoore
  - Replaced Shockwave with Endurance Aura
  - Replaced Devotion Aura with Unholy Aura
  - Removed ability Avatar
  - Increased mana regeneration
- Replaced Satyrs with Mutants and Skeletons
- Replaced a Scroll of Healing with a Rune of Restoration
- Every fourth item in the Endfight will be a Rune of Mana
- Reduced reaction time of Blackmoore to pick up an item from 1.5 to 1 second
- Slightly changed cliff blocking in Endfight
- Slightly moved items towards corners in Endfight
- Added a Rune of Restoration
- Decreased target acqusition range of Blood Mage from 600 to 200
- Added more Sentry Wards
- Replaced a Scroll of Mana with a Rune of Greater Mana

### User Interface
- Camera will now pan pan when entering the spider lair
- Added a hint for the Tower items

### Audio/Visuals
- Removed some Circles of Power
- Removed all Support Columns in the Invisible Bandits area
- Added walls to the Water area
- Decreased scale of Obelisks in Endfight area
- The spike traps will no longer be audible while the Intro cinematic is playing
- Fire units are removed befor the fight cinematic
- Fixed a bug that prevented the Fight cinematic from playing
- The Water Spike and Flame Traps will no longer be activated during the Fight cinematic

## Epilogue
- Added JonayMartin, HeeWonLee, ANachron, PeeKay, WILL THE ALMIGHTY, INSEKT, Sin'dorei300, Hemske, Kitabatake, supertoinkz, Epsilon, tauer, Sunchips, jatter2, -Grende, Xaran Alamas, Tenebrae, -Berz-, and KILLCIDE to credits



# Update 4 [2.0.0] (2015-01-24)
412 changes

## Campaign
### Multiple maps
#### Gameplay
- Fixed abilities not being loaded properly form a previous chapter
- Removed unnecessary custom objects
- Removed some unnecessary duplicated trigger actions
- Custom objects are now stored in the campaign file instead of each map
- Added new unit Spearthrower
- New items: Wand of Chain Lightning, Wand of Lightning Shield (self), Wand of Far Sight
- Removed Slow, Abolish Magic and Bash from all Kobolds
- Removed Flee from Shades
- Removed custom Healing Salve
- Decreased map size
- Added more space in many areas

#### User Interface
- Fixed quest descriptions
- Fixed spelling mistakes
- Changed icon of Catapult to classic Reign of Chaos icon

#### Audio/Visuals
- Removed unnecessary duplicated imports
- Replaced all non-Blizzard music with Blizzard music
- New model for Baby Thrall
- New model for Draka
- Changed Taretha's hair color to blonde
- - Increased detail in many areas
- Mixed Lordaeron Winter and Northrend tilesets
- Added fog
- Removed Thrall's death sequence
- Removed some wait times in cinematics
- Modified cinematics for new terrain

### Heroes
#### Thrall
- Rage can no longer be cast on enemy units or catapults
- Decreased duration of Rage from 40 to 30 seconds
- Increased cast range of Rage from 0 to 300
- Increased damage of War Stomp from 25/50/75 to 50/75/100
- Decreased mana cost of War Stomp from 90 to 75
- Increased selection scale from 1.1 to 1.2
- Fixed score screen icon
- Increases scale from 1.0 to 1.2
- Improved spell animations

## Prologue
- Removed some dialogue
- Added and changed some cameras
- Removed some unnecessary doodads
- Replaced fel orcs with normal grunts
- Renamed Baby Thrall to Orc baby
- Fixed fight timings

## Chapter 1
### Gameplay
- Changed locations of some switches
- Changed some patrol routes and starting locations of guards
- Changed types of some droppable items
- Replaced some knights with footmen
- Repositioned some guards
- Fixed a bug that removed visibility from switches
- Replaced the Mortal Team with two Bandits
- Added 5 Tomes of Lesser Experience
- Changed ownership of all units of Player 5 (Citizens) to Player 3 (Citizens)
- Removed Player 5

### User Interface
- Changed map title from "The Adventure Begins" to "Unchained"
- "Thrall must survive" is now a proper defeat condition

### Audio/Visuals
- Fixed a bug that stopped the music
- Removed a transmission from the Intro cinematic
- Fixed a bug that prevented Thrall from fighting in the Intro cinematic

## Chapter 2
### Gameplay
- Added more Trolls to starting area
- Added an optional quest to rescue some wolves
- Changed types of some droppable items
- Thrall can now flee through the main gate
- Removed a patrol guard
- Changed patrol route of a guard
- Second Escape quest is now completed when Thrall finds the Goblins
- Removed Player 9 (Guards)
- Imprisoned orcs are no longer invulnerable but periodically healed

### User Interface
- Split requirement for quest Second Escape into two
- Find your belonging quest requirement will now be properly completed
- Renamed player Camp to Guards

### Audio/Visuals
- Fixed a quest sound bug
- The Rest cinematic is now triggered after killing all trolls
- Fixed duration of the Kelgar cinematic
- The correct peon is now moving to Thrall in the Kelgar cinematic

## Chapter 3
### Gameplay
* Thrall
  - Decreased experience gain at level 3 from 75% to 50%
  - Decreased experience gain at level 4 from 33% to 20%
- Food quest items now grant experience
- Removed the Paladin quest
- Added a new optional quest "The Bandit Lord"
- Completing the new optional quest will reveal all items for the main quest
- Replaced and changed location of some guards
- Decreased time for cave sequence
- Decreased time until Towers are destroyed when Barrels of Explosives explode
- Removed cheese/self-destroying barrel sequence
- Added hiding spots for more stealthy gameplay
- Added Ensnare to Swordsmen
- Added a hint abouts Ensnare
- Thrall will gain vision of Guards in an area when entering that area
- Removed a dog
- Removed a droppable item from a pack horse
- Increased level of attack upgrades for Guards from 0 to 3
- Added some bandits at the northeast exit
- The Exit quest is now completed when the last group of bandits is dead
- Fixed bug preventing Riflemen from shooting at practice targets
- A Knight will now attack Thrall if he gets too close to the children
- Fixed bug preventing Tom from fighting Jerry

### User Interface
- Changed map title from "Hunger for your People" to "Hunger"
- The Food quest is now discovered after the Intro cinematic
- Added quest requirement "Find a village" to Food quest
- Removed optional quest "More Food". Its requirements are now part of the main quest
- Added quest requirement to all quests
- Changed text "Find the northeast exit" to "Flee through the northeast exit"
- Changed transmission "I don't need more food..." to "I have enough..."
- Added a transmission when Thrall is too close to the children
- Added minimap pings for each Food quest item
- Player 4 (Warsong clan) is now hidden in the Score Screen

### Audio/Visuals
- Removed the Lothar cinematic
- Removed the Paladin cinematic
- Remade Outro cinematic

## Interlude
- Replaced fel orcs with normal grunts
- Removed unnecessary objects in the scene
- Fixed some unit locations
- More cameras and improved camera movement
- Added some water to the terrain
- Changed the throne of Hellscream
- Removed all rats
- Changed color of fighting orcs to purple

## Chapter 4
### Gameplay
* Thrall
  - Decreased vision range in starting area
  - Life and Mana are refilled when seeing Grom or Taretha
  - Life now set to 100% when entering the Pacman game
- Thrall must now loot enemies for health to survive in the starting area
- Increased periodic damage to Thrall in the starting area
- Increased number of creeps in the starting area
- Removed all Healing Torches from the starting area
- Added numerous Runes of Healing and other helpful items to creeps
- Hellscream and Taretha now turn into hostile enemies that drop items when killed
- Added fast Spirit Pigs to the Pigs quest that will drop items when caught
- Removed all visibility modifiers for the Pigs quest
- Added a new visibility modifier that allows vision to the whole Pigs quest area
- Pigs quest net is now invulnerable
- Pigs quest will now stop when the timer runs out
- Removed a sheep
- All minigames (Book, Pigs and Pacman) will now restart when lost or Thrall dies
- Added some rewards for completing each miniquest
- Set life of all player units to 100% after the Ogre cinematic
- Thrall will no longer take damage form traps if invulnerable
- Added some Boulder Towers to the gnoll camp
- Repositioned some units at the gnoll camp
- Backpack upgrade is now disabled
- Decreased damage and hit points of all gnolls
- Added a Tome of Strength behind the Book quest area
- The Pacman speed items will no longer be usable multiple times during a single try
- Fixed a bug that prevented triggering the DrekTharAfterGnolls and Outro cinematics
- Ogre quest can now be started when the Pigs quest is completed instead of the Raiders vs Gnolls quest
- Increased terrain space in the starting area

### User Interface
- Changed text of first hint
- Renamed leaderboard from "Hay - Pigs at Hay" to "Pigs - missed"
- "Thrall must live" is now a proper defeat condition
- Renamed quest "The Frostwolves" to "Alone and Cold"
- Added quest "The Frostwolves" whick displays which quests need to be completed
- Changed text "Free the base to..." to "Enter the gnoll camp"
- Changed text "Rescue the pigs" to "Rescue all pigs"
- Fixed a transmission that wouldn't play
- Added a bonus item at the gnoll camp
- Buildings wil no longer drop items
- Removed some blocking doodads at the Pigs quest spawning areas
- Redesigned the gnoll camp

### Audio/Visuals
- Decreased volume of the scary sound during the Durotan vision
- Changed model of item "Lord of the Alliance" to a book
- Game is now playing War2IntroMusic during the Pacman game
- Changed sky from Lordaeron Winter (Yellow) to Blizzard
- Added Magical Runes to help guide Thrall
- Added more space at the ogre camp
- Increased ramp space to final gnoll camp
- Removed a few cameras from the Intro cinematic
- Removed a transmission from the Intro cinematic
- Removed haze effects for all non-vision cinematics
- Fixed some errors with the MeetFrostwolves cinematic
- Removed the RaidersvsGnollsGate cinematic
- Fixed some errors with the Raiders vs Gnolls cinematics

## Chapter 5
### Gameplay
* Thrall
  - Increased experience gain at level 6 from 33% to 40%
  - Is now properly revived when killed
* Air
  - Towers will no longer cast Taunt
  - Cinematic Tornado Thrall is no longer commandable
  - Decreased size of movement regions for the last group of hippogryphs
* Earth
  - Replaced Golems with Kobolds
  - Bringing the keys to the Circle of Light will now spawn Kobolds
  - Replaced Potions with Runes
* Fire
  - Decreased Mana Drained Per Second of Immolation from 2 to 1
  - Removed all Rock Chunks
  - Gate will no longer close
  - Removed a Rune of Greater Healing
  - Changed location of a Rune of Greater Mana
  - Changed locations of some obstacles
  - Replaced some Burning Archers with Skeletal Orcs
  - Replaced the Staff of Negation with a Wand of Chain Lightning
  - Decreased target acquisition range of all enemy units to 200
  - Removed a Flame Skeleton
  - Changed locations of some resurrectable Grunts
  - Added two Runes of Resurrection
  - Increased time between trap damage from 0.1 to 0.2 seconds
  - All player units can now suffer trap damage
  - Decreased hit points of Fire Beetles from 550 to 400
  - Decreased time for elevator under water by 1 second
  - Increased time for elevator above water by 1 second
  - Added more space to area
* Water
  - Removed the last line of Logs
  - Replaced all Mur'gul Blood-Gills with Makrura Snappers
  - Summoners are now invulnerable
  - Mur'gul Tidewarriors will drop Runes of Mana when killed
  - Quest will now properly reset when Thrall is killed
  - Decreased target acquisition range of all enemy units to 150
* Wilds
  - Decreased size of area
  - Feral Spirit is now properly removed when ending the quest
  - Removed unnecessary damaging regions
  - Removed Runes of Life from the Stag path
  - Added Boulder Towers that will force the Stag to move back
  - Stag can no longer escape the playground
* Doomhammer
  - Removed Reincarnation from Doomhammer
  - Items will now appear every 8 seconds
  - Doomhammer will now attack each item after 4 seconds
  - Thrall's death will no longer trigger the Doomhamer cinematic
  - Replaced a Potion of Lesser Invulnerability with a Wand of Chain Lightning
- Replaced a Shimmerglaze Roast with a Wand of Lightning Shield
- Added a Potion of Mana and a Potion of Healing

### User Interface
- Floating texts will be removed properly
- Renamed Strange Wanderer to Wanderer
- Fire: Changed initial hint to "Beware of the flame traps..."
- Earth: Changed initial hint to "Slay the enemies..."
- Water: Changed quest requirement to "Kill all 20 enemies"
* Wilds
  - Fixed initial hint
  - Changed the hotkey of Feral Spirit to F

### Audio/Visual
- Decreased scale of Spirit of Air
- Will no longer play object sounds during Fire cinematic
- Removed the Wind and Snow weather effects
- Earth: Removed some rocks
- Removed the Travel sequence from the Intro cinematic
- Removed some minor parts from the Intro cinematic
- Changed some camera angles in the Intro cinematic
- Removed first camera movement from the Earth cinematic
- Removed first camera movement from the Water cinematic
- Removed some minor parts form the Air cinematic
- Changed some camera angles in the Air cinematic
- Removed some minor parts from the Wilds cinematic
- Added pathing Blockers (Air) to the Wilds cinematic
- Improved camera movement in Doomhammer cinematic
- Improved text in Doomhammer cinematic
- Removed some parts from the Outro cinematic
- Game now removes all buffs at the start of a cinematic

## Chapter 6
### Gameplay
- Thrall: Fixed a bug with starting abilities
* Langston
  - Increased initial mana from 30% to 100%
  - Removed abilities Holy Light and Resurrection
  - Increased hero level for 8 to 10
- Decreased experience gain for all heroes at level 7 from 50% to 20%
- Doomhammer and Hellscream can now be revived at the new Altar of Storms
- Removed all starting items from Doomhammer and Hellscream
- Thrall can now be revived after his escape
- Game can only be lost if Thrall dies while escaping 
- Redesigned Breakout area
- Player will now start with a few units at the Breakout area
- Removed time pressure from Breakout area
- Replaced escaping grunts with normal grunts
- Replaced camp guards with footmen
- Removed escaping peons
- Removed optional quest "The Items"
- The Orc's Rescue is now part of the Main Quest
- Changed The Orc's Rescue objective to destroy the gate
- Changed locations of two Barracks
- Changed locations of War Mill, Catapults and Neutral Buildings
- Removed most creeps
- Added golems to the northeast that drop a Helm of Valor
- Decreased cost of Ankh of Reincarnation from 300 to 200 gold
- Ankh of Reincarnation can now be dropped
- Increased costs of all upgrades and mercenary units
- Removed Staff of Teleportation from the Goblin Merchant
- Added Wand of Chain Lightning and Wand of Lightning Shield to the Goblin Merchant
- Replaced Dire Frost Wolf with Spearthrower in Drek'Thar's camp
- The War Mill now produces 50 Food
- Added more Guard Towers
- Added an optional quest to rescue elite orcs
- Removed player 3 (Citizens)
- Set Stock Maximum for Catapults, Frost Wolves and Spearthrowers to 3 seconds
- Set Stock Replenish Interval for Catapults, Frost Wolves and Spearthrowers to 30 seconds
- Set Stock Start Delay for Catapults, Frost Wolves and Spearthrowers to 0 seconds
- Frost Wolves and Spearthrowers to 3/30 seconds/0 seconds
- Added Boots of Speed
- Increased damage of Guard Towers from 23-28 to 33-38
- Doomhammer's items will be transferred to Chapter 7
- Added Elite Guard Towers
- Increased base damage of Watch Towers from 15 to 60

### User Interface
* Langston
  - Changed name "Paladin" to "Chief Lieutenant"
  - Changed proper name "Lord Karramyn Langston" to "Karramyn Langston"
- Doomhammer: New icon
- Changed hotkey of Shaman Adept/Master Training to "H"
- Removed the hint to kill creeps
- Removed hint about custom Healing Salve
- Renamed Bodyguard to Elite Knight
- Barracks leaderboard will now be updated correctly

### Audio/Visuals
- Langston: Level Up graphics are now hidden
- Replaced Great Hall doodads with Orc Houses (Burrows)
- Added a way to cross between the two Barracks expansions
- Fixed skip bug in Intro cinematic
- Removed some parts in the Intro cinematic
- Removed Flame Strike effect that appeared at the center of the map
- Watch Towers from the Intro cinematic are now preplaced
- Cinematic mode will no longer be deactivated at the end of the outro cinematic
- Moved Thrall's speech to the starting area in the Outro cinematic
- Player 12 Grunts now belong to Player 1 in the Outro cinematic
- Player 4 starting units are no longer hidden in Outro cinematic
- All kinds of Spirit Wolves are removed for the cinematics

## Chapter 7
### Gameplay
- Thrall: Increased starting level from 5 to 8 if not restored from game cache
- Hellscream: Increased starting level from 5 to 8 if not restored from game cache
- Doomhammer's items are now imported from Chapter 6
- Complete gameplay redesign
- Removed most of old Durnholde
- Changed locations of all players' bases
- Removed all optional quests
- Removed many creeps
- Refined enemy AI
- Enemies will now research upgrades
- Enemies will now attack in different tiers after some time
- Now able to control player base while looking for Taretha
- Reset speed and food cost of all enemy units
- Can now research Burning Oil and Reinforced Defenses
- Peons will stop harvesting while in a cinematic
- Can now train Spearthrowers from the Barracks
- Can now upgrade Envenomed Weapons from the War Mill
- Removed player 3 (Citizens)
- Player has to destroy all buildings of Durnholde (Grey) except Farms and Towers
- Removed all tech tree requirements for enemy units
- Player 9 (Durnholde) will no longer rebuild his base
- Added a new optional quest to free captured elite orcs
- Units surviving the Taretha quest will now be brought over to the main area
- Game is now lost when all player structures are destroyed
- Added runes, bundles of lumber and gold coins on the road to Taretha
- Added elite knight to each enemy base
- Removed defeat condition for Drek'Thar's death
- When killed, Drek'Thar will come back to life after 30 seconds
- Increased target acquisition range of Drek'Thar from 1250 to 1700
- Drek'Thar will now only teleport to structures

### User Interface
- No longer required to press ESC twice to skip the TarethaAndBlackmoore cinematic
- Changed quest requirement "Destroy the four..." to "Destroy the Grey Base"
- Added quest requirement to not attack Durnholde while looking for Taretha
- Fixed description for Spirit Lodge
- Decreased time between minimap pings from 20 to 12 seconds
- Removed Frost Wolf hint

### Audio/Visuals
- Complete terrain redesign
- Removed all cinematics associated with optional quests

## Chapter 8
### Gameplay
- Cloak of Shadows will no longer be removed at map start
- Removed player 12 (Vagabonds)
- Removed player 4 (Neutral)
- All enemy units (except Blackmoore) are now neutral hostile
- Added Tomes of Experience to multiple enemies
- Blackmoore will now appear from time to time
- Changed general layout to be less linear
- Many areas are now connected via Way Gates
* Thrall
  - Decreased experience gain from 100% to 45%
  - Increased starting level from 8 to 9 when not restored from game cache
* Spiders
  - Added numerous spider eggs
  - Now all spider eggs hatch when Thrall approaches them
  - Spiders no longer cast Ensnare
* BlueFlames
  - Redesined area
  - Changed position and number of flame traps
  - Added more types of traps
  - Added more enemy units
  - Replaced Circlet of Nobility with Cloak of Flames
* Sheep
  - Redesigned area
  - Player can now control sheep directly
  - Added ability Kaboom! to all sheep
  - Sheep will be replaced infinitely
  - Increased controllable number of sheep from 1 to 3
  - Removed teleporters, Iron Gates and Switches
  - Added a Blood Mage that casts Flame Strike
  - Player now has to guide sheep to destroy a Power Generator
  - Added vision to the area
* Glaives
  - Redesined area
  - Increased damage region of glaives
  - Increased attack check rate of glaives
  - Set attack rate of glaives to 1.45 seonds
  - Increased damage of glaives from 100 to 150
  - Added new types of glaives with different movement
  - Added hostile Satyrs
  - Added vision to the area
  - Added a Rune and a Healing Potion
  - Added two switches which activate a Way Gate
* Flood
  - Removed Rising Water doodads and gameplay mechanics
  - Redesigned area
  - Added a transport ship
  - Added gates
  - Added more types of Water Elementals and Earth-Fury Towers
  - Earth-Fury Towers now drop items
* Bandits
  - Redesigned area
  - Removed the Charing Pan, Rock Chunks and Catapult
  - Replaced Shadow Meld of Brigands with Permanent Invisibility
  - Added Slow Poison to Brigands
  - Added Sentry Ward items
  - Removed all Land Mines
* Endfight
  - Removed Flesh Golem and Switches
  - Runes will now be created before a fire
  - After a while two fires will be created
* Blackmoore
  - Decreased reaction time to items from 2.0 to 1.5 seconds
  - No longer moves unless there is an item
  - Removed ability Shockwave
  - Added ability Drunken Haze
  - No longer takes damage from fire

### User Interface
- Renamed Teleporter to Circle of Power
- Changed main quest requirement text to "Kill Aedelas Blackmoore"
- The quest completed message is now displayed before the Outro cinematic
- Sheep: Renamend Mechanical Sheep to Explosive Sheep

### Audio/Visuals
- Added sound to Fire units
- Increased scale of Brood Mother
- Removed the Dalaran Shield weather effect
- Moved Thrall further away from the Gate in the Fight cinematic
- Removed a minor scene in the Outro cinematic
* Endfight
  - Music theme will be repeated until victory
  - Music theme will no longer deactivate when minimizing the game

## Epilogue
- Merged the modified Chapter 1 and the new Chapter 7
- Complete remake of camera and unit movement
- Removed some minor scenes and dialogue
- Removed rain effect
- Combined credits of "Idea and Execution" and "Triggers" into "Design"
- Removed "Music" credits
- Added additional "Models, Skins and Art" credits and named them "Additional Art and Music"
- Added  ChevronSeven, Tauer, Frankster, Stanakin sniper_zero and darklord_avalon to the credits
- Removed Blizzard, Gladiator and The Matrix Trilogy from the credits


# Update 3 [1.2.0] (2013-09-18)
170 changes

## Campaign
### Multiple maps
#### Gameplay
* Thrall
  - Will no longer lose his items from previous chapters
  - Baby cloth no longer drops on death
  - Added ability Rage
  - Removed ability Evasion
* Thrall (Grunt)
  - Increased initial mana from 50 to 100
  - Increased base intelligence from 14 to 17
  - Increased mana regeneration from 0.66 to 0.80 per second
- Added map victory cheat "-winmap"

#### User Interface
- Fixed player name
- Floating texts will now be removed properly
- Fixed typos and spelling mistakes

## Prologue
- Improved terrain in the Raven flight area
- Removed scene "travelling to fire camp"
- Increased field of view for Doomhammer cameras
- Removed a stone

## Chapter 1
### Gameplay
* Thrall
  - Changed starting ability to from Evasion to Storm Bolt
  - Increased starting hit points from 250 to 400
- Removed some enemy units
- Decreased target acquisition range for a Footman
- Added more Runes of Healing/Mana
- Now all switches need to be pressed for the gate to open
- Fixed defeat condition when killing civilians
- Player will no longer lose control of the Dog when it tries to exit the city
- Dog now moves back a bit when it tries to exit the city
- Game will now longer pause when switches 1-4 are pressed

### User Interface
- Renamed player Durnholde to Guards

## Chapter 2
### Gameplay
- Removed or replaced all Mud Golems
- Added a Fountain of Mana to the Kobold camp
- Food now heals life and mana
- Removed some Humans
- Changed location of some Trolls
- Removed some Trolls for the quest "Volbir and Bolvir"
- Decreased required lumber for the quest "Volbir and Bolvir" from 16 to 12
- The Mock cinematic can no longer be played before the Kelgar cinematic
- Removed and changed location of some Kobolds
- Added a Rune of Healing to a Kobold
- Disabled sleeping for all creeps

### User Interface
- Changed map title from "Wrong Time..." to "Lethargy of the Orcs"
- Renamed player Camp-Soldiers to Guards
- Removed the Lumber leaderboard
- Added exclamation marks to the unfriendly orc and Kelgar

### Audio/Visuals
- Smoothed terrain in the Capture cinematic
- Increased time for some cameras in the Volbir and Bolvir cinematics

## Chapter 3
### Gameplay
- Decreased hit points of Rock Chunks
- Removed some enemy units
- Changed location of a Food quest item
- Added a blockade to the northern parts of the village
- Added defeat condition "Don't kill innocent people"
- Changed ownership of horses and dogs to Neutral Passive

### User Interface
- Transmission at the grain farm will only appear once
- Removed transmission at the slums

## Interlude
- Changed map title from  "A Hell's Scream" to "Hellscream"

## Chapter 4
### Gameplay
- Removed some enemy creeps
- Changed starting location of Raiders at the quest "Raiders vs Gnolls"
- Removed some towers at the Ogres area
- Increased pathing space at the Ogreas area
- Removed keyboard controls at the Pacman quest
- Decreased base damage of Ogre Maulers in the Pacman quest from 200 to 100
- Replaced all Runes of Healing with Runes of Speed in the Pacman quest
- Item Lord of the Alliance is no longer marked as usable
- Added blocking terrain at Pigs quest area
- Camera will no longer change at the Pigs quest
- Decreased time for Pigs quest from 180 to 150 seconds
- Decreased random movement speed of pigs by 20
- Increased time between pig spawns from 15/10/8 to 20/15/13
- Decreased trap damage at Book quest area from 200 to 125
- Decreased hit points of some Rock Chunks

### Audio/Visuals
- Removed Pacman music
- Changed hint for the Pigs quest to stay close to the hay
- Created minimap pings for all switches
- Fixed time for some transmissions
- Raiders will now attack the proper Rock Chunks

## Chapter 5
### Gameplay
- Thrall: Life and mana reset to 100% before each quest
* Thrall (Wilds)
  - Added ability Feral Spirit
  - Removed ability Blink
  - Removed ranged attack
  - can now reach the Stag
* Air
  - Removed timer
  - Removed some hippogryphs and towers
  - Increased time between hippogryph movement from 3/4/5 to 4/5/6 seconds
* Fire
  - Thrall: Added ability Immolation
  - Removed two Firebeetles
  - Replaced Hellfires with Skeleton Archers
  - Added a Rune of Mana
  - Increased pathing space
* Earth
  - Removed timer
  - Leaderboard is now properly destroyed
- Water: Removed keyboard controls
- Endfight: Thrall can now use all abilities

### Audio/Visuals
- Cinematic mode is now deactivated when the Intro cinematic is skipped

## Chapter 6
### Gameplay
- Thrall: Increased maximum level from 7 to 8
* Hellscream
  - Increased maximum level from 7 to 8
  - Increased starting level from 4 to 7
* Langston
  - Decreased level from 10 to 8
  - Removed ability Divine Shield
  - Increased level pf Holy Light from 1 to 2
- Mana of heroes is now set to 100% when Langston appears
- Ankhs of Reincarnation carried by heroes are now removed at map victory
- Rescuing the fleeing orcs is now a separate optional quest
- Can no longer fail the mission if a fleeing orc dies
- Fleeing Grunts/Peons are now replaced with normal Grunts/Peons when rescued
- Decreased range of initial attack location of Hellscream and Doomhammer
- Changed location of a camp guard

### User Interface
- Renamed quest "The Orc's Rescue" to "The Internment camp"
- Increased time between displaying starting quests and hints

## Chapter 7
### Gameplay
- Thrall: Increases maximum level from 8 to 9
- Hellscream: Increases maximum level from 8 to 9
- Destroying one Rock Chunk now destroys all Rock Chunks
- Zeppelin now shares vision with player
- Added a Fountain of Health
- Decreased numer of enemy Gryphons in attack wave from 3/6/9 to 2/4/6
- Removed some Towers from enemy bases
- Removed defeat condition from quest "Reinforcements"
- Removed a Rifleman from Reinforcements area
- Added Rock Chunks to Reinforcements area
- Increased pathing space at Reinforcements ramp
- Reinforcements ramp can now be reached on foot

### User Interface
- Added exclamation mark to Zeppelin
- Added Leaderboard for towers built for the quest "Reinforcements"
- Removed leader for destroyed enemy town halls
- Can no longer trigger the Reinforcements dialogue  multiple times

### Audio/Visuals
- Added Dog to Taretha's cave
- Removed a scene from the Zeppelin cinematic

## Chapter 8
### Gameplay
* Thrall
  - Increased maximum level from 9 to 10
  - Set experience gain to 100%
  - Added ability Evasion
  - Life and mana set to 100% before Endfight
* Blackmoore
  - Removed items
  - Decreased Damage Sides Per Die from 6 to 5
  - Increased Attack Cooldown from 2.2 to 2.6
  - Increased Intelligence Per Level from 0.8 to 1.6
  - Increased Life
  - Now tries to steal spawned items
- Decreased hit points of Iron Gates to 50
- Replaced Greater Rune of Healing with a Rune of Restoration
- Added a Rune of Healing
- Removed several Spiders and Bandits
- Added an Enforcer
- Increased spawn rate for Blue Flame Traps from 1.75 to 4/3/2 seconds
- Mechanical sheep will now move towards an opened gate
- Fixed a broken switch
- Decreased size of fire regions in the endfight
- Decreased spawn rate of items in the endfight from 5 to 3 seconds
- Removed Orb of Lightning from the endfight
- Added more Runes of Healing to endfight
- Removed healing water

### User Interface
- Changed name of player Aedelas Blackmoore to Lord of Durnholde

### Audio/Visuals
- Removed scene with Flesh Golem
- Runes will now glow before activating in the endfight

## Epilogue
- Thrall now says what item he is giving to Hellscream
- Merged all map creation credits
- Replaced all non-orcs in credits with versions of Thrall
- Added World of Warcraft to Music credits


# Update 2 [1.1.1] (2011-01-13)
7 changes

## Campaign
### Multiple maps
#### Audio/Visuals
- Fixed typos and spelling mistakes
- Smoothed terrain on some ramps

## Chapter 2
### Gameplay
- Changed location of secret exit in internment camp

## Chapter 4
### Gameplay
- Decreased time of the quest "These Pigs!"

## Chapter 6
### Gameplay
- Changed location of Barracks
- Changed initial target location for heroes
- Langston: Decreased level of all abilities


# Update 1: [1.1.0] (2010-02-22)
58 changes

## Campaign
### Multiple maps
#### Gameplay
- Thrall: Replaced Bash with Storm Bolt
- Turned Give Bounty on for player Neutral Hostile

#### User Interface
- Thrall: Changed War Stomp Hotkey to W

#### Audio/Visuals
- Added sound effects to water
- Changed time for some transmissions
- Fixed typos and spelling mistakes

## Prologue
- Improved some camera angles

## Chapter 1
### Gameplay
- Thrall: Changed starting ability to Evasion
- Game will no longer pause for transmissions

### Audio/Visuals
- Added sound effects to switches
- Changed sound effect when completing quest "The Gate"
- Decreased volume of opening gate
- Decreased playtime of Outro cinematic

## Chapter 2
### Gameplay
- Removed some Trolls
- Added a Rune of Mana
- Triggering the Kelgar cinematic now deactives the Mock cinematic
- Fixed plotstopper with the quest "Volbir and Bolvir"

### User Interface
- The Lumber Leaderboard is now properly updated

## Chapter 3
### Gameplay
- Added Pathing Blockers to the village entrance
- The Paladin's map is now properly removed

## Interlude
- Changed owner of grunts to Player 4 after defeating them

## Chapter 4
### Gameplay
- Thrall: Fixed bug loading stats from Chapter 2
- Decreased time of the quest "These Pigs!" by 40 seconds
- Decreased speed of pigs by 50
- Decreased spawn rate of pigs by 2 seconds
- Fixed plotstopper when completing the quests in a specific order
- Raiders no longer attack Thrall if he attacks them
- Raiders no longer surround Thrall
- Improved difficulty curve for quest "Raiders vs Gnolls"
- Increased lumber gather radius in quest "Pacman"
- Increased width of road to the ogre towers
 
### Audio/Visuals
- Increased terrain height under Gnoll Huts

## Chapter 5
### Gameplay
- Thrall: Increased level to 6
- Drek'Thar no longer gains a level if Thrall dies
- Decreased spawn rate of Skeleton Archers
- Increased spawn speed of Skeleton Archers
- Granite Golem is now asleep until bringing all keys to him
- Decreased rate of elevator height change from 5 to 4 seconds

### User Interface
- Floating texts are now properly removed

## Chapter 6
### Gameplay
* Thrall
  - Added Cloak of Shadows to inventory at map start
  - Added Ankh of Reincarnation to inventory at map start
- Replaced Cloak of Shadows at city centre with a Potion of Healing
- Decreased spawn rate of enemies
- Removed defeat condigion for civilians
- Changed initial targets for Hellscream and Doomhammer from the expansion Barracks to the first Human Towers
- Fleeing Orcs now changed ownership to Player 1 when rescued
- Decreased hit points of Bodyguards from 1200 to 1000
- Changed initial mana of Langston to 30%

## Chapter 8
### Gameplay
* Thrall
  - Changed experience gain to 50%
  - Increased maximum level from 8 to 9
  - Unlocked War Stop level 3
- Added hint for the Sheep puzzle
- Removed many Runes of Healing at the Spiders area
- Replaced some low-level spiders with higher-level spiders
- Added a Rune of Restoration at the Fountain of Health
- Removed a Potion of invulnerability
- Changed position of endfight items to the corners

### Audio/Visuals
- Decreased height of teleporters

## Epilogue
- Credits theme is now repeated until the end of the cinematic