# 🎮 GAMEZONE - Digital Game Store (ASP.NET Core MVC)

![.NET](https://img.shields.io/badge/.NET-8.0-blue)
![Architecture](https://img.shields.io/badge/Architecture-Layered-green)
![Database](https://img.shields.io/badge/Database-SQL%20Server-orange)
![ORM](https://img.shields.io/badge/ORM-Entity%20Framework%20Core-purple)

## 📌 Overview

GameZone is a digital game store web application built using **ASP.NET Core MVC (.NET 8)**.  
The system allows managing and displaying games with full CRUD operations using **Entity Framework Core (Code First approach)**.

This project demonstrates understanding of:
- MVC Architecture
- Layered Architecture
- Entity Framework Core
- Database Design
- CRUD Operations

---

## 🚀 Features

- ➕ Add new games
- ✏️ Update existing games
- ❌ Delete games
- 📋 View all available games
- 🔍 View game details
- 🗄 Database integration using EF Core (Code First)
- 🧱 Layered project structure

---

## 🏗 Architecture

The project follows a **Layered Architecture**:

- **Presentation Layer (MVC)**
- **Business Logic Layer**
- **Data Access Layer**
- **Models**

This separation improves maintainability, readability, and scalability.

---

## 🛠 Technologies Used

- ASP.NET Core MVC (.NET 8)
- Entity Framework Core
- SQL Server
- Code First Approach
- LINQ
- Razor Views

---

## 🗄 Database

The project uses **Entity Framework Core (Code First)**.

To apply migrations:

```bash
Add-Migration InitialCreate
Update-Database