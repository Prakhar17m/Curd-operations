
# MERN Stack CRUD Application – User Registration & Management

This is a full-stack CRUD (Create, Read, Update, Delete) application built using the **MERN stack**: **MongoDB**, **Express.js**, **React.js**, and **Node.js**. The application provides a user-friendly interface to **register users**, **update existing entries**, **store data**, and **display it** in a clean and responsive UI.

---

## 🔗 Live Demo

👉 [Live App Link](https://curd-frontend-ovbl.onrender.com/)  
*(Replace this link with your deployed app's actual URL)*

---

## 📌 Features

- 🧾 User Registration Form
- ✏️ Edit/Update Existing Users
- 📄 View All Registered Users
- ❌ Delete Users
- 📦 MongoDB for Persistent Storage
- 💻 Responsive UI built with React
- 🚀 RESTful APIs with Express and Node.js

---

## 🧑‍💻 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/mern-crud-form.git
cd mern-crud-form
```

### 2. Install Backend Dependencies

```bash
cd backend
npm install
```

### 3. Create Environment File

Inside the `backend` directory, create a file named `.env` and add the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

> Replace `your_mongodb_connection_string` with your actual MongoDB URI.

### 4. Start the Backend Server

```bash
npm start
```

### 5. Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

### 6. Start the React App

```bash
npm start
```

> ✅ The frontend will run on **http://localhost:3000**  
> ✅ The backend will run on **http://localhost:5000**

---

## 📦 API Endpoints

| Method | Endpoint           | Description              |
|--------|--------------------|--------------------------|
| GET    | `/api/users`       | Get all users            |
| POST   | `/api/users`       | Create a new user        |
| PUT    | `/api/users/:id`   | Update user by ID        |
| DELETE | `/api/users/:id`   | Delete user by ID        |

---

## 📁 Folder Structure

```
mern-crud-form/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── .env
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   └── index.js
├── package.json
└── README.md
```

---

## 🖼️ Screenshots

> *(Add screenshots of your UI here)*

- 📋 User Registration Form  
- 🧾 User List Table  
- 🔄 Update User Modal  

---

## ⚙️ Tech Stack

- **Frontend**: React.js, HTML5, CSS3, Bootstrap  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB (with Mongoose)  
- **Dev Tools**: VS Code, Postman, Git  

---

## 🚀 Deployment

> You can deploy the frontend on **Vercel** or **Netlify** and the backend on **Render** or **Railway**.

### Deploy Backend on Render:

- Push your backend to GitHub  
- Go to [Render](https://render.com/)  
- Create a new web service  
- Add your environment variables (`MONGO_URI`)  
- Set build command: `npm install`  
- Set start command: `npm start`  

### Deploy Frontend on Vercel:

- Push your frontend to GitHub  
- Go to [Vercel](https://vercel.com/)  
- Import the GitHub repository  
- Deploy using default settings  

---

## 🙋‍♂️ Author

**Prakhar Mehrotra**  
📧 prakhar.your@email.com  
🔗 [GitHub](https://github.com/prakharm404) • [LinkedIn](https://linkedin.com/in/yourprofile) • [Portfolio](https://your-portfolio-link.com)

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ *If you found this project helpful or interesting, feel free to leave a star!*
