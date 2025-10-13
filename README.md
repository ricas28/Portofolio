# 👋 Hello, I'm Ricardo Santos!

I'm currently studying **Computer Science** at [Instituto Superior Técnico](https://tecnico.ulisboa.pt/pt/) (Lisbon, Portugal).  
I created this repository to store all of my personal projects during my degree.  
Hope you enjoy exploring them!

---

## 📚 Table of Contents
- [Skills](#skills)
- [Git Submodules Management](#git-submodules-management)
- [Projects](#projects)
- [Contact](#contact)

---

## 🧠 Skills
- **Languages:** Python, Java, C, RISC-V Assembly, Prolog  
- **Tools:** Git, VS Code  

---

## 📦 Git Submodules Management

This portfolio uses **Git submodules** to include individual projects.  
Each submodule is a separate repository, maintained independently, and the portfolio only stores a **reference (commit)** to each of them.

A **submodule** is simply a link to another Git repository inside this one.  
Instead of copying the code, Git tracks **which exact commit** of each project is included.

- ✅ Keeps the original structure and history of each project  
- ✅ Allows projects to be updated independently  
- ⚠️ Changes in submodules are **not automatically reflected** in the portfolio  

---

### ⚙️ Managing Submodules

| Action | Commands |
|--------|-----------|
| ➕ **Add** | `git submodule add <repo-url> <path>`<br>`git commit -m "Added new submodule"` |
| 🔁 **Update** | `cd <path>`<br>`git pull origin main`<br>`cd ../..`<br>`git add <path>`<br>`git commit -m "Updated submodule"` |
| 🧹 **Remove** | `git submodule deinit -f <path>`<br>`rm -rf .git/modules/<path>`<br>`git rm -f <path>`<br>`git commit -m "Removed submodule"` |
| 🔄 **Update All** | `git submodule update --remote --merge`<br>`git add .`<br>`git commit -m "Updated all submodules"` |
| 📥 **Clone with Submodules** | `git clone <portfolio-url>`<br>`cd <portfolio-name>`<br>`git submodule update --init --recursive` |

---

## 💻 Projects

### 🕹️ **Tic-Tac-Toe with MiniMax Algorithm**
**Description:**  
A simple implementation of the classic Tic-Tac-Toe game where the user can play against another player or an AI opponent that uses the **MiniMax algorithm** to make optimal decisions.  
This was my first project exploring **logic and artificial intelligence**.

🔗 [Repository → Tic-Tac-Toe MiniMax](https://github.com/ricas28/Tic-Tac-Toe-MiniMax-)

---

### ✅ **Full-Stack To-Do List App**
**Description:**  
A simple **full-stack to-do list application** built to learn how to integrate a **front-end, back-end, and database**.  
The app allows users to add, edit, and delete tasks, and automatically persists data in the connected database.  
This project helped me understand the fundamentals of **client-server communication**, **REST APIs**, and **database management**.

🔗 [Repository → To-Do List App](https://github.com/ricas28/To-Do-list)

---

## 📬 Contact
- **Email:** rcurveira05@gmail.com  
- **GitHub:** [@ricas28](https://github.com/ricas28)

---
