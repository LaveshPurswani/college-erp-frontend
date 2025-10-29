# 🎓 College ERP SaaS – Frontend

This is the **College ERP SaaS Frontend Cobebase** which is a scalable, modular, and responsive web application built using **Next.js (App Router)**.  
It serves as the interface for administrators, faculty, and students to access various ERP modules like authentication, dashboards, course management, and communication systems.

---

## 🚀 Tech Stack

- **Framework:** Next.js (v16)
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **State Management:** React Context API or Redux Toolkit
- **Auth & Data:** JWT + Bycrpt 
- **Linting:** ESLint + Prettier
- **Package Manager:** npm

---

## ⚙️ Getting Started

### 1️⃣ Clone the repository
```bash
git clone git@github.com:LaveshPurswani/college-erp-frontend.git
cd college-erp-frontend
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Run the development server
```bash
npm run dev
```

Your app will be running on  
👉 http://localhost:3000

---

## 🗂️ Project Folder Structure

Below is the proposed **scalable folder structure** for reference and future development.

```
src/
├── app/                     # Next.js App Router pages
│   ├── layout.tsx           # Root layout
│   ├── page.tsx             # Landing page
│   ├── (auth)/              # Auth routes grouping
│   │   ├── login/
│   │   │   └── page.tsx
│   │   └── signup/
│   │       └── page.tsx
│   ├── dashboard/           # Main ERP dashboard
│   │   └── page.tsx
│   └── not-found.tsx
│
├── components/              # Shared React components
│   ├── ui/                  # Reusable UI elements (buttons, modals, etc.)
│   ├── layout/              # Navbars, sidebars, etc.
│   └── forms/               # Auth forms, etc.
│
├── context/                 # React Contexts or Redux (Auth, GlobalProvider)
│   └── AuthContext.tsx
│
├── lib/                     # Utility functions & configs
│   ├── api.ts               # API endpoints, axios setup
│   ├── constants.ts         # Static constants
│   ├── helpers.ts           # Helper functions
│   └── appwrite.ts          # Appwrite SDK config (later)
│
├── hooks/                   # Custom hooks (useAuth, useFetch, etc.)
│
├── styles/                  # Global and component-specific styles
│   └── globals.css
│
└── types/                   # TypeScript types/interfaces
    ├── user.ts
    └── index.ts
```

---

## 🧩 Git & Branching Workflow

This project follows a **clean Git branching model** to ensure stable deployments and organized feature development.

```
main        → Production-ready code
dev         → Active development branch
feature/*   → Individual features (merged into dev)
```

<!-- ### Initial Setup
```bash
git init
git add .
git commit -m "Initial Next.js frontend setup"
git branch -M dev
git remote add origin https://github.com/<your-username>/college-erp-frontend.git
git push -u origin dev
``` -->

<!-- ---

## 🧠 Future Plans

- Integrate Appwrite for Authentication & Database
- Add Super Admin Login and Protected Routes
- Create Global Context Provider for State Management
- Implement Reusable UI Components (Sidebar, Navbar, Modal)
- Add CI/CD pipeline for automated builds & deploys -->

---

<!-- ## 📄 License
This project is licensed under the **MIT License**.  
Feel free to modify and extend for educational or organizational use.

--- -->

## 👨‍💻 Author
**Lavesh Purswani**  
MERN / Full Stack Developer  
<!-- 📧 <your-email> | 🌐 [GitHub](https://github.com/<your-username>) -->
