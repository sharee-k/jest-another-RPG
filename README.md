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

10.3.4 states that there should be 11 passing tests. I have re-read this lesson twice, and there are only 10 tests at this point. 10.3.3 Matches the number of tests from the beginning of the section (5 tests) to the end of the section (7 tests). Starting 10.3.4 we have 7 tests. We only write 3 more during this section. I believe that is only 10 tests. Again, typos are delaying progression through the module because I am re-reading and re-working code to make sure I haven't missed something.