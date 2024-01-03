# RPG - Dragon Repeller
![image](https://github.com/YorkieDev/DragonRepellerRPG/assets/42919623/4f1d252e-8870-4025-be28-8df702748171)


Welcome to Dragon Repeller! This is a simple Role Playing Game (RPG) where your mission is to defeat the dragon that is preventing people from leaving the town.

## Table of Contents

1. [Introduction](#introduction)
2. [Game Overview](#game-overview)
3. [Technologies Used](#technologies-used)
4. [How to Play](#how-to-play)
5. [Game Logic](#game-logic)

## Introduction

Dragon Repeller is an RPG game developed as part of the "Learn Basic JavaScript by Building a Role Playing Game" course from [freeCodeCamp](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/). The game is built using HTML, CSS, and JavaScript and is designed to be a fun and interactive experience. This is a Guided Project where I had to solve various tasks throughout the course provided by freeCodecamp. 

## Game Overview


![DemoRPGDRAGON](https://github.com/YorkieDev/DragonRepellerRPG/assets/42919623/9de7802a-e0fb-4135-bf2d-87926039f1a7)


- **Objective**: Defeat the dragon that is terrorizing the town.
- **Game Elements**: 
  - Player stats (XP, Health, Gold)
  - Inventory system
  - Various weapons
  - Multiple monsters to fight
- **Locations**: Town square, Store, Cave, and more.

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Play

1. Clone the repository to your local machine.
2. Open the `index.html` file in a web browser.
3. Follow the on-screen instructions to navigate through the game.

## Game Logic

The game is structured around various game states or locations. Each location has different actions available to the player, such as buying items, fighting monsters, or navigating to other locations. The game uses event listeners in JavaScript to handle button clicks and update the game state accordingly.

### Key Functions

- `goTown()`: Navigate to the town square.
- `goStore()`: Navigate to the store.
- `goCave()`: Navigate to the cave.
- `fightDragon()`: Initiate a fight with the dragon.
- `buyHealth()`: Buy health using gold.
- `buyWeapon()`: Buy weapons using gold.
- `attack()`: Perform an attack during a fight.
- `dodge()`: Dodge an attack during a fight.
- `defeatMonster()`: Handle the logic for defeating a monster.
- `lose()`: Handle the game over scenario when the player loses.
- `winGame()`: Handle the game over scenario when the player wins.

