# Milestone 1 ASSUMPTIONS
* Character starts the game with the following stats:
    - Position: Hero’s Castle
    - Health points: 100
    - Experience points: 0
    - Gold: 15 gold
    - Equipment: nothing
    - Speed: 20 points

* Slug has the following stats:
    - Type: Standard
    - Health: 5 points
    - Damage: 5  points
    - Battle Radius: 5 distance units.
    - Support Radius: 5 distance units.
    - Speed: 5 points

* Character gets the following rewards upon beating a slug:
    - 1 Card
    - 5 Experience points
    - 5 Gold
    - 0 Equipment

## ENEMIES
* Zombie has the following stats
    - Type: Moderate
    - Health: 5 points
    - Damage: 7  points
    - Battle Radius: 7 distance units.
    - Support Radius: 5 distance units
    - Speed: 3 points

* Character gets the following rewards upon beating a zombie:
    - 1 Card
    - 7 Experience points
    - 7 Gold
    - Random Defence gear

* Vampire has the following stats
    - Type: Aggressive
    - Health: 10 points
    - Damage: 9  points
    - Battle Radius: 7 distance units.
    - Support Radius: 8 distance units
    - Speed: 8 points

* Character gets the following rewards upon beating a Vampire:
    - 2 Cards
    - 9 Experience points
    - 7 Gold
    - Random Weapon

## ITEMS
* Sword has the following stats:
    - Type: Standard, Weapon
    - Increase in Damage to Slug: 3  points
    - Increase in Damage to Zombies: 3  points
    - Increase in Damage to Vampire: 3  points
    - Price: 5 gold

* Stake has the following stats:
    - Type: Standard, Weapon
    - Increase in Damage to Slug: 2  points
    - Increase in Damage to Zombies: 2  points
    - Increase in Damage to Vampire: 5  points
    - Price: 7 gold

* Staff has the following stats:
    - Type: Standard, Weapon
    - Increase in Damage to Slug: 1  points
    - Increase in Damage to Zombies: 1  points
    - Increase in Damage to Vampire: 1  points
    - Price: 5 gold

* Armour has the following stats:
    - Type: Standard, Defence
    - Reduces ALL enemy damage by 50%
    - Price: 7 gold

* Shield has the following stats:
    - Type: Standard, Defence
    - Reduction in slug attack damage: 1 point
    - Reduction in zombie attack damage: 2 points
    - Reduction in vampire attack damage: 3 points
    - Price: 7 gold

* Shield has the following stats:
    - Type: Standard, Defence
    - Reduction in slug attack damage: 0.2 x slug damage
    - Reduction in zombie attack damage: 0.3 x zombie damage
    - Reduction in vampire attack damage: 0.4 x vampire damage
    - DECREASE in character damage dealt by 1 damage point
    - Price: 5 gold

* Health cost on menu is 8 gold.

* RARE item can ONLY be received by chance of winning a battle.

## BUILDINGS
* Shooting radius of tower is 5 distance points.

* Damage of tower is 2 damage points on enemy.

* Assumed passing through village causes character to gain 5 health points

* Campfire has a battle radius of 10 distance points

## ALLIED SOLDIER
* Allied soldier has the following stats:
    - 5 health points
    - 3 damage points

## GENERAL/RULES

* Maximum number of equipment the character can store in inventory is 16 pieces

* 1 health potiion regains health fully.

* Character may only sell what is not currently equipped. Equipped items can't be sold.

* A trance (an attacking enemy is transformed into an allied soldier temporarily) affects all basic enemies.

* Standard Allied soldiers will always have a speed equal to that of the character.

* Allied soldier can not have armour, helmet or any weapons.

* Selling price of an item at Hero’s Castle is the same as the buying price of that item. 

* When the character has equipped a helmet, when the character fights a slug, then all the slug attacks deal 20% less damage, when the character fights a zombie, then all the zombie attacks deal 30% less damage and when the character fights a vampire, then all the vampire attacks deal 40% less damage.

* Allied soldiers fight before the character, so they have to die before the character dies.

# ASSUMPTIONS ADDED IN MILESTONE 2
* The vampire castle spawns vampires on the 5th, 10th, 15th... cycles regardless of when they were placed.
    For example, a vampire castle spawned on the second round will still spawn vampires on the 5th, 10th, 15th...
    round and not the 7th, 12th, 17th... rounds.

* Character may have multiple defensive items but only one character

* If character is within radius of two campfires, only one campfire boosts its stats

* Tower shoots all enemies in its radius at the same time (more than one archer)

* Trance lasts for 5 seconds

* Two buildings should not be allowed to be placed on the same position [YET TO BE IMPLEMENTED]

* When an enemy is in the support radius of another enemy who is in battle, they will fight from where 
    they are and not move towards the actual fight

* When placing a building, if the building is placed on the area for which it is not allowed to be, the card
    returns to the same place at the bottom of the screen

* CHANGED BATTLE RADII AND SUPPORT RADII: Made them 1/10 multiplied by the values asserted in Milestone 1

* A battle ends when either the character or the enemy dies. It is not a case of simply one attack each and move on.

* Character may never be in two battles at once; if the character enters the battle radius of two enemies at the same
    time, then they fight the enemy who spawned first.

* CHANGED: character attack damage reduced by 3 points to make the game more fair.

* A health potion may not be bought when the character health is 100

* If the character receives a health potion from the path when they have 100 health then they will be 
    instead rewarded with 8 gold.

# ASSUMPTIONS ADDED IN MILESTONE 3
* Doggie appears every 20 cycles

* Doggie moves in a random motion, and high health

* Doggie stuns the character and prevent the character from making the attack temporarily.So, characters first attack will be nullified i.e the when the character is in a battle with the Doggie then it can't make its first attack to the Doggie and will start the attack after the second attack of the Doggie, it will apply to attacks with the other enemies in its Support radii as well.

* Elan has the ability to heal other enemy NPCs 

* Elan spawns after 40 cycles(every 40th cycle) and character has reached 10000 experience points.

* The health points of the enemies gets increased by 5 points when the enemies move from the support radius of the elan muske. 

* HEALTH PORTION IN MENU INCREASES CHARACTER HEALTH BY 20 WHEN BOUGHT. Not like in milestone 2, where it simply resotred full health.

* There can be at most 3 rare items, if a new rare item is added then the oldest one is replaced

* Anduril, Flame of the West:
    Damage points against normal enemies - 3 points.
    Damage points against the Bosses - 9 points.
    Causes triple damage against the bosses

* Tree Stump: 
    Defence points against normal enemies: 0.3 setdamage for this weapon against any enemy attack.
    Defence points against the Bosses: 0.8 against bosses.
    Causes higher defence(assumption) against the bosses

* If there are no bosses in the world and if the character attains all the other goals then the character can win the game.

* Added an assumption that when the character is in a battle with an enemy and there are other enemies as well which are present within the support radius then chracter primarily fights a battle with the enemy in the battle radius, then fights a battle with a enemy in its support radii in the order of increasing raddi until either the character is dead or all the enemies in the support raddi are dead.

* Confusing mode bears a standard mode menu as the mode has no effect on purchasing items in shop.