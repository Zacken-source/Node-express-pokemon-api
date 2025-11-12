# Node-express-pokemon-api

A simple **Node.js + Express** REST API that serves sample Pokémon data.  
This project is meant for learning backend fundamentals with Express — routes, parameters, and local data handling.

---

## 🚀 Features

- Node.js + Express backend
- Simple routing system
- Dynamic route parameters
- Local mock data (Pokémon list)
- Easy to extend into a full REST API (GET, POST, PUT, DELETE)

---

## 🗂 Project Structure

.
├── app.js # Main server file
├── mock-pokemon.js # Local Pokémon data
├── package.json
├── package-lock.json
└── .gitignore

yaml
Copier le code

---

## ⚙️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Zacken-source/Node-express-pokemon-api.git
   cd Node-express-pokemon-api
Install dependencies:

bash
Copier le code
npm install
Start the server:

bash
Copier le code
node app.js
Open your browser and go to:

arduino
Copier le code
http://localhost:3001
🧠 Example Endpoints
Method	Route	Description
GET	/	Returns a welcome message
GET	/api/pokemons/:id	Returns Pokémon by ID

Example:

bash
Copier le code
GET http://localhost:3001/api/pokemons/1
Response:

nginx
Copier le code
Vous avez demandé le Pokémon : Bulbizarre
🧰 Tech Stack
Node.js

Express.js

🧑‍💻 Author
Zacken-source
GitHub Profile

📄 License
This project is open source and available under the MIT License.

yaml
Copier le code

---

### ✅ How to add it to your repo

In your project root, create a file named **`README.md`**, paste this text, then run:

```bash
git add README.md
git commit -m "Add English README"
git push origin main