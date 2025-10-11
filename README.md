# 💊 MedLog: A Full-Stack Learning Journey

![Repo Size](https://img.shields.io/github/repo-size/alamin72b/MegLog-A-Full-Stack-Learning-Journey?style=flat-square&color=4CAF50)
![Last Commit](https://img.shields.io/github/last-commit/alamin72b/MegLog-A-Full-Stack-Learning-Journey?style=flat-square&color=2196F3)
![Open Issues](https://img.shields.io/github/issues/alamin72b/MegLog-A-Full-Stack-Learning-Journey?style=flat-square&color=FF9800)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)

Welcome to **MedLog**, a web app I’m building to track monthly medicine purchases while learning the **full software development process** from scratch!  

This project is my hands-on dive into creating a real-world full-stack application using **React (frontend)**, **Express/Node.js (backend)**, and **MongoDB (database)**.  
I’m documenting every step to make it easy for beginners to follow along and learn how to build a complete app from start to finish.

---

## 🧭 Table of Contents

- [What is MedLog?](#-what-is-medlog)
- [Why This Project?](#-why-this-project)
- [Project Structure](#-project-structure)
- [Features](#-features)
- [How to Follow Along](#-how-to-follow-along)
- [Tech Stack](#️-tech-stack)
- [Getting Started](#-getting-started)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🧾 What is MedLog?

**MedLog** lets users:

- Sign up and log in  
- Track medicines they buy each month (name, price, quantity, and date)  
- Calculate monthly totals  
- Set reminders for next month’s purchases  
- View statistics and charts  
- Compare medicines or monthly expenses  
- Export data (CSV, PDF, etc.)

It’s a **simple but complete** full-stack learning app that helps users manage purchases while serving as a hands-on development project.

---

## 🎯 Why This Project?

I’m using MedLog to learn and apply the **Software Development Lifecycle (SDLC)** — from planning to deployment.  

This project helps me (and others) understand how to:

1. 📝 Plan features and requirements  
2. 🎨 Design the app (UI, APIs, and database)  
3. 💻 Build the frontend and backend  
4. 🧪 Test and debug  
5. ☁️ Deploy to the cloud  
6. 🔄 Maintain and improve over time  

Every commit, diagram, and doc in this repo serves as a **learning resource** for anyone following along.

---

## 🗂 Project Structure

```

MedLog/
├── .gitignore
├── README.md                   # Main intro (includes walkthrough references)
├── docs/
│   ├── planning/
│   │   └── requirements.md     # Requirements and feature plan
│   ├── design/                 # For later phases
│   │   ├── wireframes/
│   │   ├── api-design.md
│   │   └── database-schema.md
│   └── walkthrough/            # Step-by-step documentation
│       └── planning.md         # Walkthrough for Step 1
├── frontend/                   # React frontend code
│   ├── ...
├── backend/                    # Express/Node backend code
│   ├── ...
├── scripts/                    # Optional helper scripts
│   └── ...
├── tests/                      # Testing folder
└── config/                     # Environment/config files
└── ...

````

📘 **Walkthrough:** [docs/walkthrough/planning.md](https://github.com/alamin72b/MegLog-A-Full-Stack-Learning-Journey/blob/main/docs/walkthrough/planning.md)

> Each walkthrough file explains what I did in that phase, the thought process, and how to replicate it — making this repo a complete learning guide.

---

## 🛠 Features

| Feature | Description |
|----------|-------------|
| **User Authentication** | Secure sign up, log in, and logout using JWT |
| **Medicine Management** | Add, edit, and delete records |
| **Monthly Summary** | Automatically calculate total spending |
| **Charts & Analytics** | Visualize trends using Chart.js |
| **Reminders** | Get email notifications for next month’s purchases |
| **Export Data** | Save records as CSV or PDF |
| **Responsive Design** | Works smoothly on all devices |

---

## 📚 How to Follow Along

### 🧩 1. Check the Commits
Each commit represents a milestone, e.g.,  
> “Add requirements document” or “Implement login API.”

### 📄 2. Read Documentation
You can explore detailed documentation and phase-based walkthroughs:
- 📘 [Planning Walkthrough](https://github.com/alamin72b/MegLog-A-Full-Stack-Learning-Journey/blob/main/docs/walkthrough/planning.md)
- 📗 [Requirements Document](https://github.com/alamin72b/MegLog-A-Full-Stack-Learning-Journey/blob/main/docs/planning/requirements.md)

### 💬 3. Ask Questions
Open an **Issue** on this repo if you’re curious about the code, process, or tools — I’ll answer as I learn.

### 🤝 4. Contribute
If you’re a beginner, clone the repo, explore the code, and share suggestions through Issues or Pull Requests!

---

## ⚙️ Tech Stack

| Layer | Technologies |
|-------|---------------|
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![Material-UI](https://img.shields.io/badge/Material--UI-0081CB?style=flat&logo=mui&logoColor=white) ![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat&logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/Express.js-404D59?style=flat) |
| **Database** | ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat&logo=mongodb&logoColor=white) |
| **Other Tools** | ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white) ![Nodemailer](https://img.shields.io/badge/Nodemailer-3C873A?style=flat) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) |

---

## 🚀 Getting Started

### 🧰 Clone the Repository
```bash
git clone https://github.com/alamin72b/MegLog-A-Full-Stack-Learning-Journey.git
cd MegLog-A-Full-Stack-Learning-Journey
````

### ⚡ Setup Instructions

1. Navigate into the `backend` and `frontend` folders to install dependencies:

   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```
2. Configure your **.env** file:

   ```
   MONGO_URI=<your_mongodb_connection_string>
   JWT_SECRET=<your_secret_key>
   EMAIL_USER=<your_email>
   EMAIL_PASS=<your_password>
   ```
3. Start both servers:

   ```bash
   # backend
   cd backend
   npm start

   # frontend
   cd ../frontend
   npm start
   ```

Your app should now be running locally 🎉

---

## 🤝 Contributing

Contributions are welcome!

To contribute:

1. **Fork** the repository
2. **Create** your feature branch

   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Commit** your changes

   ```bash
   git commit -m "Add new feature"
   ```
4. **Push** to your branch and open a **Pull Request**

---

## 🪪 License

This project is open source under the **MIT License**.
See the [LICENSE](https://github.com/alamin72b/MegLog-A-Full-Stack-Learning-Journey/blob/main/LICENSE) file for details.

---


Made with ❤️ by **[alamin72b](https://github.com/alamin72b)**
