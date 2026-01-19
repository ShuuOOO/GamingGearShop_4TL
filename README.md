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

### UI
The user interface is designed to be clean and intuitive, supporting both customer-facing features and admin management functionalities.

<p align="center"> <img src="https://github.com/user-attachments/assets/aba3ed15-f5c2-4fa5-8522-c30462eeefbb" width="360"/> <img src="https://github.com/user-attachments/assets/b841c8f2-f393-4fca-913a-6de0fd720f9d" width="360"/> </p> <p align="center"> <img src="https://github.com/user-attachments/assets/cffdb603-3f12-4f4c-af1e-a4ffec1fd18b" width="360"/> <img src="https://github.com/user-attachments/assets/740f624e-f8d7-4192-84c5-809f8c6d17b7" width="360"/> </p> <p align="center"> <img src="https://github.com/user-attachments/assets/68cbf091-2a03-47f3-9f6d-a6877211b252" width="360"/> <img src="https://github.com/user-attachments/assets/b5f2b1c3-e805-4858-aa67-de87f56bd9e7" width="360"/> </p>

#### Screens: Home · Product Listing · Admin Dashboard · Checkout · VNPay · PayPal

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

## Demo Video: https://youtu.be/xB1nHv52Mfs

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
 └── Database/            # SQL scripts for schema and data initialization 
