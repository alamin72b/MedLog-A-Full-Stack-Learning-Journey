# 🧩 Step 1: Planning and Requirement Analysis — Walkthrough

Welcome to **Step 1 of the MedLog journey** — **Planning and Requirement Analysis**.  
Before coding, we need to define *what the app will do*, *who it’s for*, and *why it matters*.  
This walkthrough will guide you in creating your `requirements.md` file step by step, explaining what to include in each section and why it’s important.

---

## 🎯 Purpose of This Step

Planning is the **foundation** of any software project.  
Here you’ll:
- Translate your idea into a clear, structured plan.  
- Learn how professionals capture requirements before development.  
- Create documentation you’ll refer to throughout the project.

---

## 🗂️ What You’ll Do

You’ll create a file named:

```

docs/planning/requirements.md

````

This file will describe everything your app should do — from user goals to technical needs.  
In this walkthrough, each section below explains **what to write** inside that file.

---

## 🧾 Sections Overview

Your `requirements.md` will have 12 sections.  
Here’s what to include in each and why it matters.

---

### 1. **Project Overview**
**What to Do:**  
Write 2–3 paragraphs summarizing what MedLog is, its purpose, and its core idea.

**Why It Matters:**  
This gives readers (and yourself) a quick understanding of the app’s purpose — like an elevator pitch.  
Think of it as answering:  
> “What problem does MedLog solve, and how does it help users?”

---

### 2. **Problem Statement**
**What to Do:**  
Explain the main pain point that motivated this project. Describe the issue users currently face.

**Why It Matters:**  
A clear problem statement gives direction. It helps make sure every feature you add actually solves that problem.

---

### 3. **Goals and Objectives**
**What to Do:**  
List 3–6 measurable goals for your project.  
Each goal should describe *what success looks like* — not just tasks.

**Why It Matters:**  
You’ll later evaluate your project against these goals to see how well it performs.

---

### 4. **Project Scope**
**What to Do:**  
Separate features into two lists:  
- **In Scope** → What you’ll build in this version.  
- **Out of Scope** → Features to consider for the future.

**Why It Matters:**  
Scope boundaries prevent feature creep and help you stay focused on core deliverables.

---

### 5. **Target Users & Personas**
**What to Do:**  
Describe 2–3 types of users who might use your app (age, role, motivation).  
Optionally, make a small table with their pain points and what they expect from MedLog.

**Why It Matters:**  
This helps you design user-friendly features and keeps development user-focused.

---

### 6. **Functional Requirements**
**What to Do:**  
List specific things the system should do — such as user authentication, data tracking, and exporting reports.  
Each should have an ID like **FR-1**, **FR-2**, etc.

**Why It Matters:**  
These define the **core features** you’ll later implement and test.

---

### 7. **Non-Functional Requirements**
**What to Do:**  
List performance, security, and quality aspects.  
Example categories: speed, reliability, responsiveness, accessibility, scalability.

**Why It Matters:**  
These don’t describe *features* — they describe *how well* your system should perform.

---

### 8. **System Constraints**
**What to Do:**  
Document the limitations of your project — hosting limits, free-tier tools, API usage, etc.

**Why It Matters:**  
Every real-world project has constraints. Listing them helps you design realistic solutions and anticipate issues.

---

### 9. **Tools & Technology**
**What to Do:**  
Create a small table showing which tools and technologies you’ll use for each layer:
- Frontend  
- Backend  
- Database  
- Additional tools (e.g., Git, Nodemailer, Chart.js)

**Why It Matters:**  
Choosing a consistent stack early helps avoid compatibility issues later.

---

### 10. **Risks and Mitigation**
**What to Do:**  
List possible challenges (like database limits, email spam, or unclear goals) and how you plan to reduce their impact.

**Why It Matters:**  
Risk planning prepares you for obstacles before they happen — a key habit in professional development.

---

### 11. **Success Metrics**
**What to Do:**  
Define measurable outcomes to check whether your project meets expectations.  
Example: “Dashboard loads in under 2 seconds” or “Reminder emails sent successfully.”

**Why It Matters:**  
This turns your project into a measurable learning experience — not just a coding exercise.

---

### 12. **Future Roadmap**
**What to Do:**  
Describe upcoming phases (design, development, testing, deployment, maintenance).  
Mention what will happen in each.

**Why It Matters:**  
It shows long-term planning and helps readers follow your journey phase by phase.

---

## 🧩 Validation Checklist

Before finalizing your `requirements.md`, review:
- [ ] Each section clearly describes what to build  
- [ ] Functional & non-functional requirements are realistic  
- [ ] Constraints match your resources  
- [ ] You’ve written from a **user’s perspective**, not just technical terms  
- [ ] The file is well formatted and readable on GitHub  

When ready, commit your file:

```bash
git add docs/planning/requirements.md
git commit -m "docs: add project requirements document for MedLog"
git push
````

---

## 📎 Example Reference

Once complete, link it here:

> 📄 [View Final Requirements Document](../../docs/planning/requirements.md)

---

## ✅ Summary

**Goal:** Learn how to define your app before coding it.
**Outcome:** A detailed `requirements.md` file that captures all functional, non-functional, and contextual requirements.
**Next Step:** Proceed to **Step 2 – Design Phase** (wireframes, API design, and database schema).

---

> *“Clarity before code — great software starts with great understanding.”*

