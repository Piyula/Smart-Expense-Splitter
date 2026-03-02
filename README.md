📝 Project Description (Simple + Strong for GitHub)

Smart Expense Splitter is a lightweight web application designed to simplify shared expenses among groups such as friends, roommates, or travel partners.
Users can add expenses, assign who paid, and select members involved in the split.
The app automatically calculates who owes whom and generates a clean settlement summary.

This project is ideal for students and beginners learning Node.js, Express, and MongoDB, while also practicing real-world applications like data validation, modular API design, and simple frontend development.

📄 Full README.md (Ready to Upload to GitHub)

(Professional + Attractive + Simple)

📌 Smart Expense Splitter

A simple and efficient web app to calculate shared expenses among a group. Inspired by Splitwise but built with a minimal and beginner-friendly stack.

🚀 Features

➕ Add shared expenses

👥 Manage group members

🔄 Automatically split expenses equally

📊 Generate “Who owes whom” settlement

🗂 Expense categories (Food, Travel, Bills, Shopping…)

📁 Download final report as PDF

🔐 (Optional) User authentication using JWT

🌐 (Optional) Real-time updates with Socket.IO

🧰 Tech Stack
Frontend

HTML

CSS

JavaScript

(Optional) React

Backend

Node.js

Express.js

MongoDB (Mongoose)

Tools

Postman

Git & GitHub

VS Code

📁 Folder Structure

smart-expense-splitter/
│
├── backend/
│   ├── app.js
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── utils/splitLogic.js
│   └── config/db.js
│
├── frontend/
│   ├── index.html
│   ├── app.js
│   └── style.css
│
├── .gitignore
├── README.md
└── package.json


⚙️ Installation & Setup
1. Clone the Repository
git clone https://github.com/your-username/smart-expense-splitter.git
cd smart-expense-splitter
2. Install Dependencies
npm install
3. Setup Environment Variables

Create .env file

MONGO_URI = your_mongodb_connection_url
PORT = 5000
JWT_SECRET = your_secret_key   # optional
4. Start Server
npm start
📌 API Endpoints
Add Expense

POST /api/expenses/add

Get All Expenses

GET /api/expenses

Calculate Settlement

GET /api/expenses/settlement

Add Member

POST /api/members/add

🧮 Example Settlement Output
John owes Mary: $12
Alex owes John: $5
Total outstanding: $17
📸 Screenshots (You can add later)

Add expense screen

Settlement summary

Group management page

🏗 Future Improvements

✔ Add PDF export

✔ Add authentication

✔ Real-time updates

✔ Monthly expense graph

✔ Voice input for expense

🙌 Contributing

Pull requests are welcome.
For major changes, please open an issue first.

📜 License

MIT License
