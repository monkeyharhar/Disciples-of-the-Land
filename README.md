# Disciples-of-the-Land
The goal of this project is to implement the gathering system from FFXIV in a browser format.

# Classes
-Botanist: harvests resources from the various flora and growth (plants and trees) of Eorzea.

-Fisher: harvests fish and other sea creatures from the waters of Eorzea.

-Miner: extracts minerals from grounds of Eorzea.

The first class that will be implemented is the Miner.

# Attributes
-Gathering: increases your likelihood of receiving an item while gathering. The higher the level of the item, the more Gathering Points   are required for a 100% chance.

-Perception: increases the probably of the item you receive to be high quality, up to a maximum of 15% base chance. No effect on items that cannot be high quality until reaching level 42 for miners and botanists, which unlocks a trait that allows perception to grant a chance of gathering up to 10 additional items for many of these. In Heavensward, Perception also determines the effectiveness of abilities that increase collectability.

-GP: Ability Resource Points used for gathering abilities (though Fishing does not make use of it until Heavensward). Slowly recharges over time while not gathering from resource spots and with each successful gathering attempt. The current amount is shared between classes, though points can be lost if switching to a class with a lower maximum, including any non-gathering class (which lowers it to the base pool without any gear bonuses).
