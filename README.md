# lib-management
A Java-based Library Management System with a Swing GUI, designed to help users manage library resources efficiently. This application allows students to select their semester and branch, then displays the corresponding courses.


📚 Library Management System
A Java-based Library Management System with a Swing GUI, designed to help users manage library resources efficiently. This application allows students to select their semester and branch, then displays the corresponding courses.

🚀 Features
📌 User-friendly GUI built with Java Swing

📖 Course Selection based on Semester & Branch

🔍 Book Search & Management

📦 Preloaded Book Database using SQL

🔐 User Authentication (Future Enhancement)

🗄️ Database Integration with MySQL

🛠️ Tech Stack
Java (Core Logic)

Swing (GUI)

MySQL (Database)

📂 Project Structure

📁 src  
 ┣ 📜 Main.java  // Entry point  
   ┣ 📜 LibraryGUI  // Swing-based UI  
   ┣ 📜 CourseSelection  // Logic for semester & branch  
   ┣ 📜 DatabaseManager  // Handles DB operations  
   ┗ 📜 Utils // Helper functions  

📁 database    
 ┗ 📜 library_data.sql  // Preloaded book records   

🔧 Setup & Installation
Clone this repo:
```
git clone https://github.com/your-username/library-management-system.git
cd library-management-system
```
Import the library_data.sql into MySQL

Update database credentials in DatabaseManager.java

Open in IntelliJ IDEA / Eclipse

Run Main.java to launch the app

🎯 Roadmap
✅ Basic Course Selection

✅ Database Integration

⏳ Book Issue/Return System

⏳ Authentication (Librarian & Students)

🤝 Contributing
Feel free to fork, create pull requests, or open issues to improve this project!
