# CampusHire — React Job & Internship Portal

A responsive frontend portfolio project built with React + Vite. It helps students and fresh graduates discover jobs and internships, filter opportunities, save roles, and track application status.

## Features
- Responsive dashboard layout
- Search by role, company, or skill
- Filter by work type and experience level
- Save/unsave opportunities (persisted with localStorage)
- Apply interaction and application tracking
- Job detail modal
- Toast feedback and empty states
- Sample data included; no backend/API key required

## Tech stack
React, Vite, JavaScript, CSS, Lucide React, localStorage.

## Run locally
1. Install Node.js (LTS).
2. Extract this project and open the folder in VS Code.
3. Open a terminal in the project folder.
4. Run:

   ```bash
   npm install
   npm run dev
   ```

5. Open the local URL printed by Vite (usually http://localhost:5173).

## Build for production
```bash
npm run build
npm run preview
```

## GitHub upload
Create a new empty GitHub repository named `campushire-react`, then run:

```bash
git init
git add .
git commit -m "Build CampusHire React job portal"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/campushire-react.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username.

## Important
This is a frontend demo. Job listings and companies are sample data, and the Apply action is simulated in the browser. Connect a backend (for example, Java Spring Boot + MySQL) to support real accounts and applications.

## Suggested resume description
Built a responsive job and internship portal using React, featuring job search, filters, saved opportunities, application tracking, reusable components, and localStorage persistence.
