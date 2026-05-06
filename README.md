# 🐍 Snake Game

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

A modern Snake Game built with **Node.js**, **Express**, **MongoDB**, and **Vanilla JavaScript**.

</div>

---

# 📖 Project Description

This project is a full-stack Snake Game application where players control a snake, collect food, increase their score, and store scores in a MongoDB database.

The game includes:

- 🎮 Interactive gameplay
- 📈 Real-time score tracking
- 🏆 Leaderboard system
- 💾 MongoDB database integration
- 🌐 Express.js backend server
- 🎨 Responsive frontend design

---

# 🚀 Technologies Used

| Category | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | Node.js, Express.js |
| Database | MongoDB, Mongoose |
| Package Manager | npm |
| Version Control | Git & GitHub |
| Development Tools | VS Code, PowerShell |

---

# 📂 Project Structure

| Folder/File | Purpose |
|---|---|
| `public/` | Frontend files (HTML, CSS, JS) |
| `server/` | Backend server files |
| `models/` | MongoDB database models |
| `routes/` | API routes |
| `package.json` | Project dependencies and scripts |
| `server.js` | Main server entry point |

---

# ⚙️ Requirements

Before running the project, make sure you install the following:

| Requirement | Download |
|---|---|
| Node.js | https://nodejs.org |
| MongoDB Community Server | https://www.mongodb.com/try/download/community |
| Git | https://git-scm.com/downloads |
| VS Code (Recommended) | https://code.visualstudio.com |

---

# 📦 Required Dependencies

The following dependencies are installed automatically using:

```bash
npm install
```

### Main Dependencies

| Package | Purpose |
|---|---|
| express | Backend web framework |
| mongoose | MongoDB connection |
| cors | Cross-origin requests |
| body-parser | Request parsing |

---

# 🛠️ Step-by-Step Installation Guide

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/SnakeGame.git
```

---

## 2️⃣ Open the Project Folder

```bash
cd SnakeGame
```

---

## 3️⃣ Install Dependencies

```bash
npm install
```

---

## 4️⃣ Start MongoDB

Make sure MongoDB service is running.

Windows Command:

```powershell
net start MongoDB
```

---

## 5️⃣ Run the Project

```bash
npm start
```

---

## 6️⃣ Open the Game in Browser

Open:

```text
http://localhost:3000
```

---

# 🎮 How To Play

| Key | Action |
|---|---|
| ⬆️ Arrow Up | Move Up |
| ⬇️ Arrow Down | Move Down |
| ⬅️ Arrow Left | Move Left |
| ➡️ Arrow Right | Move Right |

### Objective

- Eat food to grow the snake
- Increase your score
- Avoid hitting walls or your own body

---

# 🧠 Backend Features

| Feature | Description |
|---|---|
| REST API | Handles score requests |
| MongoDB Storage | Saves player scores |
| Score Validation | Prevents invalid input |
| Leaderboard | Returns top scores |

---

# 🗄️ MongoDB Database

### Database Name

```text
snakegame
```

### Collection Name

```text
scores
```

Example Document:

```json
{
  "name": "Player",
  "score": 14,
  "date": "2026-05-07"
}
```

---

# 🔌 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/scores` | Get top 10 scores |
| POST | `/api/scores` | Save a new score |

---

# 📸 Game Features

✅ Snake movement

✅ Food collection

✅ Score tracking

✅ MongoDB score saving

✅ Leaderboard system

✅ Game over detection

✅ Express backend integration

---

# 🐞 Troubleshooting

| Problem | Solution |
|---|---|
| `npm` not recognized | Install Node.js |
| MongoDB not connected | Start MongoDB service |
| `localhost:3000` not opening | Make sure server is running |
| Port already in use | Restart terminal/server |

---

# 👨‍💻 Author

**Mohamad Diab**

GitHub Repository: `SnakeGame`

---

# 📄 License

This project is created for educational and learning purposes.

