### 📋 To-Do App with MongoDB

A simple and efficient **To-Do App** built using **MongoDB**, **Node.js**, and a modern frontend framework like **React** or **Vue.js**. This app helps users organize and manage their daily tasks with ease. 🚀

---

### 🌟 Features
- 📝 **Task Management:** Create, update, and delete tasks.
- ✅ **Mark as Complete:** Easily mark tasks as completed or pending.
- 🔍 **Search & Filter:** Search tasks by keywords and filter by status.
- 📆 **Due Dates:** Set deadlines to stay on track.
- 🔒 **User Authentication:** Secure login and registration for personalized task management.

---

### 🛠️ Tech Stack
- **Frontend:** React / Vue.js
- **Backend:** Node.js with Express.js
- **Database:** MongoDB (NoSQL)

---

### 📂 Database Schema
#### Users Collection:
```json
{
  "_id": "ObjectId",
  "name": "string",
  "email": "string",
  "password": "string"
}
```

#### Tasks Collection:
```json
{
  "_id": "ObjectId",
  "userId": "ObjectId",
  "title": "string",
  "description": "string",
  "dueDate": "Date",
  "status": "boolean",
  "createdAt": "Date"
}
```

---

### 🚀 How to Run the Project
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/todo-app.git
   ```
2. **Navigate to the project folder:**
   ```bash
   cd todo-app
   ```
3. **Install dependencies:**
   ```bash
   npm install
   ```
4. **Start the development server:**
   ```bash
   npm run dev
   ```
5. **Set up MongoDB:**  
   Ensure MongoDB is running locally or use a MongoDB Atlas connection string in the `.env` file.

---

### 🎯 APIs Overview
1. **User APIs:**
   - POST `/register` ➡️ Register a new user.
   - POST `/login` ➡️ Log in a user.

2. **Task APIs:**
   - GET `/tasks` ➡️ Fetch all tasks for a user.
   - POST `/tasks` ➡️ Add a new task.
   - PUT `/tasks/:id` ➡️ Update a task.
   - DELETE `/tasks/:id` ➡️ Delete a task.

---

### 📸 Screenshots
1. **Home Page**: View and manage tasks.
2. **Task Form**: Add or edit tasks.
3. **Login/Register**: Secure authentication flow.

---

### 🌐 Live Demo
Check out the live demo here: [**To-Do App Live**](https://your-app-demo-link.com) 🌟

---

### 💡 Future Enhancements
- 📱 Mobile app support.
- 🎨 Custom themes for better UI.
- 📊 Task completion analytics.

---

### 🤝 Contribution
Feel free to fork the repo, open issues, or submit pull requests. Contributions are welcome! 🙌

---

### 📧 Contact
For any questions, reach out at **[subhankhatri922@gmail.com](mailto:subhankhatri922@gmail.com)**.

Happy Coding! 😄
