🛍️ Bazaar - eCommerce MERN App
Welcome to Bazaar, a full-featured, robust eCommerce platform crafted with the MERN Stack (MongoDB, Express.js, React, Node.js). Bazaar offers a streamlined online shopping experience packed with essential functionalities to elevate user satisfaction.

✨ Key Features
🛒 Full Shopping Cart: Effortlessly add, remove, and manage products in a streamlined cart experience.
⭐ Product Reviews & Ratings: Users can rate and review products to inform others.
🎠 Top Products Carousel: Showcase top-rated products in an eye-catching carousel.
📄 Product Pagination: Smooth navigation with paginated product listings.
🔍 Search Functionality: Easily search for products using keywords.
👤 User Profiles: Users can create accounts, track orders, and manage profile settings.
⚙️ Admin Dashboard: A powerful admin interface to manage all aspects of the platform, including:
Admin Accounts: Manage admin-level permissions.
Product Management: Add, edit, and delete products.
User Management: Manage customer accounts.
Order Management: View, update, and mark orders as "delivered."
💳 Secure Checkout: Complete checkout process with options for shipping and payments via Razorpay.
🚀 Database Seeder: Quickly populate the database with sample data for testing and setup.
🚀 Getting Started
📌 Prerequisites
Fork this repository.

Clone the forked repository to your local machine:

bash
Copy code
git clone https://github.com/Vanshahuja1/Bazaar.git
cd MERN-eCommerce
MongoDB: Create a MongoDB database (MongoDB Atlas).

Razorpay: Set up an account to obtain Key ID & Secret (Razorpay).

Brevo: Set up a Brevo account and create an SMTP Key (Brevo).

🔑 Environment Variables
Rename .env.example to .env and update the following details:

dotenv
Copy code
NODE_ENV=development
PORT=5000
JWT_SECRET=ADD_YOUR_JWT_SECRET_HERE
MONGO_URI=ADD_YOUR_MONGO_URI_HERE
RAZORPAY_KEY_ID=ADD_YOUR_RAZORPAY_KEY_ID
RAZORPAY_KEY_SECRET=ADD_YOUR_RAZORPAY_KEY_SECRET
PAGINATION_MAX_LIMIT=12
EMAIL_HOST=smtp-relay.brevo.com
EMAIL_PORT=587
EMAIL_USER=ADD_YOUR_BREVO_LOGIN
EMAIL_PASS=ADD_YOUR_BREVO_PASSWORD
EMAIL_FROM=ADD_YOUR_BREVO_LOGIN
📦 Install Dependencies
Install dependencies for both backend and frontend:

bash
Copy code
# Backend dependencies
npm install

# Frontend dependencies
cd frontend
npm install
▶️ Run the Application
To run both the frontend and backend concurrently:

bash
Copy code
npm run dev
To run only the backend:

bash
Copy code
npm run server
📤 Build for Production
To create a production build for the frontend:

bash
Copy code
cd frontend
npm run build
🔄 Database Seeding
Use the following commands to populate the database with sample users and products, or to clear all data:

bash
Copy code
# Import sample data
npm run data:import

# Destroy all data
npm run data:destroy
👥 Sample Users for Testing
Admin Dashboard:

Email: admin@admin.com
Password: admin123
Customer Accounts:

John Doe
Email: john@email.com
Password: john123
Alice Smith
Email: alice@email.com
Password: alice123
Feel free to explore and customize Bazaar to suit your specific needs. Happy coding! 🎉

🤝 Contributing to Bazaar
Your contributions are valuable! We welcome the community to help improve Bazaar by adding new features, fixing issues, or providing feedback.

Getting Started
Fork the repository.

Clone your fork:

bash
Copy code
git clone https://github.com/Vanshahuja1/Bazaar.git
cd MERN-eCommerce
Create a New Branch for your contribution:

bash
Copy code
git checkout -b feature/your-feature-name
Making Changes
Implement your changes.
Test thoroughly to avoid introducing bugs.
Update documentation if needed.
Submitting Changes
Commit your changes with a descriptive message:

bash
Copy code
git add .
git commit -m "Add new feature or fix"
Push your changes:

bash
Copy code
git push origin feature/your-feature-name
Creating a Pull Request
Visit your fork on GitHub.
Open a New Pull Request and provide details of your changes.
Code Review
Our team will review your pull request, and we may suggest adjustments to ensure quality and compatibility.

Thank you for considering a contribution to Bazaar! If you have any questions, feel free to reach out. Happy coding! ✨