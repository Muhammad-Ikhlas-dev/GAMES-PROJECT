# 🎮 GAMES-PROJECT

A full-stack project featuring a **React frontend** and a **Node.js backend**.  
This project demonstrates how to combine a modern UI with **CRUD APIs** to manage game data.

---

## 📂 Project Structure
GAMES-PROJECT/
├── client/ # React frontend
│ ├── src/
│ ├── public/
│ └── package.json
├── server/ # Node.js backend (CRUD APIs)
│ ├── routes/
│ ├── models/
│ └── package.json
└── README.md

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v16+ recommended)
- [npm](https://www.npmjs.com/)

---

### 1. Clone the repository
```bash
git clone https://github.com/Muhammad-Ikhlas-dev/GAMES-PROJECT.git
cd GAMES-PROJECT

cd server
npm install
npm run dev

```
Runs the Node.js backend with CRUD endpoints.
Default URL: http://localhost:5000

3. Setup the Client
Open a new terminal:
```bash
cd client
npm install
npm run dev
```

🔗 API Endpoints

The backend exposes RESTful APIs for managing games.

Method	Endpoint	Description
GET	/games	Get all games
GET	/games/:id	Get a single game
POST	/games	Create a new game
PUT	/games/:id	Update an existing game
DELETE	/games/:id	Delete a game
