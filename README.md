# 🛒 ReBazar — Second-Hand Marketplace

<p align="center">
  A modern, secure, and responsive second-hand marketplace platform for buying and selling pre-owned products.
</p>

<p align="center">
  <a href="https://reseller-frontend-silk.vercel.app">🌐 Live Demo</a>
  ·
  <a href="https://github.com/avishekrayyash">GitHub</a>
</p>

---

## 📌 Overview

**ReBazar** is a full-stack second-hand marketplace platform designed to make buying and selling pre-owned products simple, secure, and convenient.

The platform connects **buyers, sellers, and administrators** through dedicated experiences and dashboards. Users can discover products, search by category, manage wishlists, place orders, and make secure payments through Stripe.

Sellers can manage their products and orders while monitoring sales and revenue. Administrators can manage users, products, orders, and overall marketplace activity.

ReBazar also promotes **sustainable shopping** by encouraging product reuse and reducing unnecessary waste.

---

## 🌐 Live Project

### Frontend

🔗 https://reseller-frontend-silk.vercel.app

### Backend API

🔗 https://reseller-backend-pi.vercel.app

---

# ✨ Key Features

## 🔐 Authentication & Authorization

* Email and password authentication
* Google authentication
* Better Auth integration
* Persistent user sessions
* Protected private routes
* Role-based access control
* Secure authentication flow
* Logout functionality

---

## 🛍️ Marketplace

Users can easily explore and discover second-hand products.

* Browse all products
* Product search
* Category-based browsing
* Featured products
* Product details
* Product condition information
* Product stock management
* Responsive product cards
* Seller information
* Wishlist functionality

---

## 👤 Buyer Features

Buyers have access to a personalized shopping experience.

* Browse available products
* View detailed product information
* Add products to wishlist
* Purchase products
* Secure Stripe checkout
* View order history
* View payment history
* Manage profile
* Track purchased products

---

## 🏪 Seller Features

Sellers can manage their marketplace activities through a dedicated dashboard.

* Seller dashboard
* Add new products
* Edit products
* Delete products
* Manage product inventory
* View customer orders
* Update order status
* Sales analytics
* Revenue statistics
* Product management

---

## 🛡️ Admin Features

Administrators can monitor and manage the entire marketplace.

* Admin dashboard
* User management
* Product moderation
* Order monitoring
* Platform analytics
* Marketplace statistics
* Manage platform activities

---

# 🏠 Home Page

The ReBazar homepage provides users with a complete overview of the marketplace.

### Main Sections

* Hero Banner
* Marketplace Statistics
* Featured Products
* Popular Categories
* Success Stories
* Sustainability Section
* Trusted Sellers
* Call-to-Action Sections

The homepage is designed to quickly communicate the platform's purpose and guide users toward exploring products.

---

# 💳 Payment System

ReBazar integrates **Stripe Checkout** to provide a secure online payment experience.

### Payment Features

* Stripe Checkout
* Secure payment flow
* Payment success page
* Payment status handling
* Transaction history
* Order-payment integration

---

# 🎨 UI & User Experience

The application focuses on providing a clean and modern marketplace experience.

### UI Features

* Fully responsive design
* Mobile-first layouts
* Dark / Light theme
* Modern marketplace interface
* Skeleton loading states
* Toast notifications
* Custom 404 page
* Responsive navigation
* Dashboard UI
* Interactive components
* Smooth animations

---

# 📱 Responsive Design

ReBazar is designed to provide a consistent experience across different screen sizes.

| Device      | Support |
| ----------- | ------- |
| 📱 Mobile   | ✅       |
| 📱 Tablet   | ✅       |
| 💻 Laptop   | ✅       |
| 🖥️ Desktop | ✅       |

---

# 🛠️ Tech Stack

## Frontend

* **Next.js 16** — React framework
* **React 19** — UI development
* **Tailwind CSS v4** — Styling
* **HeroUI** — UI components
* **Framer Motion** — Animations
* **Next Themes** — Dark/light theme
* **React Icons** — Icons
* **React Toastify** — Notifications
* **Recharts** — Analytics and charts

## Backend & Database

* **Node.js**
* **MongoDB**
* **Better Auth**
* **MongoDB Adapter**

## Payment

* **Stripe**
* **Stripe.js**

---

# 📦 NPM Packages

```bash
@better-auth/mongo-adapter
@heroui/react
@heroui/styles
@stripe/stripe-js
better-auth
framer-motion
mongodb
next
next-themes
react
react-dom
react-icons
react-toastify
recharts
stripe
```

---

# 📄 Main Pages

### Public Pages

* 🏠 Home
* 🛍️ Products
* 📦 Product Details
* 🗂️ Categories
* ℹ️ About
* 📞 Contact
* 🔐 Login
* 📝 Register

---

# 👤 Buyer Dashboard

Buyers have access to:

* Dashboard
* My Orders
* Wishlist
* Payment History
* Profile

---

# 🏪 Seller Dashboard

Sellers can manage:

* Dashboard
* Add Product
* My Products
* Manage Orders
* Sales Analytics

---

# 🛡️ Admin Dashboard

Administrators can access:

* Dashboard
* Manage Users
* Manage Products
* Manage Orders
* Platform Analytics

---

# 📂 Project Architecture

The application follows a modular architecture that separates pages, reusable components, authentication, dashboards, and marketplace functionality.

```text
ReBazar/
│
├── app/
│   ├── page.js
│   ├── products/
│   ├── categories/
│   ├── login/
│   ├── register/
│   ├── dashboard/
│   │   ├── buyer/
│   │   ├── seller/
│   │   └── admin/
│   └── ...
│
├── components/
│   ├── Navbar/
│   ├── Footer/
│   ├── ProductCard/
│   ├── Hero/
│   └── ...
│
├── lib/
│   ├── auth/
│   ├── mongodb/
│   └── ...
│
├── public/
│   └── images/
│
├── package.json
├── next.config.js
└── README.md
```

> The exact structure may vary depending on the current project implementation.

---

# 🚀 Getting Started

Follow the steps below to run ReBazar locally.

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/reseller-frontend.git
```

## 2. Navigate to the Project

```bash
cd reseller-frontend
```

## 3. Install Dependencies

```bash
npm install
```

## 4. Configure Environment Variables

Create a `.env.local` file in the project root.

```env
# MongoDB
MONGODB_URI=your_mongodb_connection_string

# Better Auth
BETTER_AUTH_SECRET=your_better_auth_secret

# Google Authentication
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

# Stripe
STRIPE_SECRET_KEY=your_stripe_secret_key
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key

# Backend API
NEXT_PUBLIC_API_URL=your_backend_api_url
```

> Never commit `.env.local` or expose secret keys in a public repository.

---

## 5. Run Development Server

```bash
npm run dev
```

The application will run at:

```text
http://localhost:3000
```

---

# 📜 Available Scripts

### Development

```bash
npm run dev
```

Starts the Next.js development server.

### Production Build

```bash
npm run build
```

Creates an optimized production build.

### Production Server

```bash
npm start
```

Starts the production server.

### Lint

```bash
npm run lint
```

Checks the project for code quality and linting issues.

---

# 🔄 Application Flow

```text
                    ┌─────────────────┐
                    │     ReBazar     │
                    └────────┬────────┘
                             │
              ┌──────────────┼──────────────┐
              │              │              │
          👤 Buyer        🏪 Seller       🛡️ Admin
              │              │              │
              ▼              ▼              ▼
        Browse Products  Manage Products  Manage Users
        Wishlist         Manage Orders    Manage Products
        Checkout         Sales Analytics   Manage Orders
        My Orders        Revenue Stats     Platform Analytics
              │
              ▼
        💳 Stripe Checkout
              │
              ▼
        📦 Order Processing
```

---

# 🔒 Security

The application implements several security-focused practices:

* Protected routes
* Authentication-based access control
* Role-based dashboard access
* Secure authentication using Better Auth
* Environment variables for sensitive credentials
* Secure Stripe payment processing
* Server-side handling of sensitive operations

---

# 📊 Dashboard Analytics

ReBazar provides visual analytics for sellers and administrators using **Recharts**.

### Seller Analytics

* Sales statistics
* Revenue statistics
* Product performance
* Order statistics

### Admin Analytics

* User statistics
* Product statistics
* Order statistics
* Platform activity

---

# 🌱 Sustainability

ReBazar is designed around the concept of **sustainable consumption**.

By providing a platform for buying and selling pre-owned products, the project encourages:

* ♻️ Product reuse
* 🌱 Reduced waste
* 💰 Affordable shopping
* 🔄 Extending product life cycles
* 🤝 Community-based commerce

---

# 🎯 Project Objectives

The main objectives of ReBazar are to:

1. Build a modern second-hand marketplace.
2. Provide a secure buying and selling experience.
3. Connect buyers and sellers through a centralized platform.
4. Implement secure online payments.
5. Provide role-based dashboards.
6. Create a responsive and accessible user interface.
7. Promote sustainable and reusable consumption.
8. Provide useful analytics for sellers and administrators.

---

# 🔮 Future Improvements

Potential future enhancements include:

* 💬 Real-time buyer-seller messaging
* 🔔 Real-time notifications
* ⭐ Product reviews and ratings
* 📍 Location-based product discovery
* 🔎 Advanced product filtering
* 🤖 AI-powered product recommendations
* 📈 More advanced seller analytics
* 🚚 Delivery tracking
* 🧾 Automated invoices
* ❤️ Personalized recommendations
* 📱 Progressive Web App support

---

# 🧪 Testing

Future testing improvements can include:

* Unit testing
* Component testing
* API testing
* Authentication testing
* Payment flow testing
* End-to-end testing

---

# 📸 Screenshots

Add screenshots of your application here to showcase the UI.

### Homepage

```text
Add homepage screenshot here
```

### Product Page

```text
Add product page screenshot here
```

### Buyer Dashboard

```text
Add buyer dashboard screenshot here
```

### Seller Dashboard

```text
Add seller dashboard screenshot here
```

### Admin Dashboard

```text
Add admin dashboard screenshot here
```

---

# 👨‍💻 Author

## Avishek Roy Yash

**Full Stack Developer | Aspiring Software Engineer**

📧 Email: `avishekroyyash@gmail.com`

🔗 GitHub: [github.com/avishekroyyash](https://github.com/avishekrayyash)

🔗 LinkedIn: [linkedin.com/in/avishek-roy-yash](https://linkedin.com/in/avishek-ray-yash)

---

# ⭐ Support

If you like this project, consider giving the repository a ⭐ **Star** on GitHub.

Your support and feedback are highly appreciated!

---

# 📄 License

This project is developed for **educational and portfolio purposes**.

© 2026 Avishek Roy Yash. All rights reserved.
