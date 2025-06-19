# CodePlayground Frontend

Live Site: [https://cp-frontend-six.vercel.app/login](https://cp-frontend-six.vercel.app/login)

This is the frontend of CodePlayground, a LeetCode-style web application built to help students and professionals practice real online assessment (OA) and interview questions from top tech companies like Microsoft, ServiceNow, Amazon, and more.

It provides a clean UI with a code editor, test case evaluation, and detailed problem views.

---

## Features

- User authentication (Login / Signup)
- Problem dashboard with filters (company, topic, year, difficulty)
- Problem view page with:
  - Description
  - Input/Output format
  - Constraints
  - Examples
- Code editor with AceEditor (C++ support)
- Submit code and evaluate against real test cases
- Modern dark UI inspired by LeetCode

---

## Tech Stack

### Frontend

- React.js
- React Router DOM
- Axios
- Ace Editor (C++ mode)
- Custom CSS and inline styles

---

## Getting Started Locally

```bash
# Clone the repository
git clone https://github.com/sakshisinha-13/cp-frontend.git
cd cp-frontend

# Install dependencies
npm install

# Start development server
npm start

Folder Structure
csharp
Copy
Edit
cp-frontend/
├── public/
├── src/
│   ├── components/         # UI components like ProblemCard, Header, Filters
│   ├── pages/              # Route pages (Login, Signup, Dashboard, ProblemView)
│   ├── utils/              # Helper functions (recommendation logic, filters, etc.)
│   └── App.js              # Routing and layout
Author
Sakshi Sinha
B.Tech, IIT Patna
GitHub: @sakshisinha-13

