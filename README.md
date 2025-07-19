# RAD Shopping App

A full-stack MERN (MongoDB, Express, React, Node.js) shopping cart application.  
Frontend deployed on **Vercel**, backend on **Render**, and database on **MongoDB Atlas**.

---

## 🚀 Live Demo

- **Frontend (Vercel):** [https://rad-shopping-app.vercel.app/](https://rad-shopping-app.vercel.app/)
- **Backend API (Render):** [https://rad-shopping-app.onrender.com](https://rad-shopping-app.onrender.com)

---

## 📸 Screenshots

### Login Page
![Login Page](Screenshot%20login.png)

### Register Page
![Register Page](Screenshot%20register.png)

### Home Page
![Home Page](Screenshot%20home.png)

### Cart Page
![Cart Page](Screenshot%20cart.png)

---

## 🛠️ Tech Stack

- **Frontend:** React, Vite, React Router, Axios, SweetAlert2, React Hot Toast
- **Backend:** Node.js, Express, Mongoose, JWT, CORS, dotenv
- **Database:** MongoDB Atlas

---

## 📂 Project Structure

```
client/         # React frontend
server/         # Express backend
```

---

## ⚙️ Setup & Installation

### 1. Clone the repository

```sh
git clone https://github.com/your-username/rad-shopping-app.git
cd rad-shopping-app
```

### 2. Environment Variables

Set the following in `server/.env`:
- `MONGO_URI` (MongoDB Atlas connection string)
- `PORT` (e.g., 5005)
- `CLIENT_URL` (Frontend URL, e.g., http://localhost:5173)
- `JWT_SECRET` (your secret)

Set the following in `client/.env`:
- `VITE_BASE_URL` (Backend API URL, e.g., http://localhost:5005)

### 3. Install dependencies

```sh
cd server
npm install
cd ../client
npm install
```

### 4. Run locally

- **Backend:**
  ```sh
  cd server
  npm run dev
  ```
- **Frontend:**
  ```sh
  cd client
  npm run dev
  ```

---

## 🚀 Deployment

- **Frontend:** Deploy `client/` to [Vercel](https://vercel.com/)
- **Backend:** Deploy `server/` to [Render](https://render.com/)
- **Database:** Use [MongoDB Atlas](https://www.mongodb.com/atlas)

---

## 📝 Features

- User registration and login (JWT authentication)
- Browse products (fetched from fakestoreapi.com)
- Add to cart, adjust quantity, remove items
- Cart persistence per user
- Responsive UI with notifications

---

## 👤 Author

**Dev-Romm**

---

## 📄 License

This project is licensed under the ISC License.