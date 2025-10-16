# PACMAN-RL-VS-BC

A Pacman game implementation that compares Reinforcement Learning (DQN) with Behavioural Cloning (Imitation Learning) approaches for game AI.  

> 🧩 **Original project by [Jmansford](https://github.com/jmansford)**  
> 🔧 **Extended and modified by Team Members: Yi Yang, Kaiyue Yang, and Chenle Wang**  
>  
> On top of the original codebase, we added three new gameplay mechanics — **Accelerate**, **Freeze**, and **Invisible** — and completed **reinforcement learning (RL) training** experiments for the DQN agent.

<img src="images/gameplay.png" alt="Game Screenshot" style="width:50%;">

---

## Project Overview

This project builds upon Jmansford’s original Pacman RL framework and extends it with additional features and experiments.  
It provides an environment where Pacman can be controlled by:

1. A **Deep Q-Network (DQN)** trained through reinforcement learning  
2. A **Behavioural Cloning** model trained through imitation learning  
3. Extended gameplay functions to test advanced AI adaptability

The goal is to compare the performance, learning efficiency, and behavior of these two AI approaches under enhanced game dynamics.

---

## New Features Added by Our Team

- **Accelerate Mode** – Pacman can temporarily move faster.
- <img src="images/Accelerate.png" alt="Game Screenshot" style="width:50%;">
- **Freeze Mode** – Freezes ghosts for a short duration.
- <img src="images/Freeze.png" alt="Game Screenshot" style="width:50%;">
- **Invisible Mode** – Makes Pacman invisible to ghosts temporarily.
- <img src="images/Invisible.png" alt="Game Screenshot" style="width:50%;">
- Completed **Reinforcement Learning (RL) training** and evaluation for DQN agents under these new mechanics.

---

## Original Features (from Jmansford)

- Classic Pacman gameplay with ghosts and pellets  
- Two different maze configurations (Simple and Complex)  
- DQN-based reinforcement learning implementation  
- Behavioural Cloning through imitation learning  
- Expert demonstration recording and playback  
- Automated testing framework  
- Enhanced feature extraction for better learning  
- Visual rendering of the game state  

---

## Controls

### Game Modes
- `1`: Switch to HUMAN mode (manual control)  
- `2`: Switch to A_STAR mode (automatic pathfinding)  
- `3`: Switch to DQN mode (reinforcement learning)  
- `4`: Switch to IMITATION mode (behavioural cloning)

### Human Mode Controls
- `↑`: Move up  
- `↓`: Move down  
- `←`: Move left  
- `→`: Move right  

### Game Management
- `M`: Switch between Simple and Complex maze  
- `SPACE`: Restart game (when game over or won)

### New Extended Features
- `F`: Activate **Freeze** mode  
- `I`: Activate **Invisible** mode  
- `X`: Activate **Accelerate** mode  

### Demonstration Recording (when RECORD_DEMONSTRATIONS = True)
- `R`: Start recording demonstration (in HUMAN mode)  
- `T`: Stop recording demonstration  
- `C`: Cancel current recording  
- `A`: Analyse all recorded demonstrations  

---
