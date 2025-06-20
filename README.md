MERN Product Management App
A full-stack Product Management Application built with the MERN Stack (MongoDB, Express, React, Node.js). This app allows you to create, read, update, and delete products with fields like name, price, and image URL.

📁 Project Structure
mern-product/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   └── (React app with Zustand store)
├── .env
├── package.json
├── README.md


🚀 Features
Add, update, delete products
View all products on homepage
Zustand for global state management
MongoDB as the database
REST API with Express.js
React frontend served by Node in production


🧰 Technologies Used
Frontend: React + Vite + Zustand
Backend: Node.js + Express.js
Database: MongoDB + Mongoose
State Management: Zustand
Env Management: dotenv
Cross-platform Scripts: cross-env


📦 Installation Steps
Clone the repo: git clone https://github.com/asha-16/mern-product.git
                cd mern-product
Install all dependencies: npm install
                          npm install --prefix frontend
Set up .env file in the root: MONGO_URI=your_mongodb_connection_string
                              PORT=5000
Run in Development: npm run dev
                    Backend: http://localhost:5000
                    Frontend: http://localhost:5173


🏁 Run in Production
Build frontend: npm run build
Start server: npm run start
Then go to: http://localhost:5000


🧪 API Endpoints
Method	    Endpoint	          Description
GET	        /api/products	      Get all products
POST	      /api/products	      Create a product
PUT	        /api/products/:id	  Update a product
DELETE	   /api/products/:id	  Delete a product


🌐 Example Product Format
{
  "name": "Jacket",
  "price": 1499,
  "image": "https://example.com/image.jpg"
}



