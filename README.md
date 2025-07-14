# 📝 To-do List CLI App

A simple and interactive **command-line To-do List app** built with **Node.js**. Manage your tasks directly from the terminal with local JSON-based persistence and a user-friendly experience enhanced with emojis.

> 🧩 **This project was developed as part of the** > **Workforce Opportunity Services (WOS) – Technology Talent Development Program in partnership with Auto Club Enterprises (ACE)**
> A 14-week intensive initiative that combines enterprise-level technical training, hands-on project work, and agile team simulations.

---

## 🚀 Features

-   📋 View all tasks
-   ✅ Add new tasks
-   ✏️ Update task descriptions
-   🗑️ Delete tasks
-   🔁 Mark tasks as completed or incomplete
-   💾 Local data persistence using `tasksData.json`
-   😎 Console-based user experience with emoji-enhanced prompts

---

## 📦 Installation

```bash
git clone https://github.com/blazo-dev/todo-list-node-cli.git
cd todo-list-node-cli
npm install
npm start
```

---

## 📂 Project Structure

```
.
├── app.js             # Entry point – main program flow and user interaction
├── store.js           # Task state logic (add, update, delete, complete)
├── persistence.js     # File I/O for saving and loading tasks
├── utils.js           # Utility functions (menus, input, validation)
├── tasksData.json     # Local file storing tasks
├── package.json       # Project metadata and scripts
└── .gitignore
```

---

## 💻 How It Works

1. Launch the app from the terminal.
2. A menu of actions is displayed.
3. Choose an action: view, add, update, complete, or delete tasks.
4. All changes are saved locally and persist between sessions.

---

## 🧪 Sample Output

```bash
📝 Welcome to the To-do List!

📋 Menu

1️⃣: View tasks
2️⃣: Add task
3️⃣: Complete task
4️⃣: Delete task
5️⃣: Update task
6️⃣: Exit

👉 Choose an option (1-6):
```

Task list example:

```
[1]: [X] Learn Node.js
[2]: [ ] Build CLI app
```

---

## ✅ Requirements

-   Node.js v18 or higher

---

## 📄 License

This project is licensed under the [ISC License](https://opensource.org/licenses/ISC). You are free to use and modify it.

---

## 🙌 Acknowledgements

[**Workforce Opportunity Services (WOS)**](https://www.linkedin.com/company/workforce-opportunity-services)
[**Auto Club Enterprises (ACE)**](https://www.linkedin.com/company/aaa-auto-club-enterprises/).

Created with 💻 and ☕ by [Bryan Lazo](https://github.com/blazo-dev).
