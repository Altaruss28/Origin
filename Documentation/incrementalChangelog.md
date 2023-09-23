## AST-v1.0

Initial remake of the Bootstrap setup (v1.10.3, June 2023)

## AST-v1.1

### Rebalance changes:
- Reduced assassin speed while rallypointed to that of Arabian swordsmen, doubled their damage to buildings and base melee damage (Damage against more elite melee units remains the same)
- Tunneler base building damage up to 100
- Catapult speed level down to 8 (European swordsman speed)
- Mercenary post cost down to 10 wood
- Engineer's guild cost down to 10 wood
- Stables cost up to 400 gold, 40 wood, 40 stone
- Tower2 (Perimeter turret) cost down to 5 stone, 5 wood
- Tower ballista cost up to 20 wood
- Ox tether cost down to 5 wood
- Wheat and hops farm cost down to 10 wood, health down to 250
- Cathedral cost up to 400 gold, 40 stone
- Blacksmith cost up to 10 wood, 5 stone, 1 iron
- Tanner cost up to 10 wood, 5 stone
- Armorer cost up to 10 wood, 5 stone, 5 iron

## AST-v1.2

### Rebalance changes:
- Fletcher cost up to 10 wood, 10 stone
- Armorer cost up to 10 wood, 10 stone, 5 iron
- Stables cost down to 300 gold, 30 wood, 30 stone

### Map changes:
- Added "2v2-Wacht des Wassermanns"

### Other:
- Remade the Snake AI
- Added Pig and Wolf AIs

## AST-v1.3

### Rebalance changes:
- Tanner cost down to 10 wood

### Map changes:
- Updated "1v1-Chernozhice" - A fix to a farmspot

### Other:
- Removed links to Bootstrap rebalance v1.10.2 and v1.10.5 stats spreadsheets from the ReadMe

## AST-v1.4

### Rebalance changes:
- Tower ballista cost up to 30 wood
- Tanner health down to 250

### Map changes:
- Added "1v1-Kopidlno"

### Other:
- Small adjustments to the AIs
- Added a new improved monk graphic
- Added a separate graphics pack for copy-paste installation

## AST-v1.5

### Map changes:
- Added "1v1-Odessa"
- Added "1v1-Tabor"
- Added "2v2-Neratov"
- Added "vsAI-Tilos"
- Added "vsAI-Wall of Iron"

### Other:
- Added a Sultan and an Abbot AI (Neither of which utilize the beer sell bug)
- Added a fixed monk graphic
- Fixed copy-paste graphics pack directory in the ReadMe
- Added this incremental changelog, as well as a link to it in the ReadMe

## AST-v1.6

### Rebalance changes:
- Stables cost up to 400 gold, 40 wood, 40 stone
- Blacksmith cost to 10 wood, 1 iron, 5 pitch
- Armorer cost up to 10 wood, 20 stone, 5 iron

### Map changes:
- Updated "1v1-Tabor" - Fewer safe trees for the lowground player and more for the highground player

### Other:
- Added a new horse archer graphic and a new beach graphic
- Remade this incremental changelog in Markdown

## AST-v1.7

### Rebalance changes:
- Halved the arrow damage taken of all units (Except for workers and animals)
- Monk base melee damage down to 25dpt
- Tower ballista cost to 200 gold, 20 wood
- Killing pit cost down to 20 gold
- Cathedral cost down to 300 gold, 30 stone
- Cost of all negative fear factor buildings down to 40 gold
- Cost of all positive fear factor buildings down to 20 gold

## Origin-v1.0

The setup has been renamed from 'AST' (Alternative-Setup-Testing) to Origin

### Rebalance changes:
- Woodcutter's hut health down to 125
- Ox tether health down to 125

#### Armored unit/Iron rework
- Halved the health of pikemen, European swordsmen, knights and Arabian swordsmen
- Pikeman damage to knights and horse archers up to 200dpt
- Increased European swordsman and Arabian swordsman speed by 1 level
- Arabian swordsman base damage up to 200dpt, base building damage up to 100
- Blacksmith cost up to 10 wood, 5 iron, 5 pitch
- Armorer cost to 10 wood, 10 stone, 10 iron
- Stables cost down to 300 gold, 30 wood, 30 stone
- Iron per delivery up to 2

### Population, popularity, taxation, fear factor and housing rework:

#### Peasant respawn rate
- Peasant respawn rate at 100 popularity is halved
- From 100 to 50 popularity the respawn rate linearly decreases by 10% for every 5 popularity points lost
- From 50 to 0 popularity, the rate at which you lose peasants/workers linearly increases by 10% for every 5 popularity points lost, and is half of the respawn rate

#### Taxation changes
- There are 12 levels, the first is for bribes which gives you +10 popularity, the second is for "No taxes" which gives you 0 popularity, the next 10 levels are for taxing, which cost you -1 popularity each, going up to -10
- The first taxation level no longer gives you 3 times the gold, compared to the rest
- The only bribe level (+10) costs you exactly as much gold as the highest tax level (-10) gives you
- Gold income per tax level is otherwise unchanged

#### Religion changes
- Chapel cost up to 100 gold, 10 stone
- Church cost up to 200 gold, 20 stone
- Cathedral cost to 400 gold, 40 stone
- Blessing popularity modifier down to +1 per level, up to +4
- Percentage of blessed population thresholds down to 20%, 40%, 60%, 80%

#### Beer/Food changes
- Hops farm cost up to 20 wood, health up to 500
- Hops per delivery down to 1
- Inn cost up to 20 wood, 20 stone, population coverage up to 50
- Beer coverage popularity modifier stays at +1 per level, up to +4
- Wheat farm cost up to 20 wood, health up to 500
- Wheat per delivery down to 1
- Mill cost up to 20 wood, 20 stone
- No rations popularity modifier to -10, half rations to -5, extra rations to +5, double rations to +10
- Meat per delivery down to 5, apples per delivery up to 5, cheese per delivery up to 5, bread per delivery up to 10
- Hunter's post health down to 125

#### Fear factor condenstation
- All positive fear factor building cost up to 100 gold, health ranging from 125 to 500, the larger the building, the more health
- All negative fear factor building cost up to 200 gold, health ranging from 125 to 500, the larger the building, the more health
- Base fear factor coverage to 64 population (4 times more coverage)

#### Housing condensation
- Hovel cost up to 20 wood, health up to 500, population per hovel up to 25
- Population per keep up to 25

### Map changes:
- Reduced the number of deer groups and iron mine spots on all maps, except the AI ones

### Other changes:
- Removed all the AIs but the inactive Rat, as this update breaks them, to be replaced in an upcoming update
- Adjusted in-game text and voice lines to reflect some of the changes
