# 🎓 School Management System

<div align="center">

![School Management System](https://img.shields.io/badge/School-Management%20System-2563EB?style=for-the-badge&logo=graduation-cap&logoColor=white)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![ASP.NET](https://img.shields.io/badge/ASP.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/en-us/apps/aspnet)
[![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)](https://learn.microsoft.com/en-us/dotnet/csharp/)
[![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)](https://www.microsoft.com/en-us/sql-server)

A comprehensive web application for managing school operations — students, staff, attendance, fees, results, and announcements.

</div>

---

A comprehensive, robust, and user-friendly School Management System built using **ASP.NET (C#)** and **Microsoft SQL Server**. This system is designed to streamline administrative tasks, manage student and staff records, track attendance, and handle fee processing efficiently.

---

## 🚀 Features

### 🔐 Multi-Role Authentication
- **Admin**: Full control over the system, including staff and student management.
- **Staff**: Access to student records, attendance tracking, and result management.
- **Student**: View personal profile, results, and fee status.

### 📋 Core Modules
- **Student Management**: Comprehensive system to register, update, and manage student information.
- **Staff Management**: Efficient handling of staff records and roles.
- **Attendance Management**: Digital tracking of daily attendance for both students and staff.
- **Fee Management**: Streamlined processing and tracking of student fees.
- **Result Management**: Tools to record and display academic performance.
- **Notification System**: Built-in system for broadcasting important announcements.
- **User Profiles**: Personalized dashboards for all user types.

---

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap
- **Backend**: ASP.NET Web Forms (C#)
- **Framework**: .NET Framework 4.5.2
- **Database**: Microsoft SQL Server
- **IDE**: Visual Studio

---

## 📁 Project Structure

```text
├── School Management/             # Main Application Folder
│   ├── CS Files/                  # Backend Logic (Business Logic)
│   ├── Database/                  # SQL Server Database Scripts & Backups
│   ├── css/                       # Custom Stylesheets
│   ├── js/                        # JavaScript Files
│   ├── fonts/                     # Typography Assets
│   ├── images/                    # UI Graphics & Assets
│   ├── MasterPage.master          # Consistent Layout Template
│   ├── Web.config                 # Application Configuration & DB Connection
│   └── *.aspx                     # Application Pages
├── Project Reports/               # Documentation & Certificates
└── README.md                      # Project Overview
```

---

## ⚙️ Setup & Installation

### 1. Prerequisites
- Visual Studio (2015 or later recommended)
- Microsoft SQL Server Management Studio (SSMS)
- .NET Framework 4.5.2

### 2. Database Setup
1.  Open **SQL Server Management Studio**.
   
2.  Run the script located at `/School Management/Database/MainSchoolDB.sql` to create the database and tables.

3.   Alternatively, restore the database using the `.bak` file provided in the same directory.

### 3. Application Configuration
1.  Open the solution file `School Management.sln` in Visual Studio.

2.  Open `Web.config` and update the `connectionString` to match your local SQL Server instance:

    ```xml
    <connectionStrings>
        <add name="conn" connectionString="Data Source=YOUR_SERVER_NAME;Initial Catalog=MainSchoolDB;Integrated Security=True" />
    </connectionStrings>
    ```

### 4. Running the Project
1.  Press `F5` or click **Start** in Visual Studio to launch the application.

2.  The application will open in your default web browser (usually at `localhost:[port]/loginPage.aspx`).

---

## 📸 Screenshots

> Add your screenshots inside an `School Management/Screen Images/` folder and update the paths below.

<table>
  <tr>
    <th colspan="3">ADMIN</th>
  </tr>
  <tr>
    <th>Dashboard</th>
    <th>Student</th>
    <th>Staff</th>
  </tr>
  <tr>
    <td><img src="School Management/Screen Images/Admin/DashboardOne.png" alt="dashboard"></td>
    <td><img src="School Management/Screen Images/Admin/Student.png" alt="student"></td>
    <td><img src="School Management/Screen Images/Admin/Staff.png" alt="results"></td>
  </tr>
  <tr>
    <th>Fees</th>
    <th>Attendance</th>
    <th>Restore</th>
  </tr>
  <tr>  
    <td><img src="School Management/Screen Images/Admin/Fees.png" alt="fees"></td>
    <td><img src="School Management/Screen Images/Admin/Attendance.png" alt="attendance"></td>
    <td><img src="School Management/Screen Images/Admin/Bin.png" alt="restore"></td>
  </tr>
</table>

<table>
  <tr>
    <th colspan="3">STAFF</th>
  </tr>
  <tr>
    <th>Dashboard</th>
    <th>Attendance</th>
    <th>Student</th>
  </tr>
  <tr>
    <td><img src="School Management/Screen Images/Staff/Dashboard.png" alt="dashboard"></td>
    <td><img src="School Management/Screen Images/Staff/AttendanceView.png" alt="attendance-view"></td>
    <td><img src="School Management/Screen Images/Staff/StudentMenu.png" alt="student"></td>
  </tr>
</table>


<table>
  <tr>
    <th colspan="3">STUDENT</th>
  </tr>
  <tr>
    <th>Dashboard</th>
    <th>Fees Details</th>
    <th>Profile</th>
  </tr>
  <tr>
    <td><img src="School Management/Screen Images/Student/Dashboard.png" alt="dashboard"></td>
    <td><img src="School Management/Screen Images/Student/FeesViewDetails.png" alt="fees-details"></td>
    <td><img src="School Management/Screen Images/Student/Result.png" alt="result"></td>
  </tr>
</table>

---

## 🤝 Contributing

Contributions are welcome! Follow these steps:

1. **Fork** the repository

2. **Create** a feature branch

   ```bash
   git checkout -b feature/your-feature-name
   ```
   
3. **Commit** your changes
   
   ```bash
   git commit -m "Add: your feature description"
   ```
   
4. **Push** to the branch

   ```bash
   git push origin feature/your-feature-name
   ```
   
5. **Open a Pull Request** and describe what you've added or fixed

---

## 📄 License
This project is for educational purposes.

---

## 📬 Contact

Have questions, found a bug, or want to contribute? Feel free to reach out!

<div align="center">

### Parth Dhaduk

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ParthDhaduk)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ps359511@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/patelparth2456)

</div>

---

<div align="center">

Made with ❤️ by **Parth Dhaduk**
⭐ If you found this project helpful, please give it a star!

</div>
