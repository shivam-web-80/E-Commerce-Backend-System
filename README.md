# Project Description

Complete E-commerce Backend System
Build a full-featured e-commerce backend with authentication, product management, orders, payments, and admin dashboard
Node.js with Express.js framework

## Features

- Full CRUD (Create, Read, Update, Delete) operations for product ,user,review,order,cart
- RESTful API Design
  Built following REST principles with predictable, resource-based endpoints and standard HTTP methods.
- MongoDB with Mongoose ODM for database operations
- JWT authentication with refresh tokens stored in HTTP-only cookies
- Argon2 for secure password hashing during registration/login
- Express-validator for comprehensive request validation
- Multer for file uploads with Cloudinary integration for image storage
- Nodemailer for sending transactional emails (order confirmations, password reset)
- Helmet.js for setting secure HTTP headers
- CORS configuration for cross-origin requests
- Rate limiting to prevent brute force attacks
- XSS protection for input sanitization
- use ethereal.email to verify with email or updatepassword or confirm order


## Folder Structure :

```

├── src/
│ ├── models/
│ │ ├── User.js
│ │ ├── Product.js
│ │ ├── Category.js
│ │ ├── Cart.js
│ │ ├── Order.js
│ │ ├── Review.js
│ │ └── Token.js
│ │
│ ├── validation/
│ │ ├── authValidation.js
│ │ ├── productValidation.js
│ │ ├── orderValidation.js
│ │ ├── userValidation.js
│ │ └── tokenValidation.js
│ │
│ ├── controllers/
│ │ ├── authController.js
│ │ ├── productController.js
│ │ ├── cartController.js
│ │ ├── orderController.js
│ │ ├── reviewController.js
│ │ ├── userController.js
│ │ └── adminController.js
│ │
│ ├── routes/
│ │ ├── authRoutes.js
│ │ ├── productRoutes.js
│ │ ├── cartRoutes.js
│ │ ├── orderRoutes.js
│ │ ├── reviewRoutes.js
│ │ ├── userRoutes.js
│ │ └── adminRoutes.js
│ │
│ ├── middlewares/
│ │ ├── authMiddleware.js
│ │ ├── errorMiddleware.js
│ │ ├── notFoundMiddleware.js
│ │ ├── validationMiddleware.js
│ │ ├── uploadMiddleware.js
│ │ ├── rateLimitMiddleware.js
│ │ └── tokenMiddleware.js
│ │
│ ├── utils/
│ │ ├── asyncHandler.js
│ │ ├── sendEmail.js
│ │ ├── cloudinary.js
│ │ ├── generateToken.js
│ │ ├── apiFeatures.js
│ │ ├── generateResetToken.js
│ │ └── passwordUtils.js
│ │
│ └── app.js
├── package.json
├── .env
├── .env.example
├── .gitignore
└── README.md
```
