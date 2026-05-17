<h1>🛒 ShopEase - Full-Stack E-Commerce Website</h1>

<p>
    ShopEase is a fully functional e-commerce platform built with the <strong>MERN stack</strong> (MongoDB, Express, React, Node.js).
    It includes essential e-commerce features like product browsing, filtering, user authentication, order management, and secure online payments using <strong>Stripe</strong>.
    The project also includes a complete admin dashboard for managing products, categories, and customer orders.
</p>

<hr>

<h2>🚀 Features</h2>

<h3>✅ User Features</h3>
<ul>
    <li>🏠 <strong>Home Page</strong> – Browse featured and latest products.</li>
    <li>🔍 <strong>Product Listing</strong> – Filter products by category, subcategory, and price.</li>
    <li>🛒 <strong>Shopping Cart</strong> – Add, remove, and update cart items easily.</li>
    <li>💳 <strong>Stripe Payment</strong> – Secure online checkout using Stripe.</li>
    <li>📦 <strong>Order History</strong> – View previous orders and track order status.</li>
    <li>🔐 <strong>Authentication System</strong> – User registration and login using JWT.</li>
</ul>

<h3>🔑 Admin Features</h3>
<ul>
    <li>📦 <strong>Product Management</strong> – Add, edit, and delete products.</li>
    <li>📊 <strong>Order Management</strong> – Manage customer orders and update delivery status.</li>
    <li>🏷 <strong>Category Management</strong> – Manage categories and subcategories.</li>
</ul>

<hr>

<h2>💡 Tech Stack</h2>

<h3>Frontend</h3>
<ul>
    <li>React.js</li>
    <li>Redux Toolkit</li>
    <li>Axios</li>
    <li>React Router</li>
    <li>Tailwind CSS / CSS</li>
</ul>

<h3>Backend</h3>
<ul>
    <li>Node.js</li>
    <li>Express.js</li>
    <li>MongoDB with Mongoose</li>
</ul>

<h3>Authentication & Security</h3>
<ul>
    <li>JWT Authentication</li>
    <li>bcrypt Password Hashing</li>
</ul>

<h3>Payment Integration</h3>
<ul>
    <li>Stripe Payment Gateway</li>
</ul>

<hr>

<h2>🛠 Installation</h2>

<h3>1. Clone the Repository</h3>

<pre>
<code>
git clone https://github.com/your-username/ecommerce-fullstack-react-nodejs.git
cd ecommerce-fullstack-react-nodejs
</code>
</pre>

<h3>2. Install Dependencies</h3>

<strong>Frontend</strong>

<pre>
<code>
cd frontend
npm install
</code>
</pre>

<strong>Backend</strong>

<pre>
<code>
cd backend
npm install
</code>
</pre>

<strong>Admin Panel</strong>

<pre>
<code>
cd admin
npm install
</code>
</pre>

<hr>

<h2>⚙️ Environment Variables</h2>

<h3>Create <code>.env</code> file inside the <code>backend</code> folder</h3>

<pre>
<code>
PORT=3000
MONGO_URI=mongodb://localhost:27017
JWT_SECRET=your-access-secret-min-32-chars

STRIPE_SECRET_KEY=

CLOUDINARY_NAME=
CLOUDINARY_API_KEY=5
CLOUDINARY_SECRET_KEY=

ADMIN_EMAIL=admin@gmail.com
ADMIN_PASSWORD=123456
</code>
</pre>

<h3>Create <code>.env</code> file inside the <code>frontend</code> folder</h3>

<pre>
<code>
VITE_BACKEND_URL=http://localhost:3000
</code>
</pre>

<h3>Create <code>.env</code> file inside the <code>admin</code> folder</h3>

<pre>
<code>
VITE_BACKEND_URL=http://localhost:3000
</code>
</pre>

<hr>

<h2>🚀 Run the Project</h2>

<h3>Backend</h3>

<pre>
<code>
cd backend
npm run server
</code>
</pre>

<h3>Frontend</h3>

<pre>
<code>
cd frontend
npm run dev
</code>
</pre>

<h3>Admin Panel</h3>

<pre>
<code>
cd admin
npm run dev
</code>
</pre>

<hr>

<h2>🚦 Usage</h2>

<ol>
    <li>Open the frontend application in your browser.</li>
    <li>Create an account or login.</li>
    <li>Browse products and add items to your cart.</li>
    <li>Proceed to checkout and pay securely using Stripe.</li>
    <li>Admins can login to the admin dashboard to manage products and orders.</li>
</ol>

<hr>

<h2>📸 Screenshots</h2>

<table>
    <tr>
        <th>Home Page</th>
        <th>Products</th>
        <th>Admin Dashboard</th>
    </tr>

    <tr>
        <td>
            <img src="./screenshots/home.png" width="300" />
        </td>

        <td>
            <img src="./screenshots/products.png" width="300" />
        </td>

        <td>
            <img src="./screenshots/admin.png" width="300" />
        </td>
    </tr>
</table>

<hr>

<h2>🚀 Future Improvements</h2>

<ul>
    <li>⭐ Product reviews and ratings</li>
    <li>📍 Real-time order tracking</li>
    <li>❤️ Wishlist functionality</li>
    <li>📱 Progressive Web App (PWA)</li>
    <li>🌍 Multi-language support</li>
</ul>

<hr>

<h2>🤝 Contributing</h2>

<p>
    Contributions are welcome!
    Feel free to fork the repository and submit a pull request.
</p>

<hr>

<h2>🛡 License</h2>

<p>
    This project is licensed under the <strong>MIT License</strong>.
</p>

<hr>

<p align="center">
    <strong>⭐ If you like this project, don't forget to give it a star! 🌟</strong>
</p>
