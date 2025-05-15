

# Devotee - Devotional E-commerce Website

This is a full-stack e-commerce website focused on devotional products and user-friendly shopping experiences. It includes both frontend and backend components using **Core PHP**, **MySQL**, **HTML/CSS**, and **JavaScript**.

---

## 📁 Folder Structure

```
Devotee/
│
├── css/                      # Stylesheets
├── images/                   # Site images
├── js/                       # JavaScript files
├── project images/           # Sample product images
├── uploaded_img/             # Uploaded product images (runtime)
├── shop_db.sql               # SQL file for database setup
│
├── about.php                 # About page
├── contact.php               # Contact page
├── home.php                  # Homepage
├── shop.php                  # Product listing
├── category.php              # Category filtering
├── cart.php                  # Shopping cart
├── checkout.php             # Checkout process
├── orders.php                # User order history
├── login.php                 # User login
├── register.php              # User registration
├── logout.php                # User logout
├── search_page.php          # Product search
│
├── config.php                # Database connection settings
├── header.php                # Common site header
├── footer.php                # Common site footer
│
├── admin_page.php            # Admin dashboard
├── admin_header.php          # Admin header
├── admin_products.php        # Manage products
├── admin_update_product.php  # Edit products
├── admin_users.php           # Manage users
├── admin_orders.php          # View all orders
├── admin_contacts.php        # View contact form submissions
├── admin_update_profile.php  # Admin profile management
```

---

## ⚙️ Features

### 🛍️ User Side

* **Home Page**: Displays featured products and categories.
* **Shop Page**: Lists all products.
* **Category Filter**: Filter products based on categories.
* **Search**: Search for products by name.
* **Cart**: Add, remove, and update items in the cart.
* **Checkout**: Place orders securely.
* **Order History**: View your previous orders.
* **Authentication**: Register and log in securely.

### 🛠️ Admin Side

* **Dashboard**: Overview of users, orders, and products.
* **Product Management**: Add, update, or delete products.
* **User Management**: View all registered users.
* **Order Management**: View and update customer orders.
* **Messages**: View messages sent via the contact form.

---

## 🧑‍💻 Technologies Used

* **Frontend**: HTML5, CSS3, JavaScript
* **Backend**: PHP (Core PHP)
* **Database**: MySQL
* **Styling**: Custom CSS (in `css/` folder)

---

## 🏗️ Installation Guide

1. **Clone or Download this repository.**
2. **Place the project in your local server root (e.g., `htdocs` for XAMPP).**
3. **Create a MySQL Database:**

   * Open **phpMyAdmin**.
   * Create a database (e.g., `devotee_db`).
   * Import `shop_db.sql` into the created database.
4. **Update `config.php` with your database credentials:**

   ```php
   $conn = mysqli_connect('localhost','root','','devotee_db');
   ```
5. **Start Apache and MySQL** via XAMPP or your server.
6. **Access the website** at:

   ```
   http://localhost/Devotee/home.php
   ```

---

## 🔐 Admin Login

You can log in as admin from `admin_page.php` (credentials are defined in the database or hardcoded if required).

---

## 📸 Screenshots

*You can add screenshots of:*

* Home page
* Shop page
* Admin dashboard
* Product management panel

---

## 📝 To Do

* Add product reviews or ratings
* Implement email notifications for orders
* Integrate payment gateway
* Improve responsive design for mobile devices

---

## 🧾 License

This project is for educational purposes. You may reuse and modify it freely for non-commercial purposes.

---


