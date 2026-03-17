# Shipwreck
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

<img width="162" height="125" alt="image" src="https://github.com/user-attachments/assets/e04cee5c-4b8a-40e6-a214-cbdaa6135cb3" /> 

<sub>*An example of a piechart with a shipwreck spike. Note that spikes will differ across hardwares. Also, if you use the piechart, be sure entity distance is set to 50% and render distance to 8 in standardsettings.*</sub>

If no spike appears, you can sometimes use knowledge of the seed filter and coordinates. Since shipwrecks only spawn in the positive, positive quadrant, this can narrow down the amount of possible places to check. 

Example: the player spawns in at -41, 20. Due to the player spawning in a negative quadrant, they should head towards the positive quadrant by travelling in the positive X direction. After going far enough, they may be able to re-scan and get a spike on the piechart. 
### Looting
Shipwrecks in MCSR Ranked are guaranteed to have all 3 chests present - in other words, they will not be broken. When swimming to the shipwreck, it is important to know where the useful chests are located.

| Upright | Sideways | Flipped
| --- | --- | ---
| <img width="384" height="216" alt="ship_upright - final" src="https://github.com/user-attachments/assets/49ab3ccd-10a1-4ec3-a7e6-703d62fc568a" /> | <img width="384" height="216" alt="ship_sideways - final" src="https://github.com/user-attachments/assets/48f30d20-d38d-4552-9a4d-acf9e0334931" /> | <img width="384" height="216" alt="ship_flipped - final" src="https://github.com/user-attachments/assets/56d51ad4-02fb-49ce-a500-be379cf4517e" />

- Treasure chest
  - The treasure chest contains the materials needed to construct tools - iron, gold, and diamonds. It is found in the large, bulky section of the shipwreck.
- Food chest
  - The food chest contains - as the name implies - the food for the duration of the run. Any wheat obtained may be crafted into bread and any carrots may be crafted into golden carrots in the bastion. This chest also sometimes contains TNT. It can be found on the opposite side of the shipwreck from the treasure chest.
- Map chest
  - Unfortunately, the map chest's loot is not useful for MCSR Ranked. However, it can be found between the treasure and food chest.
  
Sometimes, it may be advantageous to loot chests in a distinct order to save health and air to prevent drowning.

### Island
After looting necessary shipwreck chests, head back to the island. Should any tnt be obtained, blow it up next to 2-3 trees with a pressure plate or button. Otherwise, break 2 logs with a fist. Craft a crafting table and 8 sticks.

At this point, decide what items to craft. At bare minimum, craft:
- An Iron (or diamond) Pickaxe
- A bucket
- Save 1 iron for a flint and steel

The above materials cost 7 base iron. After that, additional iron can be spent on iron tools, shears, and iron doors. In order, prioritize shears, tools, then doors. If any gold or diamonds are obtained, they can be used to construct tools instead. If shears are made, aim for at least 40-50 leaves.

After crafts are complete, chop down more trees. Aim to grab an amount of logs proportional to the minimum amount of beds they are comfortable with to kill the dragon. At bare minimum, one needs 6 logs, creating 24 planks. (5 for a boat, 6 for a door, and 13 leftover for 4 beds) However, get more wood for more beds, golden pickaxes, or a bow later in the run. Most top runners grab 8 or 9 logs.

Craft a boat and oak doors and head off to a magma ravine.

### Magma Ravine
To find a magma ravine, enable hitboxes with `F3` + `B`. Look for large amounts of kelp floating on the surface of the water. If no kelp can be found, look for ravines in the water.

> [!NOTE]
> A helpful tip is to change brightness to 500% in video settings. This allows for much better visibility underwater.

After arriving at the ravine, place a door on top of gravel near the edge of the ravine. Mine gravel until flint drops, then break the door and swim down to the magma.

> [!NOTE]
> On ocean seeds where the ravine is located in a warm ocean, there will not be gravel easily accessible. Grab gravel before leaving the island instead.

At this point, construct a Nether Portal. Learn to do so by following [Jourona's video](https://www.youtube.com/watch?v=mLuxNQZshy0).

## Advanced Tips
- It rarely may be more optimal to skip going to the island entirely - specifically in the case where the shipwreck is very close to a magma ravine, and the shipwreck has large masts with lots of wood.
- Check leather boots in the food chest for feather falling and depth strider. They will always be at max level. Feather falling 4 boots are extremely useful to prevent taking fall damage.
- If it seems difficult to find any magma ravine, make sure to check in areas not checked yet.
