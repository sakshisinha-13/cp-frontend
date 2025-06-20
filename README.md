# CodePlayground – Frontend

CodePlayground is a React-based frontend application for exploring coding interview problems. It supports filtering by topic, company, difficulty, and allows exporting questions in CSV, Markdown, or PDF formats.

Live App: [https://cp-frontend-six.vercel.app](https://cp-frontend-six.vercel.app)

---

## Features

- Filter questions by company, topic, difficulty, and more
- Export questions as CSV, PDF, or Markdown
- Clean and responsive UI
- Data visualization with pie charts and insights

---

## Folder Structure

client/
├── public/ # Static files like index.html
├── src/
│ ├── assets/ # Logos, images, and static resources
│ ├── components/ # Reusable components (Navbar, Filters, etc.)
│ ├── exports/ # Export logic for CSV, Markdown, PDF
│ ├── pages/ # Page-level components (Dashboard, Playground)
│ ├── App.js # Root component with route definitions
│ └── index.js # Entry point that renders the App
├── .gitignore
├── package.json
└── README.md

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/sakshisinha-13/cp-frontend.git
   cd cp-frontend/client
Install dependencies:
npm install
Run the app locally:
npm start

Tech Stack
React.js
Tailwind CSS
React Router DOM
Axios / Fetch API
jsPDF, html2canvas
Chart.js

