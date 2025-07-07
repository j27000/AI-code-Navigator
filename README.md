AI-code-Navigator

Overview
AI-code-Navigator is a Node.js/Express backend project designed to analyze, summarize, and answer questions about codebases using AI (OpenAI API). It allows users to upload code files or entire repositories, processes them, and stores summaries and code in a MongoDB database. The backend exposes endpoints for uploading code, summarizing it, and querying the codebase with natural language questions.
Additionally, the project contains a sample extracted project, PetAdopt, which is a full-stack web application for pet adoption, featuring user authentication, AI-powered pet matching, admin dashboards, and more.

Features
Code Upload & Summarization: Upload code files or repositories; the backend generates and stores AI-powered summaries.
Natural Language Query: Ask questions about the uploaded codebase and get AI-generated answers.
Repository Extraction: Download and process GitHub repositories as ZIP files.
Database Storage: Stores code, summaries, and metadata in MongoDB.
PetAdopt Example App: Includes a React-based pet adoption platform with authentication, admin/user dashboards, and AI pet matching.
Technologies Used
Backend: Node.js, Express, Mongoose, Multer, OpenAI API, Octokit (GitHub API)
Database: MongoDB
Frontend Example (PetAdopt): React, Firebase, Tailwind CSS

Setup & Usage
Clone the repository
Install dependencies
Apply to git-error-17...
Run
Configure environment variables

Set up your MongoDB URI and OpenAI API key in a .env file.
Run the server
Apply to git-error-17...
Run

Use the API
Upload code files or repositories via the provided endpoints.
Query the codebase using natural language.
Example Endpoints
POST /uploadRepo — Upload a GitHub repository for analysis.
POST /processCode — Upload a single code file for summarization.
POST /searchCode — Ask questions about the uploaded codebase.
PetAdopt Example
The uploads/extracted/ directory contains a sample project, PetAdopt, which demonstrates a real-world React app for pet adoption, including:
User/admin authentication (Firebase)
Pet listings and AI-powered matching
Admin dashboard for managing pets and applications
Shopping cart for favorite pets
Responsive design
License
MIT
Let me know if you want this written to your 
