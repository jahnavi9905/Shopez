🛒 ShopEZ - Ecommerce Website ShopEZ is a full-stack ecommerce web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). It provides a seamless online shopping experience for customers and an efficient management dashboard for sellers.

📌 Features 🛍️ For Customers: User Registration & Login (JWT Authentication)

Product Browsing and Search

Add to Cart

Place Orders

View Order History

🧑‍💼 For Sellers/Admin: Product Management (Add, Update, Delete Products)

Order Management

Dashboard Analytics

🏗️ Tech Stack Technology Usage Frontend React.js Backend Node.js, Express.js Database MongoDB (Mongoose) Styling CSS, Bootstrap, etc

📂 Project Structure bash Copy Edit ShopEZ-ecommerce-website-master/ ├── client/ # React Frontend ├── server/ # Node.js Backend (Express API) ├── demo.mp4 # Project Demo Video ├── README.md # Project Info 🚀 Installation & Running Locally Prerequisites: Node.js

MongoDB (Local or Atlas)

Backend Setup: bash Copy Edit cd server npm install Create a .env file inside /server and add your MongoDB connection string:

ini Copy Edit MONGO_URL=your_mongodb_connection_string PORT=6001 JWT_SECRET=your_jwt_secret Run the backend server:

bash Copy Edit npm start Frontend Setup: bash Copy Edit cd ../client npm install npm start Frontend runs at: http://localhost:3000

Backend runs at: http://localhost:6001

📽️ Demo Video ▶️ Watch Project Demo

✅ Functionalities Covered: User authentication with JWT

CRUD for products

Cart functionality

Placing orders

Admin product management

Order status updates

RESTful API with Express

State management with React Hooks & Context API (if used)

🛠️ Future Improvements: Payment gateway integration (e.g., Stripe, Razorpay)

Deployment (Netlify for frontend, Render/Heroku for backend)

Image uploads for products

More user roles (like Admin, Seller)
