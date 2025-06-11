# 🗂️ Kanban Task Management

## 🚀 Project Overview

**Kanban Task Management** is a responsive web-based application that allows users to organize and visualize their tasks across three workflow stages: `TODO`, `DOING`, and `DONE`. The project combines clean UI with interactive prompts to guide users through task creation and progress tracking.

## 🛠️ Technologies Used

- **HTML5** – Structure and semantic layout
- **CSS3** – Responsive design with custom properties
- **JavaScript (ES6)** – Dynamic interaction, logic, and validation
- **Google Fonts** – Plus Jakarta Sans for modern typography
- **Favicon Assets** – SVG-based icons for branding

## ✨ Features

- ✅ Responsive Kanban board with three workflow columns
- ✅ Sidebar with styled navigation and branding
- ✅ Prompt-based entry of two tasks: title, description, and status
- ✅ Accepts status input in any case (`TODO`, `Doing`, `DONE`, etc.)
- ✅ Alerts and re-prompts for invalid statuses until corrected
- ✅ Separate variable storage for both tasks
- ✅ Displays only tasks with status `"done"` in the console
- ✅ Encouraging message when no tasks are marked as `"done"`
- ✅ Clean, accessible, and maintainable code with comments

## 📁 File Structure

kanban-task-app/
├── index.html # Main HTML file
├── styles.css # CSS for layout and design
├── scripts.js # JavaScript task logic
├── assets/ # Logos and icons
└── README.md # Project documentation

## 📸 Screenshots

### 💻 Desktop View

![Desktop Screenshot](assets/screenshots/kanban-desktop.png)

### 📱 Mobile View

![Mobile Screenshot](assets/screenshots/kanban-mobile.png)



---

## ⚙️ Setup Instructions

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/VanessaDa/VANBAA25089_PTO2502_GroupA_VanessaBaart_JSL02-2025.git
   ```

2. **Navigate into the Project:**

   ```bash
   cd VANBAA25089_PTO2502_GroupA_VanessaBaart_JSL02-2025
   ```

3. **Open the Application:**
   Open `index.html` in your web browser, or use a Live Server extension for auto-refresh.

💡 No installations or dependencies required – everything runs in the browser.

## 🧑‍💻 Usage Instructions

### 🟢 Initial Launch

1. Load the site in your browser.
2. The Kanban layout appears after entering the task prompts.

### 📝 Task Entry

You will be prompted twice (for two tasks). For each task:

- Enter the title (e.g., "Fix login issue")
- Enter the description (e.g., "Bug in production login flow")
- Enter the status:
  - Valid options: todo, doing, or done (case-insensitive)
  - If input is invalid, you'll be alerted and asked again

### 🖥️ Console Output

- If any task is marked as "done", its title and status will appear in the console.
- If no task is marked "done", you'll see:
  ```
  No tasks completed, let's get to work!
  ```

## 📌 Usage Examples

### ✅ Example: One Task Done

Input via Prompt:

- Task 1:
  - Title: Write report
  - Description: Quarterly summary
  - Status: DONE
- Task 2:
  - Title: Fix navbar
  - Description: Issue in mobile view
  - Status: todo

Console Output:

```
Title: "Write report", Status: "done"
```

### ❌ Example: No Tasks Done

Input via Prompt:

- Task 1:
  - Title: Update fonts
  - Status: TODO
- Task 2:
  - Title: Test animation
  - Status: DOING

Console Output:

```
No tasks completed, let's get to work!
```

## 🧾 Future Improvements

- UI-based task creation instead of prompts
- LocalStorage or database persistence
- Drag-and-drop task movement
- Edit/delete task functionality
- Dark mode toggle

## ✍️ Author

Vanessa Baart

GitHub Repository

## 📄 License

This solution code is provided for **educational use only**.
