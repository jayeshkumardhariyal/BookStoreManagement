<h1 align="center">
📚 Book Store Management System
</h1>

<p align="center">
A Full-Stack Java Web Application for managing books, users, carts, orders, and inventory.
</p>

<p align="center">
<img src="https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=openjdk" />
<img src="https://img.shields.io/badge/JSP-Servlet-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/MySQL-Database-blue?style=for-the-badge&logo=mysql" />
<img src="https://img.shields.io/badge/Maven-Build-red?style=for-the-badge&logo=apachemaven" />
<img src="https://img.shields.io/badge/Tomcat-Server-yellow?style=for-the-badge" />
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
</p>

<p align="center">
<img src="./screenshots/banner.png" alt="Book Store Banner" width="100%">
</p>

---

<h2>🌟 Overview</h2>

<p>
Book Store Management System is a comprehensive e-commerce web application built using Java, JSP, Servlets, JDBC, and MySQL.
The platform enables users to browse books, manage carts, purchase books online, and sell old books while providing administrators with powerful inventory and order management capabilities.
</p>

---

<h2>✨ Key Highlights</h2>

<table>
<tr>
<td align="center">📚</td>
<td><b>Book Catalog Management</b></td>
<td>Browse New, Recent & Old Books</td>
</tr>

<tr>
<td align="center">🛒</td>
<td><b>Shopping Cart</b></td>
<td>Add, Remove & Manage Cart Items</td>
</tr>

<tr>
<td align="center">🔐</td>
<td><b>Authentication</b></td>
<td>User Registration, Login & Logout</td>
</tr>

<tr>
<td align="center">📦</td>
<td><b>Order Processing</b></td>
<td>Checkout & Order History</td>
</tr>

<tr>
<td align="center">👤</td>
<td><b>User Profiles</b></td>
<td>Update Profile & Address</td>
</tr>

<tr>
<td align="center">🛠️</td>
<td><b>Admin Dashboard</b></td>
<td>Manage Books, Users & Inventory</td>
</tr>

<tr>
<td align="center">♻️</td>
<td><b>Old Book Marketplace</b></td>
<td>Sell and Manage Used Books</td>
</tr>

</table>

---

<h2>🚀 Features</h2>

<h3>👨‍💼 User Features</h3>

✅ Register New Account
✅ Secure Login & Logout
✅ Browse Book Collections
✅ Search Books by Name
✅ View Detailed Book Information
✅ Add Books to Cart
✅ Remove Books from Cart
✅ Place Orders
✅ View Order History
✅ Update Personal Information
✅ Manage Delivery Address
✅ Sell Old Books

---

<h3>🛡️ Admin Features</h3>

✅ Admin Authentication
✅ Add New Books
✅ Update Book Information
✅ Delete Books
✅ Manage Inventory
✅ View All Books
✅ Track Orders
✅ Monitor Users

---

<h2>🏗️ System Architecture</h2>

<pre>
┌───────────────────────────────┐
│           Client UI           │
│      JSP + Bootstrap UI       │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│      Servlet Controllers      │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│        Service Layer          │
│  Business Logic Processing    │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│          DAO Layer            │
│     Database Operations       │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│            MySQL              │
└───────────────────────────────┘
</pre>

---

<h2>🧱 Technology Stack</h2>

<table>
<tr>
<th>Category</th>
<th>Technology</th>
</tr>

<tr>
<td>Backend</td>
<td>Java, JSP, Servlets, JDBC</td>
</tr>

<tr>
<td>Frontend</td>
<td>HTML5, CSS3, Bootstrap, JSTL</td>
</tr>

<tr>
<td>Database</td>
<td>MySQL</td>
</tr>

<tr>
<td>Server</td>
<td>Apache Tomcat</td>
</tr>

<tr>
<td>Build Tool</td>
<td>Maven</td>
</tr>

<tr>
<td>Version Control</td>
<td>Git & GitHub</td>
</tr>

</table>

---

<h2>📦 Dependencies</h2>

<pre>
javax.servlet:jstl:1.2
javax.servlet-api:4.0.1
mysql-connector-j:8.2.0
taglibs-standard:1.1.2
jakarta.mail:2.0.1
</pre>

---

<h2>📁 Project Structure</h2>

<pre>
BookStoreManagement
│
├── src/main/java
│   ├── controller
│   ├── dao
│   ├── service
│   ├── entity
│   └── DB
│
├── src/main/webapp
│   ├── admin
│   ├── components
│   ├── css
│   ├── img
│   └── JSP Pages
│
└── pom.xml
</pre>

---

<h2>🗄️ Database Design</h2>

<h3>User Table</h3>

<pre>
id
name
email
phone
password
address
</pre>

<h3>Book Table</h3>

<pre>
bookId
bookName
author
price
category
status
photo
email
</pre>

<h3>Cart Table</h3>

<pre>
cartId
userId
bookId
quantity
totalPrice
</pre>

<h3>Orders Table</h3>

<pre>
orderId
userId
customerName
address
phone
paymentType
totalAmount
</pre>

---

<h2>🔄 Application Workflow</h2>

<pre>
User Registration
        │
        ▼
     Login
        │
        ▼
 Browse Books
        │
        ▼
 Add to Cart
        │
        ▼
   Checkout
        │
        ▼
 Place Order
        │
        ▼
 Order History
</pre>

---

<h2>📸 Screenshots</h2>

<p align="center">
<img src="./screenshots/home-page.png" width="90%">
</p>

<p align="center">
<b>🏠 Home Page</b>
</p>

<br>

<p align="center">
<img src="./screenshots/book-details.png" width="90%">
</p>

<p align="center">
<b>📖 Book Details</b>
</p>

<br>

<p align="center">
<img src="./screenshots/cart-page.png" width="90%">
</p>

<p align="center">
<b>🛒 Shopping Cart</b>
</p>

<br>

<p align="center">
<img src="./screenshots/admin-dashboard.png" width="90%">
</p>

<p align="center">
<b>🛠️ Admin Dashboard</b>
</p>

---

<h2>⚙️ Installation</h2>

<h3>1. Clone Repository</h3>

<pre>
git clone https://github.com/your-username/BookStoreManagement.git
</pre>

<h3>2. Create Database</h3>

<pre>
CREATE DATABASE ebook;
</pre>

<h3>3. Configure Database</h3>

<p>
Update credentials in:
</p>

<pre>
DBConnect.java
</pre>

<h3>4. Build Project</h3>

<pre>
mvn clean install
</pre>

<h3>5. Deploy WAR File</h3>

<pre>
target/EbookMangement.war
</pre>

<h3>6. Start Tomcat</h3>

<pre>
http://localhost:8080/EbookMangement
</pre>

---

<h2>🎯 Future Enhancements</h2>

<ul>
<li>💳 Online Payment Integration</li>
<li>⭐ Book Ratings & Reviews</li>
<li>❤️ Wishlist System</li>
<li>📧 Email Notifications</li>
<li>📄 PDF Invoice Generation</li>
<li>📱 Mobile Responsive Dashboard</li>
<li>🔔 Real-Time Notifications</li>
<li>🚀 Spring Boot Migration</li>
<li>🔐 JWT Authentication</li>
</ul>

---

<h2>📈 Repository Stats</h2>

<p align="center">

<img src="https://github-readme-stats.vercel.app/api?username=jayeshkumardhariyal&show_icons=true" />

<br><br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=jayeshkumardhariyal" />

</p>

---

<h2>🤝 Contributing</h2>

<p>
Contributions are welcome!
Feel free to fork the repository, create a feature branch, and submit a pull request.
</p>

---

<h2>👨‍💻 Author</h2>

<p>
Developed using Java, JSP, Servlets, JDBC, MySQL, Maven, and Apache Tomcat.
</p>

---

<h2>📜 License</h2>

<p>
This project is licensed under the MIT License.
</p>

---

<h2>⭐ Show Your Support</h2>

<p>
If you found this project useful, please consider giving it a ⭐ on GitHub.
</p>

<p align="center">
<b>Happy Coding 🚀</b>
</p>
