# Ticket_Support

Overview
This project is an AI-driven customer support ticket system that automatically categorizes, routes, and responds to support tickets in real time. Built with simplicity and efficiency in mind, it leverages a locally hosted LLM (Gemma) to process incoming tickets and streamline customer support workflows.

Features
Ticket Submission – Clean, user-friendly form for submitting support issues.

AI Categorization – Uses a local LLM (Gemma) to classify tickets into Technical, Billing, Urgent, or General categories.

Automated Response Generation – Dynamically generates suggested responses based on ticket category.

Live Ticket Queue – Displays all current tickets with status, category, and AI-generated responses.

Analytics Dashboard – Real-time metrics including total tickets, AI accuracy, average response time, and time saved. Includes interactive charts.

Local Deployment – Powered by a local LLM via API (no paid services or cloud dependency).

Tech Stack
Front-End: HTML, CSS, JavaScript

AI Integration: Local API using Ollama and Gemma (Google DeepMind) LLM

Charts & Visualization: Chart.js

How It Works
User submits a ticket via the form.

Ticket content is sent via API to the local Gemma model.

The AI processes the input and returns a one-word category.

The system assigns the ticket category, generates a response, and routes the ticket automatically.

Metrics and visualizations update in real time.

Setup Instructions
Clone this repository.

bash
Copy
Edit
git clone https://github.com/yourusername/ai-support-ticket-system.git
Start your local LLM server (e.g., using Ollama) with the Gemma model.

bash
Copy
Edit
ollama run gemma
Open ai-support-system.html in your browser.

Note: The API call in the code is configured for http://localhost:11434/api/generate. Adjust as needed based on your local setup.

Demo
Watch a live demo: https://www.loom.com/share/b0fb9b859944404ab4b1e1eeb2ea87d0?sid=abfa6918-d49e-4acf-99af-e7c6b3bb6924
