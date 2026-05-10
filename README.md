# Multiplayer Ship Destroyer 🚢💥

A real-time multiplayer Battleship game where two players compete to destroy each other’s fleet on a 10x10 grid. Built with turn-based gameplay, live synchronization, and in-game chat functionality.

---

## 🎮 Features

- Real-time multiplayer gameplay
- Automatic matchmaking system
- Random ship placement generation
- 10x10 interactive battle grid
- Turn-based attack mechanics
- Live hit/miss updates
- In-game chat system
- Win/Lose game states
- Responsive UI

---

## 🕹️ How the Game Works

### 1. Player Connection
- When a user opens the game, they automatically join the **Waiting Room**
- The game waits until another player connects
- Once two players are connected, a match starts automatically

### 2. Ship Placement
Each player receives:
- A **10x10 grid**
- 5 randomly placed ships

#### Ship Sizes
| Ship | Size |
|------|------|
| Carrier | 5 |
| Battleship | 4 |
| Cruiser | 3 |
| Submarine | 3 |
| Destroyer | 2 |

---

## ⚔️ Gameplay Rules

- Players take turns attacking opponent coordinates
- Click on the opponent's grid to fire a shot
- Results are shown instantly

### Shot Results
- 🔴 **Red Marker** → Hit
- 🔵 **Blue Marker** → Miss

If the shot misses, the turn passes to the opponent.

---

## 🧩 Game Interface

### Your Grid (Left Side)
- Displays:
  - Your ships
  - Opponent attacks
  - Hit and missed shots

### Opponent Grid (Right Side)
- Used to attack enemy positions
- Hover effects highlight target squares
- Click to shoot

### Chat System
- Real-time communication between players
- Messages appear instantly during gameplay

---

## 🏆 Winning Condition

The first player to destroy all enemy ships wins the game.

---

# 🛠️ Tech Stack

Add your actual stack here.

Example:

- Frontend: HTML, CSS, JavaScript / React
- Backend: Node.js, Express
- Real-time Communication: Socket.io
- Database: MongoDB (if used)

---

# 📂 Project Structure

```bash
project/
│
├── client/
│   ├── src/
│   ├── public/
│
├── server/
│   ├── socket/
│   ├── routes/
│
├── package.json
└── README.md
```

---

# 🚀 Installation & Setup

## Clone Repository

```bash
git clone https://github.com/your-username/multiplayer-ship-destroyer.git
```

## Navigate to Project

```bash
cd multiplayer-ship-destroyer
```

## Install Dependencies

```bash
npm install
```

## Start Server

```bash
npm start
```

---

# 🌐 Multiplayer Flow

1. Player joins game
2. Waiting room searches for opponent
3. Match starts automatically
4. Ships are generated randomly
5. Players attack turn-by-turn
6. Game ends when all ships are destroyed

---

# 📸 Screenshots

Add screenshots here after uploading images.

Example:

```md
![Game Screenshot](./screenshots/game.png)
```

---

# 🔮 Future Improvements

- Manual ship placement
- Friend invite system
- Ranked matchmaking
- Player authentication
- Match history
- Sound effects & animations
- Mobile optimization
- AI bot mode

---

# 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you would like to change.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Rohit Vishwakarma**

Student at Lovely Professional University, Punjab, India.

Passionate about backend development, real-time systems, and multiplayer game architecture.

