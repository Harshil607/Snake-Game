# 🐍 Snake Game in C++

A console-based implementation of the classic Snake Game developed in **C++** using **Object-Oriented Programming (OOP)** concepts. The game features real-time keyboard controls, dynamic snake growth, collision detection, multiple difficulty levels, and score tracking.

---

## 🎮 Features

- Real-time snake movement using keyboard controls
- Three difficulty levels:
  - Easy
  - Medium
  - Hard
- Dynamic snake growth after consuming food
- Score tracking system
- Collision detection with walls and snake's own body
- Random fruit generation
- Restart game option after Game Over
- Console-based graphical interface

---

## 🛠 Technologies Used

- C++
- Object-Oriented Programming (OOP)
- Windows Console API
- `<conio.h>` for keyboard input
- `<windows.h>` for timing and screen control

---

## 📂 Project Structure

```
Snake-Game/
│
├── main.cpp
└── README.md
```

---

## 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/yourusername/snake-game-cpp.git
cd snake-game-cpp
```

### Compile

Using g++ (MinGW)

```bash
g++ main.cpp -o snake
```

### Run

```bash
./snake
```

> **Note:** This project uses `conio.h` and `windows.h`, so it is designed to run on **Windows**.

---

## 🎮 Controls

| Key | Action |
|------|--------|
| W | Move Up |
| A | Move Left |
| S | Move Down |
| D | Move Right |
| X | Exit Game |
| R | Restart after Game Over |

---

## 📖 OOP Concepts Used

- Inheritance
- Encapsulation
- Classes & Objects
- Enumerations
- Function Overriding
- Modular Program Design

---

## ⚙️ Game Logic

- The snake starts from the center of the board.
- Food appears at random locations.
- Every fruit increases:
  - Score by **10 points**
  - Snake length by **1**
- The game ends if the snake:
  - Hits a wall
  - Collides with its own body
- Players can restart the game immediately after a Game Over.

---

## 📸 Gameplay

You can add screenshots or a GIF here after uploading the project.

Example:

```
![Gameplay](images/gameplay.gif)
```

---

## 🔮 Future Improvements

- Wrap-around mode
- High score storage
- Obstacles and power-ups
- Pause/Resume functionality
- Better console graphics
- Cross-platform support using SDL or SFML

---

## 👨‍💻 Author

**Your Name**

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourusername
