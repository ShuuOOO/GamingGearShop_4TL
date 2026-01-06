# GamingGearShop_4TL – Gaming Gear E-Commerce Website

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![ASP.NET MVC](https://img.shields.io/badge/ASP.NET_MVC-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white)

A full-stack e-commerce web application specialized in selling gaming accessories. This project focuses on **backend business logic**, **database integration**, and the **MVC (Model-View-Controller)** architectural pattern.

---

## Features

### User Side
- **Authentication:** Secure user registration and login.
- **Product Discovery:** Browse products categorized by type (Mouse, Keyboard, Headset, etc.).
- **Product Details:** View technical specifications, descriptions, and pricing.
- **Shopping Cart:** Add/remove items using **Session-based** management.
- **Checkout:** Streamlined order placement process.

### Admin Side
- **Product Management:** Full CRUD (Create, Read, Update, Delete) operations for gaming gear.
- **Category Management:** Organize the store structure.
- **Order Management:** View and track customer orders.
- **Access Control:** Role-based authorization to protect sensitive areas.

---

## Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | HTML5, CSS3, SCSS, JavaScript |
| **Backend** | C# (ASP.NET MVC) |
| **Database** | Microsoft SQL Server |
| **Architecture** | MVC Pattern |
| **IDEs** | Visual Studio 2019/2022, SSMS |

---

## Project Structure

```text
GamingGearShop_4TL/
 ├── GEAR_SHOP-main/
 │    ├── Controllers/    # Handling HTTP requests & business logic
 │    ├── Models/         # Data structures & Entity Framework mapping
 │    ├── Views/          # Razor-based UI templates
 │    ├── wwwroot/        # Static files (CSS, JS, Images)
 │    ├── appsettings.json# Environment & Connection configurations
 │    └── Program.cs      # Application entry point
 ├── Database/            # SQL scripts for schema and data initialization
 └── README.md
