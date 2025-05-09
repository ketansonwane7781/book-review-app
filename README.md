# 📚 Book Review App

A full-stack web application where users can view, add, and manage reviews for their favorite books. Built using the **MEAN Stack**: MongoDB, Express.js, Angular, and Node.js.

---

## 🚀 Features

- 🔐 User authentication (Login/Register)
- 📖 Browse books and their details
- 📝 Add, edit, and delete reviews
- ⭐ Star rating system
- 🗂️ RESTful API integration
- 📊 Responsive UI with Angular

---

## 🛠️ Tech Stack

| Frontend  | Backend   | Database | Tools        |
|-----------|-----------|----------|--------------|
| Angular   | Node.js   | MongoDB  | Postman      |
| TypeScript| Express.js| Mongoose | Git & GitHub |

---

## 📁 Project Structure

book-review-app/
├── backend/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── config/
│ └── server.js
├── frontend/
│ └── src/
│ ├── app/
│ │ ├── components/
│ │ ├── services/
│ │ └── app.module.ts
│ └── index.html
├── package.json
├── README.md
└── .env

yaml
Copy
Edit

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/ketansonwane7781/book-review-app.git
cd book-review-app
2. Setup Backend
bash
Copy
Edit
cd backend
npm install
Create a .env file in the backend directory:

ini
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Start the backend:

bash
Copy
Edit
node server.js
3. Setup Frontend
bash
Copy
Edit
cd ../frontend
npm install
ng serve
Open http://localhost:4200 in your browser.

🔒 Authentication
New users can register via /register.

Existing users can log in and get a JWT token stored locally.

Token is used for secure API calls (edit, delete).

📷 Screenshots
Add your own screenshots here after deploying the app locally.

📌 Future Improvements
🌐 Pagination and search

💬 Comment section under reviews

📦 Deploy with Docker and CI/CD pipeline

📲 Mobile-friendly UI

📬 Contact
Ketan Sonwane
📧 ketansonwane603@gmail.com
🌐 LinkedIn
