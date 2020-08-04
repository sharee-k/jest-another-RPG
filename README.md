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