# 🛍️ Product Store

A full-stack Product Store application built with React, Node.js, Express, and MongoDB. Users can manage products through a modern web interface with CRUD operations and persistent database storage.

## 🚀 Features

- View all products
- Add new products
- Update existing products
- Delete products
- Responsive UI
- RESTful API architecture
- MongoDB database integration
- State management using Zustand
- Modern UI built with Chakra UI

## 🛠️ Tech Stack

### Frontend
- React 19
- Vite
- Chakra UI
- React Router DOM
- Zustand
- React Icons

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- dotenv

### Development Tools
- Nodemon
- ESLint
- Cross-env

---

## 📂 Project Structure

```text
Product-Store/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── vite.config.js
│
├── package.json
└── README.md
```

---

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/sRao2405/Product-Store.git
cd Product-Store
```

### 2. Install Dependencies

Root dependencies:

```bash
npm install
```

Frontend dependencies:

```bash
cd frontend
npm install
```

---

## 🔐 Environment Variables

Create a `.env` file inside the root directory.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
NODE_ENV=development
```

---

## ▶️ Running the Application

### Development Mode

```bash
npm run dev
```

Backend runs with Nodemon and automatically restarts on file changes.

### Frontend

```bash
cd frontend
npm run dev
```

---

## 🏗️ Production Build

Build the frontend:

```bash
npm run build
```

Start production server:

```bash
npm start
```

---

## 📡 API Endpoints

### Product Routes

| Method | Endpoint | Description |
|----------|----------|-------------|
| GET | /api/products | Fetch all products |
| POST | /api/products | Create a product |
| PUT | /api/products/:id | Update a product |
| DELETE | /api/products/:id | Delete a product |

---

## 📸 Screenshots

Add screenshots here after deployment.

```md
![Home Page](screenshots/home.png)
```

---

## 🎯 Future Improvements

- User Authentication
- Product Search
- Product Categories
- Image Upload Support
- Pagination
- Dark Mode
- Wishlist Feature
- Shopping Cart

---

## 👨‍💻 Author

**Sahil Rao**

GitHub: https://github.com/sRao2405

---

## 📄 License

This project is licensed under the ISC License.
