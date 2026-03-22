# Software-dev-2-assignment-Mario-Game-
## Table of Contents

- [Project Overview](#1-project-overview)
- [Project Breakdown (SDLC)](#2-project-breakdown-sdlc)
- [Game Concept / Story](#3-game-concept--story)
- [Target Audience](#4-target-audience)
- [User Profiles](#5-user-profiles)
- [User Requirements](#6-user-requirements)
- [System Requirements](#7-system-requirements)
- [Game Rules & Mechanics](#8-game-rules--mechanics)
- [Game Design](#9-game-design)
- [Technology Used](#10-technology-used)
- [Development Strategy](#11-development-strategy)
- [Scrum Backlog](#12-scrum-backlog)
- [Project Management](#13-project-management)
- [Testing](#14-testing)
- [Challenges & Solutions](#15-challenges--solutions)
- [Evaluation](#16-evaluation)
- [References](#17-references)

## 1. Project Overview

This project is a 2D platformer that draws inspiration from classic games like Mario. The goal is to develop a straightforward game in which the player advances through a level, avoids obstacles, and gathers coins.

The entire software development process—including planning, design, implementation, and testing—is illustrated in this project. The primary goal is to develop a platformer's fundamental mechanics, including movement, jumping, and collision detection.

---
## 2. Project Breakdown (SDLC)

**Planning**  
Researched platformer games and decided on core features.

**Design**  
Planned player movement, level layout and game mechanics.

**Development**  
Implemented the game using Unity and C# scripts.

**Testing**  
Tested gameplay and fixed bugs such as collision issues.

**Deployment**  
Prepared the final version for submission.

---
## 3. Game Concept

The game is a side-scrolling platformer where the player must move from the start of the level to the end. The player must jump across platforms and avoid falling or hitting obstacles.

The game is inspired by retro platform games but uses original assets and simple design.

---
## 4. Target Audience

The game is aimed at casual players who enjoy simple and easy-to-play platform games. The controls are basic so the game can be played by people with different levels of experience.

---
## 5. User Profiles
---
## 6. User Requirements

- The player should be able to move left and right  
- The player should be able to jump  
- The player should be able to collect coins  
- The player should avoid enemies  
- The player should be able to restart after losing  

**User Stories**

- As a player, I want to jump so that I can reach platforms  
- As a player, I want to collect coins so that I can increase my score  
- As a player, I want to avoid enemies so that I don’t lose the game  

---

## 7. System Requirements

- The system must detect keyboard input  
- The system must implement gravity and jumping  
- The system must detect collisions  
- The system must update and display the score  
- The system must render the game in real time  
- The system must reset the game when the player loses  

---
## 8. Game Rules & Mechanics

The game is a side-scrolling platformer where the player moves from left to right.

- The player can move and jump  
- Platforms are used to navigate the level  
- Coins increase score when collected  
- Enemies must be avoided  
- Touching an enemy results in game over  
- The level is completed when the player reaches the end  

---

## 9. Game Design

### Player

The player is controlled by the user and can move left, right and jump.

### Environment

The level consists of platforms placed at different heights. The player must navigate across them to progress.

### Gameplay Loop

Move → Jump → Avoid falling → Reach end → Restart

---

## 10. Technology Used

**Game Engine:** Unity  
**Programming Language:** C#  

**Tools:**
- Unity Editor  
- Visual Studio  
- GitHub  

Unity was chosen because it provides built-in physics and tools for 2D game development, making it easier to implement core mechanics.

---
## 11. Development Strategy

The project is developed using an iterative approach.

Features are added step by step starting with basic movement, then jumping, followed by platforms, enemies and scoring. This allows testing at each stage.

---

## 12. Scrum Backlog

| Task | Priority | Description | Status |
|-----|-----|-----|-----|


---

## 13. Project Management

### Development Log

**Week 1**  
Set up project and planned features.

**Week 2**  
Created game window and player.

**Week 3**  
Implemented movement and jumping.

**Week 4**  
Worked on collisions and level design.

**Week 5**  
Added enemies and coins.

**Week 6**  
Testing and bug fixing.

---

### Development Meetings

**Meeting 1**  
 

**Meeting 2**  
 

**Meeting 3**  


---

## 14. Testing

| Test | Expected Result | Result |
|-----|-----|-----|
Move left/right | Player moves correctly | Pass |
Jump | Player jumps and lands | Pass |
Collect coin | Score increases | Pass |
Hit enemy | Game over triggered | Pass |
Reach end | Level completes | Pass |

---

## 15. Challenges & Solutions

One challenge was implementing collision detection between the player and platforms. This caused issues where the player would fall through objects.

This was fixed by adjusting collision logic and testing different values.

Another challenge was getting the jump mechanics to feel smooth, which required adjusting gravity and jump strength.

---

## 16. Evaluation

The project successfully demonstrates the core mechanics of a platform game including movement, jumping and collision detection.

The main strength is that the game is functional and demonstrates key programming concepts.

A limitation is that the game is quite simple and only includes one level. In the future, more levels and improved graphics could be added.

---

## 17. References

- Research into platform games such as Mario  
- Online tutorials on 2D game development  
- Pygame documentation  

