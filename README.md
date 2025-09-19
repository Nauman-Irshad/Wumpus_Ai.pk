# Wumpus_Ai.pk 
👥 Contributor
-Nauman Irshad Ali Shah (Student at UCP) → [GitHub Profile](https://github.com/Nauman-Irshad)   

A Wumpus World Simulator developed in Javascript, HTML and CSS

# 🏹 Wumpus World Simulator

**Hunt the Wumpus** is a classic computer game based on a hide-and-seek adventure.  
This simulator provides an interactive grid-based environment where an agent explores, collects gold, and avoids deadly traps.

---

## 🌍 Environment Setup
- Creates a **grid-based world** (default 4×4, configurable).
- Each cell can contain:
  - **Wumpus** (monster 🐉)
  - **Pit** (hole 🕳️)
  - **Gold** (treasure 💰)
  - **Empty space**

---

## 👀 Percepts Provided to the Agent
- **Stench** → near the Wumpus.  
- **Breeze** → near a Pit.  
- **Glitter** → Gold is in the same cell.  
- **Bump** → agent hits a wall.  
- **Scream** → Wumpus is killed.  

---

## 🎮 Agent Actions
- **Move Forward**  
- **Turn Left / Right**  
- **Grab** (pick up Gold)  
- **Shoot Arrow** (to kill Wumpus)  
- **Climb** (exit the cave)  

---

## 🔄 Simulation Flow
1. Setup the world layout (manual or randomized).  
2. Agent explores step by step, receiving **percepts**.  
3. Based on percepts, the **agent decides actions** using logic or rules.  
4. Simulator updates the world state and **visualizes results**.  

---

## 🎯 Goal
- Safely **navigate the world**.  
- **Grab the Gold**.  
- **Climb out** of the cave.  
- Avoid Pits and the Wumpus.  

---

## 🏆 Scoring (common implementation)
- **+1000** → exit with Gold.  
- **-1000** → death (Wumpus or Pit).  
- **-1** → per action (to encourage efficiency).  
- **-10** → shooting arrow.  
## Screenshot

<kbd>
  <img class="screenshot" src="https://raw.githubusercontent.com/thiagodnf/wumpus-world-simulator/master/img/screenshot.png"/>
</kbd>

## Questions or Suggestions
Feel free to create <a href="https://github.com/thiagodnf/wumpus-world-simulator/issues">issues</a> here as you need

## Contribute
Contributions to the this project are very welcome! We can't do this alone! Feel free to fork this project, work on it and then make a pull request.
