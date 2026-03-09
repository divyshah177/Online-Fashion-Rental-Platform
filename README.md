# 👗 RentCouture — Online Fashion Rental Platform

> Discover, rent, and enjoy high-end fashion — without the commitment of ownership.

---

## 📌 About the Project

**RentCouture** is a full-stack fashion rental web application where users can browse designer clothing across categories, select rental dates, and checkout securely. The platform handles everything from user authentication to payment processing and order tracking — built end-to-end with PHP and MySQL.

The idea is simple: why buy a designer outfit you'll wear once, when you can rent it?

---

## ✨ Features

- 🔐 **User Authentication** — Secure register & login with encrypted passwords
- 👗 **Product Catalogue** — Browse Women, Men & Kids categories with search and filters
- 🛒 **Cart System** — Add items, manage quantities, view full order summary
- 📅 **Rental Booking** — Select rental start & end dates per order
- 📦 **Order Tracking** — Real-time status updates (Active / Completed / Cancelled / Pending)
- 💳 **Payment Integration** — Razorpay (Card, UPI, NetBanking) + Cash on Delivery
- 🚚 **Shipping Management** — Save and manage multiple delivery addresses
- ⭐ **Feedback & Ratings** — Users can leave ratings and reviews
- 🗄️ **Admin Panel** — Full database visibility and management via phpMyAdmin

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML, CSS, JavaScript |
| Backend | PHP |
| Database | MySQL |
| Local Server | XAMPP |
| Payment Gateway | Razorpay API |

---

## 🗃️ Database Design

Designed and normalized across **7 relational tables** — fully compliant up to **BCNF**.

| Table | Purpose |
|-------|---------|
| `Users` | User profiles and login credentials |
| `Products` | Fashion items with pricing, stock & images |
| `Orders` | Rental orders with dates and status |
| `Payments` | Payment records, methods and status |
| `Shippingaddr` | Delivery addresses linked to users |
| `Feedback` | User ratings and comments |
| `Order_Product` | Many-to-many link between orders and products |

**Normalization:** All tables satisfy 1NF, 2NF, 3NF, and BCNF — no partial or transitive dependencies.

---

## 🔍 SQL Highlights

The project includes **20+ SQL queries** covering:

- Aggregate functions (`COUNT`, `SUM`, `AVG`)
- Nested subqueries
- Multi-table `JOIN` operations
- `GROUP BY`, `ORDER BY`, `LIMIT`
- Pattern matching with `LIKE`
- Date-based filtering with `INTERVAL`

---

## 💡 Key Challenges Solved

- **Real-time stock updates** — availability reflects instantly after a rental is placed
- **Preventing double bookings** — backend logic validates stock before confirming orders
- **Razorpay API integration** — secure end-to-end payment flow with success/failure handling
- **Complex query optimization** — efficient filtering across products, users, and orders
- **Responsive UI/UX** — clean, navigable interface across all device sizes

---

## 📚 What I Learned

- Designing normalized relational databases for real-world e-commerce use cases
- Full-stack development flow — from database schema to frontend UI
- Secure user authentication and password encryption in PHP
- Integrating third-party payment APIs (Razorpay)
- Debugging complex backend-to-database connectivity issues
- Writing efficient SQL — nested queries, joins, aggregates

---

## 📄 Project Report

The full project report is attached in this repository and includes:

- ER Diagram & Relational Schema
- Normalization walkthrough (1NF → BCNF)
- All SQL queries with output screenshots
- Full project demonstration with UI screenshots
- Challenges faced and learnings
