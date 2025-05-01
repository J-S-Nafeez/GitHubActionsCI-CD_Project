MERN Stack Project with Docker & GitHub Actions
A full-stack web app built with MongoDB, Express.js, React.js, and Node.js, using Docker for containerization and GitHub Actions for CI/CD.

📦 Tech Stack
Frontend: React.js (/Task-Noter)

Backend: Node.js + Express (/notes-app-backend)


CI/CD: GitHub Actions

DevOps: Docker, Docker Compose

🛠️ Setup Instructions
1. Clone the Repo
git clone https://github.com/J-S-Nafeez/GitHubActionsCI-CD_Project.git
cd GitHubActionsCI-CD_Project
2. Add .env Files
Backend (/notes-app-backend/.env)

PORT=5000  
MONGO_URI=mongodb://mongo:27017/mern_db
Frontend (/Task-Noter/.env)

REACT_APP_API=http://localhost:5000
🐳 Run with Docker
docker-compose up --build
To stop:

docker-compose down
🔁 GitHub Actions
CI/CD runs on every push and pull request.
Located at: .github/workflows/deploy.yml

📄 Author
Shaik Nafeez

📧 ahamednafeez70@gmail.com
🌐 GitHub: https://github.com/J-S-Nafeez
🔗Linkedin :www.linkedin.com/in/jammalamadugu-shaik-nafeez

