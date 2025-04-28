Nani Fullstack Chatbot App


This is a fullstack chatbot project built using:

Frontend: React.js (chatbot-vibe folder)

Backend: Node.js and Express.js (nani-server folder)

The project allows users to chat with an AI chatbot powered by OpenAI API.

📂 Project Structure

ReactApp/
│
├── chatbot-vibe/   → Frontend (React app)
│
├── nani-server/    → Backend (Express server)
│
├── README.md       → This file
│
└── .gitignore      → Files to ignore in Git

✨ Features
Ask any question to the chatbot.

Get instant AI-generated replies.

Fullstack setup: Frontend + Backend connected.

Easy to run locally.

🛠️ How to Run the Project
You need Node.js installed.
(Download it here if needed: https://nodejs.org/)

1. Clone the Project

git clone https://github.com/rthavutu06/NaniAIChatbot.git

cd ReactApp

2. Start the Backend Server

cd nani-server
npm install    # Install backend dependencies
npm start      # Start the server
Server will start on something like http://localhost:5000.

3. Start the Frontend App
Open a new terminal tab (keep the server running), then:

cd chatbot-vibe
npm install    # Install frontend dependencies
npm start      # Start the React app
Frontend will start on http://localhost:3000.

🧠 Notes for Beginners
Backend handles API calls to OpenAI and sends responses.

Frontend displays a chat screen and interacts with the backend.

You must have an OpenAI API key saved in the server’s .env file like:


OPENAI_API_KEY=your_openai_api_key_here

🎯 Technologies Used
React.js (Frontend)

Node.js + Express.js (Backend)

OpenAI GPT API (Chatbot intelligence)

Git & GitHub (Version control)

📬 Contact
If you have any questions, feel free to reach out! 🚀
Rakesh Thavutu | LinkedIn Profile: https://www.linkedin.com/in/rakesh-t-ba0905190/

📢 How to Use
Run the server first (nani-server).

Then run the frontend (chatbot-vibe).

Open your browser and chat with the AI!

⚡ End of README