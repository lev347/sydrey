# Sydreys Enterprise 🌱

Sydreys Enterprise is a full-stack e-commerce platform focused on selling and managing agricultural products like **ginger**, **turmeric**, and **garlic**. It supports both **customers** and **farmers**, with an admin panel for managing products and orders.

## 👤 Developed by
**Levince Otieno**  
Nairobi, Kenya

---

## 🔧 Technologies Used

### 🌐 Frontend
- EJS Templates
- JavaScript
- CSS (Dark green theme for branding)
- Responsive Design (Mobile-friendly layout)

### 🖥️ Backend
- Node.js
- Express.js

### 🗄️ Database
- MySQL (Hosted on **ScaleGrid**)

### ☁️ Hosting
- Application hosted on **Koyeb**

---

## 👨‍💼 User Roles

### 1. Customers and Farmers
- Register and log in
- View products
- Place orders
- Track order status
- Update profile (name, phone, email, password, profile photo)
- Delete account
- Book services (e.g., education, agronomist visits)

### 2. Admin
- Access via special passkey stored in `.env` (e.g., `ABCDE`)
- Add, edit, or delete products
- View and manage orders
- Update order status (pending → processing → shipped → delivered)

---

## 📦 Key Features

- 🌱 Product listings: Ginger, Turmeric, Garlic
- 🛒 Cart system with item count
- 🧾 Order history with delete option
- 📅 Service booking system (education & agronomist)
- 🧑‍🌾 Role-based access (customers, farmers, admins)
- 🔐 Secure login and registration
- 🌐 Public home page with limited access for guests
- 📱 Mobile-responsive with dropdown navigation for small screens
- 🖼️ Profile photo support and custom UI

---

## 🧪 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/lev347/sydrey.git
   cd sydrey
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```
   
3. **Configure environment variables:**
   Create a .env file and add:
   ```bash
   DB_HOST=your-scalegrid-host
   DB_USER=your-db-user
   DB_PASSWORD=your-db-password
   DB_NAME=your-db-name
   ADMIN_PASSKEY=ABCDE
   ```
   
4. **Start the app:**
   ```bash
   npm start
   ```
5. **Visit** http://localhost:3000

## 🚀 Deployment
The app is hosted live on Koyeb, and the MySQL database is managed through ScaleGrid. It is accessible on mobile browsers with a responsive design optimized for Android.

## 🎯 Project Goal
To empower farmers by connecting them directly with customers and providing support services like education and agronomy. This system also helps streamline the agricultural supply chain digitally.
   
