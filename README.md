# 🎮 Tic Tac Toe Game  

This is a **Tic Tac Toe game** implemented in **C++**. The game supports three different modes:  
- ✅ **Player vs Player** (PVP)  
- ✅ **Player vs Computer** (PVC)  
- ✅ **Computer vs Computer** (CVC)  

---

## 🚀 How It Works  
The game is built using C++ with a structured design:  
- A header file `tic.h` contains common functions and definitions.  
- Three separate `main` functions handle different modes of the game:  
  - `main1.cpp` → Player vs Player  
  - `main2.cpp` → Player vs Computer  
  - `main3.cpp` → Computer vs Computer  

### 🧠 Game Logic  
- The game is played on a 3x3 board.  
- Players take turns placing their symbol (`X` or `O`) on the board.  
- The game checks for a win or a draw after each move.  
- The computer's moves in PVC and CVC modes are generated using a **random number generator**.  

---

## 📁 Project Structure  
```plaintext
├── tic.h              # Header file containing common functions and definitions
├── main1.cpp          # Player vs Player mode
├── main2.cpp          # Player vs Computer mode
├── main3.cpp          # Computer vs Computer mode
├── game.cpp           # Core game logic
├── utils.cpp          # Helper functions
├── README.md          # Project documentation
