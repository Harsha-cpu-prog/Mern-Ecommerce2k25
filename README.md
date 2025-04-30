✨ Features

🧑 User (Client) View

Browse products

Search and filter products

Add to cart

Checkout with PayPal

User registration & login

Order history

🔑 Admin View

Manage products (add, edit, delete)

Manage users

View and update orders

Upload product images using Cloudinary

🛠️ Tech Stack

Frontend: React, React Router, Axios, Tailwind/CSS ,Shadecn

Backend: Node.js, Express.js

Database: MongoDB (Mongoose)

Authentication: JSON Web Token (JWT)

Payments: PayPal API

Image Uploads: Cloudinary

Dev Tools: Concurrently, dotenv

🚀 Getting Started

🔧 Prerequisites

Node.js and npm installed

MongoDB URI (local or cloud)

Cloudinary account (with API key/secret)

PayPal sandbox account

📦 Installation

Clone the repository:

bash

git clone https://github.com/your-username/ecommerce-mern-app.git

cd ecommerce-mern-app

Install server dependencies:

bash

cd server

npm install

Install client dependencies:

bash

cd ../client

npm install

⚙️ Environment Variables

Server (server/.env)

env

MONGO_URI=your_mongodb_uri

CLOUDINARY_CLOUD_NAME=your_cloud_name

CLOUDINARY_API_KEY=your_api_key

CLOUDINARY_API_SECRET=your_api_secret

PAYPAL_CLIENT_ID=your_paypal_client_id

PAYPAL_CLIENT_SECRET=yout_paypal_client_secret

▶️ Running the App

Start the Server (Port 5000)

cd server

npm run dev

Start the Client (Port 5173)

cd client

npm run dev

Open http://localhost:5173 in your browser.

🛡️ Admin Login

Admin credentials can be created via MongoDB manually or seeded through your script.

Once logged in as admin, additional dashboard functionalities will be available.



🙌 Acknowledgments
PayPal Developer Portal

Cloudinary Documentation

MERN stack community

