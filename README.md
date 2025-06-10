# ERM: Web-Based Form Development Project

This project was built as part of my **Web Based Applications Course (Spring 2025)**. It demonstrates the development of a multi-page web application using ASP.NET Web Forms, C#, Bootstrap, and Microsoft SQL Server.  

## 🚀 Live Demo
Check out the deployed web application here: [**Project Demo**](http://e0750442.elmcsis.com/erm/Registration.aspx) <br/>
Check out the admin dashboard login page here: [**Login Page**](http://e0750442.elmcsis.com/ERM/Login.aspx)

> **⚠️ Note:**  
> This web application was originally connected to a Microsoft SQL Server database hosted by the university. The database has since been deleted following the conclusion of the course, so form submissions may redirect to an error page due to the inactive database connection.

## 📌 Features
- Multi-page ASP.NET Web Forms application with master pages for consistent layout.
- Bootstrap styling for responsive design and enhanced user experience.
- Form validation using C# backend, including both client-side and server-side checks.
- Integration with Microsoft SQL Server via ADO.NET for data storage and management, including full CRUD functionality.
- Secure admin dashboard protected by a login page with username-password authentication and encrypted passwords.
- SMTP integration via SendGrid for sending confirmation emails to users.

## 🛠️ Technologies Used
- **Frontend:** ASP.NET Web Forms, Bootstrap
- **Backend:** C# (ADO.NET)
- **Database:** Microsoft SQL Server
- **Email Service:** SendGrid
- **Authentication:** Encrypted passwords with C# backend decryption

## 🔐 Security
Passwords are stored in the database in encrypted form. During login, they are decrypted and validated on the server side using C# functions to ensure secure access.
