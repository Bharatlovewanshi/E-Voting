# 🗳️ E-Voting Management System

A secure and easy-to-use online voting platform built using **Node.js**, **Express.js**, **MySQL**, and **EJS**. This system allows users to register, log in, view candidate groups, and vote. Admins can manage parties and view voting results.

---

## 🚀 Features

- ✅ Voter Registration & Login
- ✅ Session-based Authentication
- ✅ One-time Voting Per User
- ✅ Party/Candidate Registration with Image Upload (Symbol)
- ✅ Display of Candidate Vote Count
- ✅ Clean and Responsive UI

---

## 🛠️ Tech Stack

| Category       | Technology                         |
|----------------|------------------------------------|
| Frontend       | HTML, CSS, JavaScript, EJS         |
| Backend        | Node.js, Express.js                |
| Database       | MySQL                              |
| File Upload    | Multer                             |
| Authentication | Express Session                    |

---

## 📁 Project Structure

E-voting/
│
├── public/ # Static assets (CSS, JS, Images)
├── views/ # EJS templates
├── routes/ # Express routes
├── uploads/ # Uploaded party symbols
├── sql_login.sql # SQL file for database setup
├── app.js or index.js # Entry point for server
├── package.json # NPM configuration
└── README.md # Project documentation

---

## 🧑‍💻 Getting Started

### 1. Clone the Repository

git clone https://github.com/Bharatlovewanshi/E-Voting.git
cd E-Voting
2. Install Dependencies

npm install
3. Set Up MySQL Database
Import the sql_login.sql file into your MySQL server.

Update DB credentials in your main server file:

const db = mysql.createConnection({
  host: "localhost",
  user: "your_mysql_user",
  password: "your_mysql_password",
  database: "e_voting"
});

4. Run the Server

node app.js
Visit http://localhost:8000 in your browser.
