# E-Commerce Application

This is a full-stack e-commerce application with backend functionality for product, user, order, and payment management, along with role-based authorization and error handling.

## Features
- **User Authentication**: JWT-based login, registration, and role-based access.
- **Product Management**: Admin can add, update, delete, and view products. Users can view and review products.
- **Order Management**: Users can place orders, view order details, and track their orders. Admins can view and manage all orders.
- **Payment Processing**: Integration with Stripe for secure payment handling.
- **Error Handling**: Centralized error handling middleware.
- **Environment Configuration**: Flexible for development and production.

---

## Project Structure

project-backend/

├── config/

│   ├── config.env            # Environment variables

│   ├── database.js           # MongoDB connection setup

├── controllers/

│   ├── orderController.js    # Order-related logic

│   ├── paymentController.js  # Payment-related logic

│   ├── productController.js  # Product-related logic

│   ├── userController.js     # User-related logic

├── middleware/

│   ├── auth.js               # Authentication middleware

│   ├── catchAsyncErrors.js   # Error handling wrapper

│   ├── error.js              # Central error handling

├── models/

│   ├── orderModel.js         # Order schema

│   ├── productModel.js       # Product schema

│   ├── userModel.js          # User schema

├── routes/

│   ├── orderRoute.js         # Order-related routes

│   ├── paymentRoute.js       # Payment-related routes

│   ├── productRoute.js       # Product-related routes

│   ├── userRoute.js          # User-related routes

├── utils/

│   ├── apiFeatures.js        # Utility for API filtering, searching, and pagination

│   ├── errorhander.js        # Custom error handling class

│   ├── jwtoken.js            # Utility for generating JWT tokens

│   ├── sendEmail.js          # Utility for sending emails

├── app.js                    # Main Express app setup

├── server.js                 # Server entry point

├── node_modules/             # Node.js dependencies

├── .env                      # Environment variables (not to be pushed to GitHub)

├── .gitignore                # Ignored files and directories for Git

├── package.json              # Backend dependencies and scripts

├── README.md                 # Project documentation

├── yarn.lock / package-lock.json # Dependency lock file



