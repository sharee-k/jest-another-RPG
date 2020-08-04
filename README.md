# jest-another-RPG

Create Potion Object
Create tests for the potion object
The potion object will be used to give the player stat boosts
If no stat is provided, the stat should be randomly selected

Create Player Object
A player object has the following properties:
Name
Health
Strength
Agility
A player object has the following methods:
getStats()
getInventory()
getHealth()
getAttackValue()
isAlive()
addPotion()
usePotion()
reduceHealth()
Write appropriate tests for the Player() constructor and methods

Create Enemy Object
An enemy object has the following properties:
Name
Weapon
Health
Strength
Agility
Potion
An enemy object has the following methods:
getDescription()
getHealth()
getAttackValue()
isAlive()
reduceHealth()
Write appropriate tests for the Enemy() constructor and methods

Create Game Object
All game logic is encompassed by a Game() constructor function
Game object has the following properties:
roundNumber
isPlayerTurn
enemies
currentEnemy
Game object has the following methods:
initializeGame()
battle()
checkEndOfBattle()
startNewBattle()

Consolidate Code

10.1.4 is terribly written and jumps from doing a random test to check if two numbers are equal to writing a test for the potion object. There is no transition just jumps around. There is no continuity and makes it difficult to follow. It made me think that I had missed something in the module, so I wasted time re-reading when I could have just moved on to the next page of the module.