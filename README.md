EquiTask AI
EquiTask is a task management platform that leverages AI to break down tasks into actionable steps. Managers can assign tasks, and employees receive detailed, simplified instructions to complete them.
Live Links
Backend API: https://real-equitask-backend.onrender.com⁠�
AI Service: https://real-equitask-ai.onrender.com⁠�
GitHub Repo: https://github.com/alagoemelina-collab/Real-Equitask-App⁠�
Tech Stack
Backend: Node.js, Express, MongoDB, JWT, Google OAuth
AI Service: Python, Flask
Deployment: Render
Key Features
User Authentication: Google OAuth, JWT-based login
Employee Onboarding: Email invite flows using Nodemailer
Task Management: Create tasks, track progress, mark steps complete
AI Task Simplification: Use AI to break down tasks into step-by-step instructions
Unit Testing: Jest tests for backend API
How to Set Up and Run
Clone the repo:
Bash
git clone https://github.com/alagoemelina-collab/Real-Equitask-App.git
Install dependencies for the backend:
Bash
npm install
Install dependencies for the AI service:
Bash
pip install -r requirements.txt
Run the backend:
Bash
npm run dev
Run the AI service:
Bash
uvicorn app:app --reload --port 8000
Testing
Backend:
Test API endpoints for:
Authentication: /api/auth/register, /api/auth/login
Task creation and management: /api/tasks, /api/tasks/:taskId
AI Service:
Test the AI route for task simplification:
Plain text
POST /api/ai/simplify-task
Provide a task description to get simplified steps.
Author
Alago Nzube Emelina
LinkedIn⁠�
