# Shipwreck [WIP]
## Overview
Shipwrecks are one of MCSR Ranked's five overworld seed types. They involve finding and looting a shipwreck, obtaining tools, blocks, and doors from an island, and travelling to an ocean ravine to build a portal and enter The Nether. Shipwrecks offer an easy supply of iron and food.

### Elo Distribution
*The below table displays the odds of the selected seed type appearing as a shipwreck.*
| Elo | %
| --- | ---
| 0 ~ 599 | 15%
| 600 ~ 1199 | 25%
| 1200+ | 20%

### Gameplay Changes
- Shipwreck generates within 4 chunks, with positive X and Z coordinates
- 2 magma ravines found within 10 chunks of the shipwreck
   - Filtered magma ravines will not generate within frozen ocean biomes
- Shipwreck treasure chest contains guaranteed 7+ iron, or 3+ diamonds and 4+ iron
- Shipwreck supply chest contains guaranteed food
   - Suspicious stew found within the supply chest cannot be poisonous
- No other shipwrecks, buried treasures, or unintended blockentities generate around spawn
- Buried shipwrecks are attempted to be filtered out

## Routing
### Locating
Shipwrecks are found by searching around the spawn island.

This process can be expedited by using the `root.gameRenderer.level.entities` piechart to scan around for a spike on the `blockEntities` portion of the piechart, indicating a chest.

**[TODO] Insert screenshots here of the pies**

If no spike appears, one can sometimes use knowledge of the seed filter and coordinates. Since shipwrecks only spawn in the positive, positive quadrant, this can narrow down the amount of possible places to check. 

Example: the player spawns in at -41, 20. Due to the player spawning in a negative quadrant, they should head towards the positive quadrant by travelling in the positive X direction. After going far enough, they may be able to re-scan and get a spike on the piechart. 
### Looting
Shipwrecks in MCSR Ranked are guaranteed to have all 3 chests present - in other words, they will not be broken. When swimming to the shipwreck, it is important to know where the useful chests are located.
**<ins>[TODO] Insert screenshot here of a ship with outlined and labelled chests. use invis outlined magma cubes inside chests with a screenshot. Gen a ship w/ gray or white concrete background</ins>**
- Treasure chest
  - The treasure chest contains the materials needed to construct tools - iron, gold, and diamonds. It is found in the large, bulky section of the shipwreck.
- Food chest
  - The food chest contains - as the name implies - the food for the duration of the run. Any wheat obtained may be crafted into bread and any carrots may be crafted into golden carrots in the bastion. This chest also sometimes contains TNT. It can be found on the opposite side of the shipwreck from the treasure chest.
- Map chest
  - Unfortunately, the map chest's loot is not useful for MCSR Ranked. However, it can be found between the treasure and food chest.
  
Sometimes, it may be advantageous to loot chests in a distinct order to save health and air to prevent drowning.

### Island
After looting necessary shipwreck chests, head back to the island. Should any tnt be obtained, blow it up next to 2-3 trees with a pressure plate or button. Otherwise, break 2 logs with a fist. Craft a crafting table and 8 sticks.

At this point, one must decide what items to craft. At bare minimum, craft:
- An Iron (or diamond) Pickaxe
- A bucket
- Save 1 iron for a flint and steel

The above materials cost 7 base iron. After that, additional iron can be spent on iron tools, shears, and iron doors. In order, prioritize shears, then tools, then doors. If any gold or diamonds are obtained, they can be used to construct tools instead. If shears are made, aim for at least 40-50 leaves.

After crafts are complete, chop down more trees. One should aim to grab an amount of logs proportional to the minimum amount of beds they are comfortable with to kill the dragon. At bare minimum, one needs 6 logs, creating 24 planks. (5 for a boat, 6 for a door, and 13 leftover for 4 beds) However, one should get more [TODO} fix


Create a boat and doors, then head off to a magma ravine.

## Advanced Tips
- It rarely may be more optimal to skip going to the island entirely - specifically in the case where the shipwreck is very close to a magma ravine, and the shipwreck has large masts with lots of wood.
- Check leather boots in the food chest for feather falling and depth strider. They will always be at max level. Feather falling 4 boots are extremely useful to prevent taking damamge from falling and ender pearls.
