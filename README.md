# CodePlayground – Practice Coding with Real Interview Questions

[Live Site 🔗](https://cp-frontend-six.vercel.app/login)

CodePlayground is a full-stack coding platform designed for students and job-seekers to practice real online assessment (OA) and interview questions asked by top tech companies like Microsoft, ServiceNow, and Amazon.

It features a LeetCode-style UI, dynamic code execution for C++, real-time test case validation, and structured problem descriptions.

---

##  Features

-  **Authentication** – Login and signup functionality
-  **Problem Dashboard** – Browse real OA and interview questions (filtered by company, topic, difficulty, etc.)
-  **Detailed Problem View** – Description, input/output format, constraints, and examples
-  **Code Editor** – Write and run C++ code with AceEditor
-  **Test Case Evaluation** – Input/output checked against real test cases
-  **Dark Mode UI** – LeetCode-style layout with tabs and themes

---

## Tech Stack

### Frontend
- [React.js](https://reactjs.org/)
- [AceEditor](https://ace.c9.io/) for coding interface
- [Axios](https://axios-http.com/) for API calls
- [React Router](https://reactrouter.com/) for navigation
- [Tailwind CSS or custom CSS] for styling (optional)

### Backend (linked repo)
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for problem data
- [C++ Code Executor] using `child_process` and `g++`

---

## 📸 Screenshots

| Description View | Code Editor View |
|------------------|------------------|
| ![Description View](https://i.imgur.com/YOUR_DESC_IMG.png) | ![Editor View](https://i.imgur.com/YOUR_EDITOR_IMG.png) |

---

##  Local Setup Instructions

```bash
# Clone the repo
git clone https://github.com/sakshisinha-13/cp-frontend.git
cd cp-frontend

# Install dependencies
npm install

# Start the development server
npm start
