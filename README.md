AI-code-Navigator
AI-code-Navigator is a Node.js/Express backend that helps developers analyze, summarize, and query codebases using AI (OpenAI API). It lets you upload files or whole repos, then generates summaries and answers your natural language questions about the code.

This project also includes PetAdopt, a full-stack example app for pet adoption, with user auth, AI-powered pet matching, and admin tools.

🚀 Features
Upload & Summarize Code: Upload code files or GitHub repos; get AI-generated summaries stored in MongoDB.

Natural Language Search: Ask questions about your codebase and get AI answers.

Repo Extraction: Download GitHub repos as ZIP files and process them.

PetAdopt Example: React-based adoption app with Firebase auth, AI matching, dashboards, and a responsive UI.

🛠️ Tech Stack
Backend: Node.js, Express, Mongoose, Multer, OpenAI API, Octokit (GitHub API)
Database: MongoDB
Frontend Example (PetAdopt): React, Firebase, Tailwind CSS

📂 Setup & Run
Clone the repo

bash
Copy
Edit
git clone <your-repo-url>
cd AI-code-Navigator
Install dependencies

bash
Copy
Edit
npm install
Add environment variables

Create a .env file:

ini
Copy
Edit
MONGO_URI=<your-mongodb-uri>
OPENAI_API_KEY=<your-openai-api-key>
Run the server

bash
Copy
Edit
npm start
📌 Example API Endpoints
POST /uploadRepo — Upload and analyze a GitHub repo.

POST /processCode — Upload a single code file for summarization.

POST /searchCode — Query the uploaded codebase with natural language.

🐶 PetAdopt Example App
Inside uploads/extracted/, you’ll find PetAdopt:

User/admin auth (Firebase)

Pet listings and AI pet matching

Admin dashboard to manage pets & applications

Shopping cart for favorite pets

Fully responsive with Tailwind CSS

📜 License
MIT

✨ Author
Naman Jhala
Portfolio | LinkedIn | Resume
