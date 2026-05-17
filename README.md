# 🛒 ShopEase - Full-Stack E-Commerce Website

ShopEase is a modern and fully functional **E-Commerce Platform** built using the **MERN Stack**  
(**MongoDB, Express.js, React.js, Node.js**).

The platform provides a complete shopping experience for customers along with a powerful admin dashboard for managing products, categories, and customer orders.

---

# 🚀 Features

## ✅ User Features

- 🏠 Browse featured and latest products
- 🔍 Filter products by category, subcategory, and price
- 🛒 Add, remove, and update cart items
- 💳 Secure online payments using Stripe
- 📦 View order history and order status
- 🔐 User authentication using JWT
- ❤️ Responsive modern UI

---

## 🔑 Admin Features

- 📦 Add, edit, and delete products
- 📊 Manage customer orders
- 🏷 Manage categories and subcategories
- ☁ Upload product images using Cloudinary
- 🔒 Secure admin authentication

---

# 💡 Tech Stack

## Frontend

- React.js
- Redux Toolkit
- Axios
- React Router DOM
- Tailwind CSS

---

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose

---

## Authentication & Security

- JWT Authentication
- bcrypt Password Hashing

---

## Payment Integration

- Stripe Payment Gateway

---

## Cloud Storage

- Cloudinary

---

# 🛠 Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/ecommerce-fullstack-react-nodejs.git

cd ecommerce-fullstack-react-nodejs
```

---

## 2️⃣ Install Dependencies

### 📌 Backend

```bash
cd backend
npm install
```

### 📌 Frontend

```bash
cd frontend
npm install
```

### 📌 Admin Panel

```bash
cd admin
npm install
```

---

# ⚙️ Environment Variables

## 📌 Backend `.env`

Create a `.env` file inside the `backend` folder and add the following:

```env
# Enter your backend port
PORT=your_backend_port

# Enter your MongoDB connection string
MONGO_URI=your_mongodb_connection_string

# Enter your JWT secret key
JWT_SECRET=your_jwt_secret_key

# Enter your Stripe secret key
STRIPE_SECRET_KEY=your_stripe_secret_key

# Enter your Cloudinary cloud name
CLOUDINARY_NAME=your_cloudinary_name

# Enter your Cloudinary API key
CLOUDINARY_API_KEY=your_cloudinary_api_key

# Enter your Cloudinary secret key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key

# Enter your admin email
ADMIN_EMAIL=your_admin_email

# Enter your admin password
ADMIN_PASSWORD=your_admin_password
```

---

## 📌 Frontend `.env`

Create a `.env` file inside the `frontend` folder and add the following:

```env
# Enter your backend API URL
VITE_BACKEND_URL=your_backend_api_url
```

---

## 📌 Admin `.env`

Create a `.env` file inside the `admin` folder and add the following:

```env
# Enter your backend API URL
VITE_BACKEND_URL=your_backend_api_url
```

---

# 🚀 Run the Project

## ▶ Run Backend

```bash
cd backend
npm run server
```

---

## ▶ Run Frontend

```bash
cd frontend
npm run dev
```

---

## ▶ Run Admin Panel

```bash
cd admin
npm run dev
```

---

# 🌐 Default Local URLs

| Service | URL |
|----------|------|
| Frontend | http://localhost:5173 |
| Admin Panel | http://localhost:5174 |
| Backend API | http://localhost:3000 |

---

# 📸 Screenshots

| Home Page | Products Page | Admin Dashboard |
|------------|----------------|------------------|
| ![](./screenshots/home.png) | ![](./screenshots/products.png) | ![](./screenshots/admin.png) |

---

# 🚀 Future Improvements

- ⭐ Product reviews and ratings
- ❤️ Wishlist functionality
- 📍 Real-time order tracking
- 📱 Progressive Web App (PWA)
- 🌍 Multi-language support
- 🔔 Notifications system

---

# 🤝 Contributing

Contributions are welcome!

Feel free to fork the repository and submit a pull request.

---

# 🛡 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If you like this project, don't forget to give it a **Star ⭐** on GitHub.
