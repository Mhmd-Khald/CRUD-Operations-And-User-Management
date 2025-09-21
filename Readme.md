# DemoPL – ASP.NET Core MVC CRUD Application

## 📌 Overview  
**DemoPL** is a **3-layer ASP.NET Core MVC application** built with **Entity Framework Core, Repositories, Unit of Work, and ASP.NET Identity**.  
It demonstrates **full CRUD operations for Employees and Departments**, with authentication and role-based authorization.  

---

## 🚀 Features  
- 👤 **Authentication & Identity**  
  - User registration, login, logout.  
  - Password reset with email + token.  
  - Role-based authorization.  

- 🏢 **Department Management (CRUD)**  
  - Create, Read, Update, Delete departments.  
  - Validation for unique department codes & names.  

- 👨‍💼 **Employee Management (CRUD)**  
  - Create, Read, Update, Delete employees.  
  - Upload employee profile pictures.  
  - Search employees by name.  
  - Assign employees to departments.  

- 🔐 **Role & User Management**  
  - Manage roles.  
  - Assign users to roles.  

- 📊 **Architecture**  
  - Clean 3-layer structure: DAL, BLL, PL.  
  - Repository + Unit of Work patterns.  
  - Strongly typed ViewModels.  

---

## 🛠️ Tech Stack  
- **Framework:** .NET 6 MVC  
- **Database:** SQL Server (EF Core)  
- **Authentication:** ASP.NET Identity + Roles  
- **Architecture:** 3-Layer (DAL, BLL, PL)  
- **Design Patterns:** Repository, Unit of Work, Dependency Injection  

---

## 🌟 Future Enhancements  
- Logging and auditing.  
- Pagination & sorting for employees.  
- Email notifications.  
- API layer for external integration.  

---

## 🤝 Contributing  
Contributions are welcome!  
Please fork and submit a pull request.  

---