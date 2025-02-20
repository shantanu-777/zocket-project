# Todovex - AI-Powered Task Management System

## Overview
Todovex is a powerful and intelligent task management system designed to help individuals and teams organize, prioritize, and automate their daily tasks efficiently. With AI-powered recommendations, real-time updates, and a seamless user experience, Todovex transforms productivity like never before.

## Features
- **AI-Powered Task Suggestions**: Get smart recommendations for task prioritization.
- **Real-time Synchronization**: Stay updated across multiple devices.
- **Intuitive UI/UX**: A clean and modern interface for seamless task management.
- **Project & Task Organization**: Categorize tasks with labels, deadlines, and priorities.
- **Collaboration & Sharing**: Share tasks with team members and track progress.
- **Secure Authentication**: JWT-based user authentication for secure access.
- **Dark Mode Support**: Enhance usability with light and dark themes.

## Tech Stack
### Backend:
- Golang (Gin/Fiber)
- PostgreSQL/MongoDB
- JWT Authentication
- WebSockets for real-time updates
- OpenAI/Gemini API for AI recommendations
- Deployed on Render/Fly.io

### Frontend:
- TypeScript
- Next.js (App Router)
- Tailwind CSS
- Real-time updates & authentication
- Deployed on Vercel

## Installation & Setup
### Prerequisites:
- Node.js & npm
- Golang
- PostgreSQL/MongoDB

### Steps:
1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/todovex.git
   cd todovex
   ```
2. **Backend Setup**
   ```sh
   cd backend
   go mod tidy
   go run main.go
   ```
3. **Frontend Setup**
   ```sh
   cd frontend
   npm install
   npm run dev
   ```

## Deployment
- **Frontend**: Deploy using Vercel
- **Backend**: Deploy using Render/Fly.io

## Contribution
Contributions are welcome! Feel free to open issues and pull requests.

## License
This project is licensed under the MIT License.



