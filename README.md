VPLAssist+ 📝  
A Simple To-Do List Manager (C# | WPF)

VPLAssist+ is a desktop-based task management application developed using **C# and Windows Presentation Foundation (WPF)**.  
The application helps users efficiently **add, view, update, delete, and search tasks** through a clean and user-friendly interface.

This project was developed as part of the **Visual Programming Language (VPL) / CCP** coursework.

---

📌 Project Information

- **Project Name:** VPLAssist+ (To-Do-List Manager)
- **Developer:** Muhammad Zain  
- **Student ID:** 54893  
- **Program:** BS (Artificial Intelligence)  
- **Faculty:** Shehzad Arain  
- **Technology Stack:**  
  - C#  
  - WPF (.NET)  
  - Object-Oriented Programming (OOP)

---

🎯 Problem Statement

Managing daily tasks manually is inefficient and error-prone.  
Users often forget tasks or fail to organize them properly.

VPLAssist+ solves this problem by providing a **simple desktop application** that allows users to manage tasks in a structured and visual way.

---

✅ Features

- ➕ Add new tasks  
- 👁️ View all tasks in a DataGrid  
- ✏️ Update existing tasks  
- ❌ Delete tasks  
- 🔍 Search tasks easily  
- 📊 Display total task count  
- 💾 Local data persistence using a text file  

---

🧠 System Design

🔹 OOP Structure
The application follows Object-Oriented Programming principles:

- `TaskItem` class represents the task data model
- Encapsulation using properties
- Constructors for object initialization
- Separation of UI and business logic

This improves **code readability, scalability, and maintainability**.

---

🧩 WPF Controls Used

| Control     | Purpose |
|------------|--------|
| TextBox    | Task title input & search |
| ComboBox  | Task status selection |
| Button    | CRUD operations |
| DataGrid  | Display task list |
| TextBlock | Show total number of tasks |

---

💾 Data Storage

- Data is stored locally in a text file: `tasks.txt`
- Task format:
