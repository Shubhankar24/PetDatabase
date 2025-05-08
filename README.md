# 🐾 Pet Management System

This is a simple **CRUD (Create, Read, Update, Delete)** web application developed using **ASP.NET Core MVC** and **Entity Framework Core (Code First)** approach. It allows users to manage a list of pets with details such as name, type, date of birth, owner's name, and email.

---

## 🔧 Technologies Used

- **ASP.NET Core MVC** (.NET 6/7)
- **Entity Framework Core** (Code First)
- **SQL Server** (LocalDB or full version)
- **Bootstrap** (for basic styling)
- **Razor Views**

---

## 🐶 Features

- Add new pets with details
- Edit pet information
- View pet listings
- Delete pet records
- Validation on forms
- Responsive UI (basic layout)

---

## 🚀 Getting Started

### ✅ Prerequisites

Make sure you have the following installed:

- [.NET SDK 6/7](https://dotnet.microsoft.com/en-us/download)
- [Visual Studio 2022+](https://visualstudio.microsoft.com/) (with ASP.NET and web development workload)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) (LocalDB or Express)
- Git (optional)

---

### 📦 How to Run the Project

1. **Clone or Download ZIP**  
   If you haven't already:
   ```bash
   git clone https://github.com/yourusername/PetManagementSystem.git

   
## Or download the ZIP from GitHub and extract it.

- Open the Solution
- Open PetManagementSystem.sln in Visual Studio.

- Configure the Connection String
- Open appsettings.json and update your connection string:
**"ConnectionStrings": {
  "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=PetDb;Trusted_Connection=True;"
}**

## go to tools -> nuget PackageManagerConsole --> then type below command :
- Add-Migration Mig1
- Update-Database


<pre> ```text ### 🐾 PetManagementSystem/ │ ├── Controllers/ │ └── PetsController.cs │ ├── Models/ │ └── Pet.cs │ ├── Views/ │ ├── Pets/ │ │ ├── Index.cshtml │ │ ├── Create.cshtml │ │ ├── Edit.cshtml │ │ └── Delete.cshtml │ ├── Data/ │ └── ApplicationDbContext.cs │ ├── appsettings.json ├── Program.cs └── PetManagementSystem.csproj ``` </pre>

## 📬 Contact
Created by **Shubhankar Gupta**
