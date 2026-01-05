# 🎓 Mentor-Connect

Mentor-Connect is a modern full-stack mentoring platform that connects students and job-seekers with industry professionals for career guidance, interview preparation, and skill development. It provides a clean, intuitive interface to discover mentors, book sessions, and track learning progress.

---

## 🚀 Features

- 👤 User authentication (Mentors & Mentees)
- 🔍 Search and filter mentors by domain & skills
- 📅 Book mentoring sessions
- 💬 One-to-one mentorship interaction
- 📊 Profile & progress tracking
- 📱 Fully responsive UI
- ⚡ Built using modern Next.js App Router architecture

---

## 🛠 Tech Stack

| Technology | Usage |
|-----------|------|
| Next.js 14 | Frontend & Backend |
| React     | UI Components |
| Tailwind CSS | Styling |
| Prisma    | Database ORM |
| PostgreSQL | Database |
| NextAuth  | Authentication |
| Vercel    | Deployment |

---

## 📁 Project Structure

```
/
├─ app/                # Application routes & layouts
├─ components/         # Reusable UI components
├─ data/               # Static datasets (interview questions, etc.)
├─ hooks/              # Custom React hooks
├─ lib/                # Utility functions
├─ prisma/             # Prisma schema & DB config
├─ public/             # Static assets
├─ tailwind.config.js
├─ package.json
└─ README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
    git clone https://github.com/akshat-2411/Mentor-Connect.git
    cd Mentor-Connect
### 2️⃣ Install Dependencies
    npm install
### 3️⃣ Setup Environment Variables
Create a .env file:
    
    DATABASE_URL=postgresql://username:password@localhost:5432/mentorconnect
    NEXTAUTH_SECRET=your_secret_key
    NEXTAUTH_URL=http://localhost:3000
### 4️⃣ Setup Database
    npx prisma generate
    npx prisma migrate dev
### 5️⃣ Start Development Server
    npm run dev

---

## 📌 Use Cases
- Students seeking career guidance
- Job seekers preparing for interviews
- Professionals offering mentorship
- Skill-based learning & career tracking

---

## 👨‍💻 Author
### Akshat Sharma
🔗 GitHub: https://github.com/akshat-2411
🔗 LinkedIn: https://www.linkedin.com/in/akshat-sharma24

---

## 📜 License
This project is licensed under the MIT License.
