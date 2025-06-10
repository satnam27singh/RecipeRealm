# 🍽️ RecipeRealm – Share and Discover Recipes Online

## 👨‍🍳 Project Overview
**RecipeRealm** is a Java-based dynamic web application designed to create a digital community for food lovers. It allows users to **register, log in, add, view, and share recipes** with the public. Users can also **comment** on recipes shared by others, promoting interaction and discovery. Admins play a crucial role in **moderating content**, ensuring all submissions meet quality standards and community guidelines.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JSP
- **Backend**: Java Servlets, JDBC
- **Database**: MySQL
- **Tools**: Eclipse IDE, Apache Tomcat, GitHub, XAMPP
- **Styling**: Bootstrap (Optional, used for UI improvement)

---

## 📁 Folder Structure

RecipeRealm/
├── WebContent/
│   ├── index.jsp
│   ├── login.jsp
│   ├── register.jsp
│   ├── addRecipe.jsp
│   └── viewRecipe.jsp
├── src/com/reciperealm/
│   ├── LoginServlet.java
│   ├── RegisterServlet.java
│   ├── AddRecipeServlet.java
│   ├── DBUtil.java
│   └── AdminServlet.java
├── WEB-INF/
│   └── web.xml
├── lib/
│   └── mysql-connector.jar


---

## 🧠 How to Run the Project

1. **Clone the repository** from GitHub.
2. **Import** the project into **Eclipse IDE** as a Dynamic Web Project.
3. **Set up MySQL**:
   - Create a new database named `reciperealm`.
   - Run the SQL script located in `/SQL/RecipeRealm_DB_Schema.sql`.
4. **Configure JDBC Driver**:
   - Add the MySQL JDBC connector (`mysql-connector.jar`) to your `/lib` folder.
5. **Deploy to Apache Tomcat**:
   - Add project to Tomcat server via Eclipse.
6. **Start Server** and navigate to:
http://localhost:8080/RecipeRealm
---

## 🔐 User Roles & Permissions

### 👤 Regular User:
- Register & log in securely
- Add new recipes with title, ingredients, steps, and image
- View all recipes
- Comment on others’ recipes

### 🛡️ Admin:
- Approve or reject recipe submissions
- Moderate inappropriate content or comments
- Manage user accounts

---

## 📸 Screenshots

> _(Add these before final submission)_  
- Login Page  
- Recipe Listing Page  
- Add Recipe Page  
- View Full Recipe with Comments  
- Admin Dashboard  

---

## 📦 Key Features

- 📋 **CRUD Functionality** for Recipes (Create, Read, Update, Delete)
- 💬 **Comment System**
- 🔐 **Secure Login & Session Handling**
- 🧹 **Admin Moderation Panel**
- ✅ **Client-side & Server-side Validation**
- 📈 **Database-Driven Design with MySQL**

---

## 💡 Innovations / Highlights

- Reusable `DBUtil.java` class for all DB operations
- Clean and modular servlets for core functionality
- Session-based login system
- Bootstrap-based responsive design (optional)
- Structured code for scalability and maintenance

---

## 📍 Project Link

🔗 GitHub Repository: https://github.com/satnam27singh/RecipeRealm.git

---

## 👨‍🎓 Author

**Satnam Singh**  
Team: *TheCodeOfTheDay*  
Course: B.Tech CSE – Galgotias University

---

## ❓ Need Help Running?

If the server doesn’t start:
- Ensure Tomcat server is running
- Check DB credentials in `DBUtil.java`
- Make sure MySQL service is active

---


