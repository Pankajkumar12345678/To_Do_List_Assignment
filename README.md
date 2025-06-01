# ✅ ToDo List App With React

A simple and efficient **To-Do List** application built with **React**, using **Context API** and **Hooks**. Tasks are stored in `localStorage`, so your list persists even after refreshing or closing the browser.

---

## 🚀 Features

- ✅ Add new tasks (with input validation)
- 🗑️ Remove existing tasks
- ✔️ Mark tasks as completed or pending
- 🔄 Edit tasks inline
- 🔍 Filter tasks by status: All / Completed / Pending
- ↕️ Sort tasks by ID (ascending/descending)
- 💾 Persistent storage using `localStorage`
- 🔄 Fully dynamic rendering

---

## 🧠 Technologies Used

- React
- React Context API
- React Hooks (`useState`, `useEffect`, `useContext`)
- LocalStorage

---


---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Pankajkumar12345678/To_Do_List_Assignment.git
   cd To_Do_List_Assignment


Install dependencies

```bash
npm install
```

Start the app

```bash
npm start
```

The app will run at http://localhost:3000/.

🧪 Testing Guide
Follow these steps to test the functionality:

Add Tasks

Enter a task name in the input field.

Click the "Add" button.

Task should appear in the list below.

Validate Input

Try submitting empty input — an alert or validation message should appear.

Mark Tasks as Complete/Pending

Use the checkbox next to the task.

Completed tasks should show visual styling (e.g., strikethrough).

Edit Tasks

Click the "Edit" icon.

Update the text and save changes.

Delete Tasks

Click the "Delete" icon to remove a task.

Filter Tasks

Use filter options to view: All, Completed, or Pending.

Sort Tasks

Use sorting controls (by ID or order of creation).

LocalStorage Persistence

Refresh the page — tasks should persist.

📁 Folder Structure

src/

├── components/

│   └── TodoList.jsx

│   └── TaskItem.jsx

├── context/

│   └── TaskContext.jsx

├── App.jsx

├── index.js

└── styles/

    └── App.css
    
    
✍️ Author
Your Name
GitHub: Pankajkumar12345678

