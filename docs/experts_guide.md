# Expert's Guide

## Weapons
In castlio there are three types of weapons.

* **Short range** - swords, hammers, battle axes and close combat weapons
* **Long range** - bows and crossbows you'll find here.
* **Magic weapons** - staffs, wands and rods and anything mana related

Good weapon is also a group of warriors, for example to kill a knight in
chestplate you'll need two mages or two gem sword holders. Look at
[items table](items.md) for damage and protection details for those items.

## Mana and water bars
Mana and water bars are located under your health and hunger bar. First decreases
water bar and if it is empty, then mana bar decreases. Mana bar is useful for
magic weapons. Each magic wand has is a different deadly weapon. Each of these
wands take different amount of mana to operate. If your mana is too low, you
can not use your magic weapons. To increase water bar, one must eat fruits,
eggs and vegetables.

## Looting
### World loot
Each biome has its usual blocks, for forest that are trees, for field it is
grass. However some biomes have unique items that spawn inside them.

Stones and bush are especially useful in the early game, when you don't have
the tools necessary to mine rocks and cut trees. When you are hungry or thirsty,
look for berries and ponds. Lastly, if you want to craft better gear, ores and
gems will be helpful.

| Biome    | Loot   |
| -------- | ------ |
| Sea      | -      |
| Shore    | stones |
| Jungle   | pond   |
| Field    | bush   |
| Snow     | gem    |
| Forest   | berry  |
| Mountain | ore    |
| Fire     | -      |
| Cave     | -      |

### Mobs
When you kill a [mob](mobs.md) you receive loot as a reward. Loot from mobs
is always the same and is described in mobs table. This is contrast to
chest loot which is assigned at the start of the game randomly.

### Chests
The mechanism that assigns loot to chests is quite simple. All chests have
theoretical rarity value, which is 16. When filling a chest, chest choses random
rarity and random item of that rarity. If chest can hold that item, it is put in
there and another item is selected. This cycle continues until chest is full or
it can not hold item of selected quality. In normal chests generate items of
rarity 1 to 4 and in locked chests 5 to 8.

| Rarity | Items
| ------ | -----
| 1 | Stick, wood, stone
| 2 | Leather, metal, string
| 3 | Coin, gem, consumable
| 4 | Key, hat, belt
| 5 | Weapon
| 6 | Armor
| 7 | Magic weapon
| 8 | Shiny gem, bomb

## Honorable uncraftable mentions
You will not find crafting recipe for these items and blocks:

* Bombs - destroys block much much faster
* Tombstone - when player dies, tombstone is created
* Food - steaks, apples and other consumable items
