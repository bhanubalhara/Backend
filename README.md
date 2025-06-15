# Backend

# ShoppyGlobe Backend API

This is the backend API for the ShoppyGlobe E-commerce Application, built using Node.js, Express.js, and MongoDB. It includes user authentication, product management, and cart functionality.

---

##  Project Structure

backend/
| |__ authController.js
| |__  cartController.js
| |__  productController.js
|__  controllers/
|__ models/
| |__  User.js
| |__  Product.js
| |__  Cart.js
|__ routes/
| |__  auth.js
| |__  cart.js
| |__  products.js
|__ middleware/
| |__ authMiddleware.js
|__ config/
| |__ db.js
|__.env
|__server.js
|__package.json
|__ Thundercliend.pdf
|__ MongoDB.pdf

##  Features

-  User registration and login using JWT
-  Protected routes for cart management
-  Product CRUD (Create, Read, Update, Delete)
-  Cart operations (Add, Update, Delete)
-  MongoDB integration using Mongoose
-  Request validation and error handling
-  Tested with ThunderClient

  git clone https://github.com/bhanubalhara/Backend.git
   cd backend
