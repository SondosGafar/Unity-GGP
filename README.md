
# ☁️ Skybound Runner | 3D Platform Runner Game

**Skybound Runner** is a 3D endless platform-running game developed using **Unity and C#**, featuring floating islands, character movement, obstacles, collectible coins, and a survival-based scoring system.

The game challenges players to navigate across floating platforms, time their jumps accurately, avoid obstacles, and survive as long as possible while collecting coins and increasing their score.

## 🎮 Project Overview

Skybound Runner is a fast-paced 3D game centered around movement precision, timing, and obstacle avoidance.

Players control a character traveling across floating platforms suspended in the sky. The gameplay incorporates platform navigation, extended jumping, collectible items, health management, and dynamically arranged obstacles.

The project combines **gameplay programming, physics-based interactions, user interface design, and game-state transitions** within the Unity environment.

### Key Features

- 3D character movement and jumping mechanics
- Extended jumping and speed-based movement
- Floating platforms with variable spacing
- Static and moving platforms
- Platforms that disappear after contact
- Randomly positioned obstacles and collectibles
- Three-life survival system
- Score tracking and coin collection
- Main Menu, How to Play, Gameplay, and Game Over screens
- Restart and main menu navigation
- Dynamic environmental lighting design

## 🕹️ Gameplay Mechanics

### 1. Character Movement

The player controls a 3D character that navigates across floating islands.

The movement system includes:

- Directional movement
- Standard jumping
- Extended jumps using increased movement speed
- Platform-to-platform navigation
- Falling detection

Precise movement and jump timing are essential for successfully crossing gaps between platforms.

### 2. Platform System

The gameplay design includes several platform behaviors:

- **Static Platforms:** Remain stationary during gameplay.
- **Moving Platforms:** Introduce additional navigation challenges.
- **Disappearing Platforms:** Disappear after player contact.
- **Variable Spacing:** Platforms are generated with varying distances within defined limits.

These mechanics create increasingly challenging navigation scenarios.

### 3. Obstacles & Collision Handling

Obstacles include cubes and spikes positioned across the platforms.

Players must avoid dangerous collisions and maintain controlled movement.

The gameplay rules specify:

- Losing one life after falling from a platform.
- Losing one life after remaining in contact with an obstacle for more than three seconds.
- A 10-point penalty for the specified obstacle interaction.

### 4. Scoring & Collectibles

The scoring system rewards successful platform navigation.

| Action | Effect |
|---|---|
| Successfully reaching a platform | +10 points |
| Obstacle penalty | -10 points |
| Collecting a coin | Increases coin count |
| Falling from a platform | Loses one life |
| Losing all three lives | Game Over |

The game interface displays the player's score, collected coins, and remaining lives.

### 5. Game Over System

Each player begins with **three lives**.

When all lives are lost, the game transitions to the Game Over screen.

The Game Over interface displays:

- Final score
- Collected coins
- Restart option
- Return to Main Menu option

The game follows an endless survival format rather than a fixed level-completion objective.

## 🖥️ Game Screens & Navigation

The game includes four main interface screens.

### Main Menu

Provides navigation options for:

- Start Game
- How to Play
- Exit

### How to Play

Introduces the player to movement controls, jumping, and navigation mechanics.

### Gameplay

Displays the interactive 3D world, player character, floating platforms, collectibles, and gameplay statistics.

### Game Over

Appears when the player loses all available lives and offers options to restart or return to the main menu.

### Game Flow

```text
Main Menu
   |
   |-- Start Game
   |      |
   |      v
   |   Gameplay
   |      |
   |      |-- Collect Coins
   |      |-- Navigate Platforms
   |      |-- Avoid Obstacles
   |      |
   |      v
   |   Lives = 0
   |      |
   |      v
   |   Game Over
   |      |
   |      |-- Restart
   |      |-- Main Menu
   |
   |-- How to Play
   |
   |-- Exit
```

## 🎨 Environment & Visual Design

Skybound Runner uses a colorful 3D environment featuring:

- Floating grass-covered islands
- Bright sky and cloud backgrounds
- Stylized character models
- Platform obstacles
- Collectible coins
- Distinct menu and gameplay interfaces

The gameplay design also specifies environmental lighting variations across consecutive sessions, including morning, nighttime, and sunrise settings.

## 🛠️ Technologies Used

| Category | Technology |
|---|---|
| Game Engine | Unity |
| Programming Language | C# |
| Development Environment | Unity Editor |
| Game Systems | Player Movement, Collision Detection, Scoring |
| Interface | Unity UI |
| Development Concepts | Game State Management, Object Interaction, Game Logic |

## 📁 Repository Structure

```text
Unity-GGP/
│
├── Assets/
│   └── Game assets, scenes, and scripts
│
├── Packages/
│   └── Unity package configuration
│
├── ProjectSettings/
│   └── Unity project configuration
│
└── README.md
```

The core Unity project is contained in the `Assets`, `Packages`, and `ProjectSettings` directories.

## 🚀 Getting Started

### Requirements

- Unity Hub
- Unity Editor (compatible with the project version)
- A computer capable of running Unity 3D projects

### Setup

**1. Clone the repository**

```bash
git clone https://github.com/SondosGafar/Unity-GGP.git
```

**2. Open the project in Unity Hub**

- Launch Unity Hub.
- Select **Add Project from Disk**.
- Navigate to the cloned repository.
- Select the project folder.

**3. Open the Unity Editor**

Use the Unity version specified in:

```text
ProjectSettings/ProjectVersion.txt
```

**4. Launch the game**

Open the main menu scene from the Unity project and press the Play button in the Unity Editor.

## 🧩 Technical Concepts Demonstrated

The project provides practical experience with:

- **Object-Oriented Programming:** Developing gameplay components using C#.
- **Game Development:** Implementing interactive mechanics within Unity.
- **Collision Detection:** Handling interactions between the player, platforms, and obstacles.
- **Game State Management:** Transitioning between menu, gameplay, and game-over states.
- **Movement Mechanics:** Controlling player movement, jumping, and speed adjustments.
- **UI Development:** Designing menus, gameplay information displays, and navigation.
- **Gameplay Logic:** Implementing lives, scoring rules, collectibles, and survival conditions.

## 🔮 Future Improvements

Potential extensions include:

- Additional levels and environmental themes
- New obstacle types and movement abilities
- Improved difficulty progression
- Persistent high scores and leaderboards
- Additional character customization options

## 🤝 Project Collaboration

Skybound Runner is a collaborative Unity game development project.

This repository is a fork of the [original Unity-GGP repository](https://github.com/Mariam-Elbishbeashy/Unity-GGP).

The project covers gameplay design, 3D interactions, navigation, user interface flow, and core game mechanics.

## 🏁 Conclusion

Skybound Runner demonstrates the development of an interactive 3D platform-running game using **Unity and C#**.

The project brings together **character controls, obstacle interactions, scoring systems, game-state transitions, and user interface design**, providing practical experience in gameplay development and software engineering concepts.
