````md id="mczv6d"
# ⚡ Smart Daily Planner App

A modern and interactive React.js productivity application designed to manage daily activities such as Gym, Work, Study, Sports, and Personal Routine tasks.

This project was developed as part of a React Internship Task to practice:

- React Components
- Props Passing
- State Management
- Hooks
- Dynamic UI Rendering
- Component Reusability
- Modern CSS Styling

---

# 🚀 Live Demo

### 🌍 Deployed Application
https://react-todo-list-app-taupe.vercel.app/

### 💻 GitHub Repository
https://github.com/captainawais/react-todo-list-app

---

# 📌 Project Description

Smart Daily Planner helps users organize their daily activities in a clean and professional interface.

Users can:

- Add daily tasks
- Select activity category
- Set task time
- Delete completed tasks
- Store tasks permanently using Local Storage
- Manage productivity activities easily

The application focuses on improving React fundamentals and building reusable components with a responsive modern UI.

---

# 🎯 Project Features

✅ Add Daily Tasks  
✅ Time Scheduling  
✅ Dynamic Task Rendering  
✅ Reusable Components  
✅ Responsive UI Design  
✅ Local Storage Support  
✅ React Hooks Implementation  
✅ Component Architecture  
✅ CSS Styling  
✅ Real-time Updates  

---

# 🧠 React Concepts Used

- Functional Components
- Props Passing
- useState Hook
- useEffect Hook
- Component Reusability
- Event Handling
- Dynamic Rendering
- Conditional Rendering
- CSS Component Styling

---

# 🛠️ Technologies Used

- React.js
- JavaScript (ES6)
- HTML5
- CSS3
- React Hooks
- Local Storage API

---

# 📂 Project Structure

```bash
src/
│
├── components/
│   ├── TodoList.js
│   ├── TodoItem.js
│   └── Todo.css
│
├── App.js
├── App.css
├── index.js
└── index.css
```

---

# ⚙️ Installation Instructions

## Step 1 — Clone Repository

```bash
git clone https://github.com/captainawais/react-todo-list-app.git
```

---

## Step 2 — Open Project Folder

```bash
cd react-todo-list-app
```

---

## Step 3 — Install Dependencies

```bash
npm install
```

---

## Step 4 — Run Project

```bash
npm start
```

The application will open at:

```bash
http://localhost:3000
```

---

# 📖 Usage Guidelines

1. Enter your activity name
2. Select task time
3. Choose activity category
4. Click "Add Task"
5. Tasks will appear in separate cards
6. Delete tasks after completion
7. Tasks remain saved after page refresh

---

# 🏗️ Component Architecture

## 🔹 TodoList Component

Responsible for:

- Managing application state
- Adding tasks
- Saving tasks in Local Storage
- Rendering TodoItem components

---

## 🔹 TodoItem Component

Responsible for:

- Displaying individual task details
- Showing task category and time
- Handling delete functionality

---

# 🎨 UI Design Goals

The application UI was designed to look:

- Clean
- Professional
- Modern
- Responsive
- Productivity-focused

The dark gradient background and card-based layout improve user experience and visual hierarchy.

---

# 🧩 Challenges Faced

## Challenge 1 — Tasks Removed After Refresh

### Solution:
Implemented Local Storage using:

```javascript
localStorage.setItem()
localStorage.getItem()
```

---

## Challenge 2 — Dynamic Rendering

### Solution:
Used React state and `.map()` method to dynamically render task cards.

---

## Challenge 3 — Component Reusability

### Solution:
Separated logic into reusable components like:

- TodoList
- TodoItem

---

# 📚 Learning Outcomes

Through this project, I learned:

- React component architecture
- State management using Hooks
- Props communication
- Dynamic UI rendering
- Event handling
- Reusable component design
- Local Storage integration
- Modern CSS styling

---

# 🧑‍💻 Developed By

### EngrAwais Farooq

Frontend Developer | React Learner | Software Engineering Enthusiast

Powered by TechFactOfficial

---

# 🙌 Internship Learning

This project was developed during my Frontend React Internship practice tasks to strengthen practical React.js skills and understand real-world component-based application development.

---

# ⭐ Future Improvements

- Dark Mode
- Task Completion Status
- Task Editing
- Authentication System
- Backend Database Integration
- Mobile Responsive Enhancements

---

# 📜 License

This project is developed for educational and internship learning purposes.
````
