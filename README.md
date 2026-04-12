#  Tic-Tac-Toe — Android Game

A native Android implementation of the classic Tic-Tac-Toe game, featuring a clean UI, real-time game logic, and persistent score tracking between two players.

---

##  Features

*  **Two-Player Mode**
  Enter player names and play locally on the same device

*  **Interactive Game Board**
  3×3 grid with responsive touch controls

*  **Turn-Based Logic**
  Automatic switching between players with visual indication

*  **Win Detection System**
  Efficient evaluation of all possible winning combinations

*  **Score Tracking**
  Keeps track of wins for both players during the session

*  **Draw Detection**
  Identifies and handles tie scenarios

*  **Restart Match**
  Reset the board instantly after each game

*  **Win Dialog**
  Displays winner or draw message with replay option

---

##  Architecture & Logic

* **Game State Management**

  * Uses an array to track board positions
  * Maintains player turns and move count

* **Winning Logic**

  * Predefined winning combinations
  * Iterative check after each move

* **UI Interaction**

  * Click listeners for each grid cell
  * Dynamic image updates for player moves

* **Activity Communication**

  * Passes player names via `Intent` between screens

---

##  Tech Stack

* **Language:** Java
* **Platform:** Android SDK
* **UI Components:** ImageView, TextView, LinearLayout
* **Architecture Style:** Activity-based

---

##  Screenshots
<p align="center">
<img src="https://github.com/user-attachments/assets/f61487c3-0045-4f5d-af80-f81fec125fda" width="250"/>
<img src="https://github.com/user-attachments/assets/41994902-f7e1-4233-995a-88c876028a97 width="250"/>
</p>



---

##  Getting Started

### 1. Clone the repository

```bash id="3k8f2a"
git clone https://github.com/your-username/your-repo.git
```

### 2. Open in Android Studio

### 3. Run the app

* Use an emulator or a physical Android device

  

