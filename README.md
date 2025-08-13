CyberLens – Smart Collaboration & Learning Platform

📝 Project Overview
CyberLens is a secure, real-time collaboration platform designed for educators and students.
It offers user authentication, secure session management, real-time chat, and document sharing with summaries.
The system is built with a strong focus on cybersecurity best practices.

🚀 Features
Secure User Authentication – Firebase Auth + JWT Tokens

Session Creation & Management – Educators create unique access codes

Real-time Chat – Socket.IO integration

Document Upload & Summarization – File storage with auto summary feature

Cybersecurity Hardening – API protection, input validation, vulnerability scans

🛠 Tech Stack
Frontend: React, Vite, TailwindCSS
Backend: Node.js, Express.js, MongoDB
Security Tools: OWASP ZAP, Snyk CLI, Postman, ESLint
Others: Socket.IO, Firebase Admin SDK, NanoID

🔒 Security Practices Implemented
Added JWT middleware for all private API routes

Implemented input validation using express-validator

Performed API penetration testing using Postman & OWASP ZAP

Scanned dependencies with Snyk CLI

Applied secure coding guidelines to prevent XSS, SQL Injection, CSRF attacks

📂 Installation & Setup
bash
Copy
Edit
# Clone the repository
git clone https://github.com/YOUR_USERNAME/CyberLens.git
cd CyberLens

# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install

# Add environment variables in .env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
MONGO_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret

# Run backend
cd ../server
npm run dev

# Run frontend
cd ../client
npm run dev
📊 My Role & Contributions
As the Developer & Cybersecurity Tester, I:

Designed and implemented full-stack functionality (Frontend + Backend)

Integrated Firebase Auth and JWT-based authentication

Developed secure session and chat system

Conducted security code audits & vulnerability scans

Fixed security issues and documented the improvements

Created final security report for deployment readiness

🧪 Testing & Security Verification
Postman – Tested all API endpoints (login, sessions, chat, upload)

OWASP ZAP – Scanned for vulnerabilities in API and frontend

Snyk CLI – Checked for dependency vulnerabilities

Manual Code Review – Fixed missing validations, JWT issues

📜 Final Outcome
CyberLens is now a secure, production-ready platform with strong authentication, encrypted sessions, and safe file handling.
It meets cybersecurity best practices and is ready for real-world deployment.
