# 🛒 SmartCart

**SmartCart** is a full-stack multi-vendor marketplace that connects farmers, local grocery stores, and customers through a single platform. Customers can compare prices, seller ratings, and nearby sellers before purchasing, while farmers and grocery store owners can manage their own products, inventory, and orders.

Unlike traditional e-commerce platforms, SmartCart allows customers to purchase products from multiple sellers using a **single shopping cart** and **one checkout**, while the backend automatically splits the order for each seller.

---

## 🚀 Features

### 👤 Customer
- User Registration & Login
- JWT Authentication
- Browse Products
- Search & Filter Products
- Compare Prices from Multiple Sellers
- View Seller Ratings & Distance
- Add to Cart
- Single Checkout
- Order History
- Track Orders
- Product Reviews

### 👨‍🌾 Farmer
- Register as Seller
- Manage Products
- Manage Inventory
- Update Product Prices
- View Orders
- Sales Dashboard

### 🏪 Grocery Store
- Register as Seller
- Product Management
- Inventory Management
- Order Management

### 👨‍💼 Admin
- Approve Sellers
- Manage Users
- Manage Products
- Monitor Orders
- Dashboard & Analytics

---

# ✨ Key Highlights

- Multi-Vendor Marketplace
- Role-Based Authentication
- Unified Shopping Cart
- Single Checkout
- Automatic Order Splitting
- Product Price Comparison
- Nearby Seller Recommendation
- Inventory Management
- Modular & Scalable Architecture

---

# 🛠 Tech Stack

## Frontend

- React.js
- React Router
- Axios
- Tailwind CSS

## Backend

- Spring Boot
- Spring Security
- JWT Authentication
- Spring Data JPA

## Database

- MySQL

## Image Storage

- Cloudinary

## APIs

- Google Maps API *(Planned)*
- Razorpay Payment Gateway *(Planned)*

---

# 📂 Project Structure

```
SmartCart
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── assets/
│
├── backend/
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── entity/
│   ├── dto/
│   ├── config/
│   ├── security/
│   └── exception/
│
└── README.md
```

---

# 👥 User Roles

- Customer
- Farmer
- Grocery Store Owner
- Admin

---

# 🗄 Database Design

Main Entities

- User
- Seller
- Product
- Category
- Cart
- CartItem
- Order
- SellerOrder
- OrderItem
- Payment
- Review
- Address

---

# 🔄 Workflow

```
Seller Registration
        │
        ▼
Admin Verification
        │
        ▼
Seller Adds Products
        │
        ▼
Customer Searches Product
        │
        ▼
Compare Prices
        │
        ▼
Add to Cart
        │
        ▼
Single Checkout
        │
        ▼
Payment
        │
        ▼
Backend Splits Orders
        │
        ▼
Seller Receives Orders
        │
        ▼
Order Delivered
```

---

# 🎯 Future Enhancements

- Google Maps Integration
- Real-Time Order Tracking
- AI Product Recommendations
- Delivery Partner Module
- Coupon System
- Wishlist
- Notifications
- Sales Analytics
- Voice Search
- Product Recommendation Engine

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/SmartCart.git
```

---

## Backend

```bash
cd backend
```

Configure your **application.properties**

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/smartcart
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
```

Run the Spring Boot application.

---

## Frontend

```bash
cd frontend
npm install
npm start
```

---

# 📸 Screenshots

> Screenshots will be added after development.

---

# 📈 Project Status

🚧 Under Development

Current Progress

- [ ] Authentication
- [ ] User Roles
- [ ] Product Management
- [ ] Search & Filter
- [ ] Price Comparison
- [ ] Shopping Cart
- [ ] Checkout
- [ ] Order Splitting
- [ ] Admin Dashboard
- [ ] Google Maps Integration

---

# 🤝 Contributing

Contributions, suggestions, and feature requests are welcome.

Feel free to fork the repository and submit a pull request.

---

# 📄 License

This project is developed for educational and portfolio purposes.

---

## 👨‍💻 Author

**Pagadala Jaya Ram**

GitHub: https://github.com/pagadalajayaram
