# E-Commerce Web Application

This is a fully functional **E-Commerce Web Application** built using **Java Spring Boot** and other modern web technologies. The application includes two modules:

- **User Module** – Allows users to browse, add to cart, place orders, and manage their profiles.
- **Admin Module** – Enables admins to manage products, view orders, and perform other administrative tasks.

---

## **Features**

### **User Module:**
- User Registration & Login with Authentication
- Secure Password Encryption
- Browse Products and Add to Cart
- Place Orders and View Order History
- Update User Profile

### **Admin Module:**
- Admin Login & Authentication
- Add, Edit, and Delete Products
- View and Manage Orders
- View Registered Users and Their Orders

---

## **Technologies Used**

### **Backend:**
- Java with Spring Boot
- Hibernate ORM
- Spring Security for Authentication & Authorization
- MySQL for Database Management

### **Frontend:**
- HTML, CSS, Bootstrap for UI Design
- JavaScript for Interactive Features
- Thymeleaf for Dynamic HTML Rendering

---

## **Project Structure**

/shopping-cart-spring-boot
├── /src
│   ├── /main
│   │   ├── /java/com/example/ecommerce
│   │   │   ├── /controller
│   │   │   │   ├── AdminController.java
│   │   │   │   ├── CartController.java
│   │   │   │   ├── OrderController.java
│   │   │   │   ├── ProductController.java
│   │   │   │   └── UserController.java
│   │   │   ├── /model
│   │   │   │   ├── Cart.java
│   │   │   │   ├── Order.java
│   │   │   │   ├── Product.java
│   │   │   │   └── User.java
│   │   │   ├── /repository
│   │   │   │   ├── CartRepository.java
│   │   │   │   ├── OrderRepository.java
│   │   │   │   ├── ProductRepository.java
│   │   │   │   └── UserRepository.java
│   │   │   ├── /service
│   │   │   │   ├── CartService.java
│   │   │   │   ├── OrderService.java
│   │   │   │   ├── ProductService.java
│   │   │   │   └── UserService.java
│   │   │   ├── /security
│   │   │   │   ├── SecurityConfig.java
│   │   │   │   └── JwtUtil.java
│   │   │   └── EcommerceApplication.java
│   │   └── /resources
│   │       ├── /static
│   │       │   ├── /css
│   │       │   │   └── styles.css
│   │       │   ├── /js
│   │       │   │   └── scripts.js
│   │       │   └── /images
│   │       └── /templates
│   │           ├── /admin
│   │           │   ├── admin-dashboard.html
│   │           │   └── manage-products.html
│   │           ├── /cart
│   │           │   └── cart.html
│   │           ├── /order
│   │           │   └── order-summary.html
│   │           ├── /product
│   │           │   └── product-list.html
│   │           └── /user
│   │               ├── login.html
│   │               └── register.html
│   └── /test
│       └── /java/com/example/ecommerce
│           └── EcommerceApplicationTests.java
├── /target
├── /.gitignore
├── /pom.xml
└── /README.md


