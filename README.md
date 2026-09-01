<div align="center">

# 🛒 BuyTrust

### A Secure & Trustworthy E-Commerce Platform

[![Report](https://img.shields.io/badge/📄_Project_Report-Docs/BuyTrust--Report.docx-blue?style=for-the-badge)](https://github.com/mhtamim136/BuyTrust/blob/main/Docs/BuyTrust-%20Report.docx)
[![UI Designs](https://img.shields.io/badge/🎨_UI_Designs-16_Screens-orange?style=for-the-badge)](https://github.com/mhtamim136/BuyTrust/tree/main/UI)
[![Diagrams](https://img.shields.io/badge/📊_Diagrams-3_Types-green?style=for-the-badge)](https://github.com/mhtamim136/BuyTrust/tree/main/Diagrams)

</div>

---

## 📌 Overview

**BuyTrust** is a fully conceptualized and designed e-commerce platform built to provide a **safe, trustworthy, and seamless** online shopping experience. The platform bridges the gap between buyers and sellers by offering transparent product listings, real-time communication, secure order management, and a robust dispute resolution system.

This repository contains the complete **project report**, **system design diagrams**, and **high-fidelity UI mockups** for all major platform flows.

---

## 📋 Table of Contents

- [Features](#-features)
- [UI Screens](#-ui-screens)
- [System Diagrams](#-system-diagrams)
- [Repository Structure](#-repository-structure)
- [Documentation](#-documentation)
- [Author](#-author)

---

## ✨ Features

### 👤 User Management
- **Sign Up & Login** — Secure account registration and authentication
- **User Profiles** — Manage personal information and preferences
- **Admin User Control** — Admin panel to manage and list all users

### 🛍️ Product Management
- **Home Page / Product Catalog** — Browse all listed products
- **Product Details Page** — View full product info, images, and seller details
- **Add Product** — Sellers can list new products with images and pricing
- **Offered Products** — Dedicated section for discounts and special deals

### 🛒 Shopping & Checkout
- **Cart Page** — Add, update, and review cart items
- **Checkout Page** — Complete purchase with shipping and payment info
- **Order Completion** — Post-purchase confirmation screen

### 📦 Order Management
- **My Orders** — Buyers can view all past and current orders
- **Order List Page** — Seller/Admin view of all incoming orders
- **Delivery Tracking** — Real-time delivery status monitoring

### 💬 Communication & Trust
- **ChatBox** — Direct real-time messaging between buyer and seller
- **Dispute Page** — Built-in dispute resolution mechanism for order issues

---

## 🎨 UI Screens

### Authentication
| Login | Sign Up |
|-------|---------|
| ![Login Page](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/UI/Login%20Page.png) | ![SignUp Page](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/UI/SignUp%20Page.png) |

---

### Product Browsing
| Home Page | Product Details | Offered Products |
|-----------|----------------|-----------------|
| ![Home Page](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/UI/Home%20Page.png) | ![Product Details](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/UI/Product%20Details.png) | ![Offered Products](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/UI/Offered%20Products.png) |

---

### Shopping Flow
| Cart | Checkout | Order Completed |
|------|----------|-----------------|
| ![Cart Page](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/UI/Cart%20Page.png) | ![Checkout Page](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/UI/Checkout%20Page.png) | ![Order Completed](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/UI/Order%20Completed.png) |

---

### Order & Delivery Management
| My Orders | Order List | Delivery Tracking |
|-----------|-----------|-------------------|
| ![My Order](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/UI/My%20Order.png) | ![Order List Page](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/UI/Order%20List%20Page.png) | ![Delivery](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/UI/Delivery.png) |

---

### Seller & Admin
| Add Product | Users List |
|-------------|-----------|
| ![Add Product](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/UI/Add%20Product.png) | ![Users List Page](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/UI/Users%20List%20Page.png) |

---

### Communication & Support
| ChatBox | Dispute Resolution |
|---------|--------------------|
| ![ChatBox](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/UI/ChatBox.png) | ![Dispute Page](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/UI/Dispute%20Page.png) |

---

## 📊 System Diagrams

### Use Case Diagram
> Illustrates the interactions between system actors (Buyer, Seller, Admin, Delivery Agent) and platform features.

![Use Case Diagram](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/Diagrams/Use%20Case%20Diagram.drawio.png)

---

### Activity Diagram
> Shows the flow of activities from product browsing through checkout and delivery.

![Activity Diagram](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/Diagrams/Activity%20Diagram.png)

---

### Sequence Diagram
> Demonstrates the step-by-step message flow between system components for key operations.

![Sequence Diagram](https://raw.githubusercontent.com/mhtamim136/BuyTrust/main/Diagrams/Sequence%20Diagram.png)

> 📁 Editable `.drawio` source files are also available in the [`Diagrams/`](https://github.com/mhtamim136/BuyTrust/tree/main/Diagrams) folder.

---

## 📁 Repository Structure

```
BuyTrust/
├── Diagrams/                          # System design diagrams
│   ├── Activity Diagram.drawio        # Editable activity diagram
│   ├── Activity Diagram.png           # Exported activity diagram
│   ├── Sequence Diagram.drawio        # Editable sequence diagram
│   ├── Sequence Diagram.png           # Exported sequence diagram
│   ├── Use Case Diagram.drawio        # Editable use case diagram
│   └── Use Case Diagram.drawio.png    # Exported use case diagram
│
├── Docs/
│   └── BuyTrust- Report.docx          # Full project report
│
├── UI/                                # High-fidelity UI mockups (Figma exports)
│   ├── Home Page.png
│   ├── Login Page.png
│   ├── SignUp Page.png
│   ├── Product Details.png
│   ├── Add Product.png
│   ├── Offered Products.png
│   ├── Cart Page.png
│   ├── Checkout Page.png
│   ├── Order Completed.png
│   ├── My Order.png
│   ├── Order List Page.png
│   ├── Delivery.png
│   ├── ChatBox.png
│   ├── Dispute Page.png
│   └── Users List Page.png
│
└── README.md
```

---

## 📄 Documentation

The complete **project report** is available in the [`Docs/`](https://github.com/mhtamim136/BuyTrust/tree/main/Docs) folder. It covers:

- Project objectives and scope
- Functional & non-functional requirements
- System architecture and design decisions
- Use case, activity, and sequence diagram explanations
- UI/UX design rationale
- Future enhancement roadmap

📥 [**Download Full Report**](https://github.com/mhtamim136/BuyTrust/raw/main/Docs/BuyTrust-%20Report.docx)

---

## 👨‍💻 Author

<div align="center">

### Md. Hasibul Tamim

*Software Engineering Student & Full-Stack Developer*

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-mhtamim136.github.io-blue?style=for-the-badge)](https://mhtamim136.github.io)
[![GitHub](https://img.shields.io/badge/GitHub-mhtamim136-181717?style=for-the-badge&logo=github)](https://github.com/mhtamim136)

> 💬 Feel free to reach out via my portfolio website for collaboration, feedback, or any inquiries!

</div>

---

<div align="center">

⭐ **If you found this project helpful, please give it a star!** ⭐

</div>
