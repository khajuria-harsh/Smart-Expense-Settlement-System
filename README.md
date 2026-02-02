# Smart-Expense-Settlement-System

A scalable web application to manage and split group expenses efficiently, with optimized settlement logic to minimize transactions between users.

---

## 🚀 Features

- User authentication using JWT
- Group creation and member management
- Add and track shared expenses within groups
- Optimized settlement algorithm to calculate net balances
- Minimizes the number of transactions between users
- RESTful API design with modular architecture
- Secure and scalable backend

---

## 🧠 Core Idea

Instead of handling multiple peer-to-peer payments, the system computes **net balances** for each user and generates a **minimal set of settlements** between debtors and creditors.

This approach reduces redundant transactions and improves clarity in group expense management.

---

## 🛠 Tech Stack

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Mongoose

### Frontend
- React.js
- Axios
- React Router

