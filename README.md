# 🖥️ Browser History Manager (C++)

A colorful, menu-driven console application in **C++** that simulates browser history management for multiple users.  
Supports both normal users (can only view their own history) and admin users (can view everyone’s history).

---

## ✨ Features
- 🌐 **Visit a webpage** → Adds a new page to your history.
- ⬅️ **Go back** → Moves one step back in the history.
- ➡️ **Go forward** → Moves one step forward if available.
- 📄 **Show current page** → Displays the page you are on.
- 👤 **Multi-user support** → Each user has their own browsing history.
- 🔑 **Admin mode** → View all users and their histories.
- 🎨 **Colorful dashboard** for better console experience.

---

## ⚙️ Implementation Details
- **Data Structures:**
  - `WebPage` → Node in a **doubly linked list** storing a single webpage.
  - `BrowserHistory` → Manages history navigation (`visit`, `back`, `forward`).
  - `map<string, BrowserHistory>` → Stores histories of multiple users (username → history).

- **Core Concepts Covered:**
  - Classes and Objects
  - Pointers and Dynamic Memory (`new`, `delete`)
  - STL `map` for user management
  - Range-based `for` loops with `auto &p`
  - Simple terminal color codes for a better UI

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/browser-history.git
   cd browser-history
