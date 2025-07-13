# 📝 To-do List CLI App

A simple and interactive **command-line To-do List app** built with **Node.js**. Manage your tasks directly from the terminal with local JSON-based persistence and a user-friendly experience enhanced with emojis.

---

## 🚀 Features

-   📋 View all tasks
-   ✅ Add new tasks
-   ✏️ Update task descriptions
-   🗑️ Delete tasks
-   🔁 Mark tasks as completed or incomplete
-   💾 Data persistence using a local JSON file (`tasksData.json`)
-   😎 Clean console interface with menu options and emojis

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/blazo-dev/todo-list-node-cli.git
cd todo-list-node-cli
```

2. Install dependencies:

```bash
npm install
```

3. Run the app:

```bash
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

1. When you run the app, a menu is displayed with options.
2. Choose an action (e.g. add a task, view tasks).
3. The task list is saved in a local JSON file so your data persists across sessions.
4. After each operation, the menu is shown again unless you choose to exit.

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

### Task display example:

```
[1]: [X] Learn Node.js
[2]: [ ] Finish homework
```

---

## ✅ Requirements

-   Node.js v18 or higher

---

## 🛠 Technologies Used

-   Node.js with ES Modules
-   `readline/promises` for input
-   `fs/promises` for file handling

---

## 📄 License

This project is licensed under the [ISC License](https://opensource.org/licenses/ISC). Feel free to use, modify, and distribute it.
