# SQL Database Project - Game Application Provider

This repository contains a full SQL database project simulating a digital game application provider (like Steam). The project was developed for academic purposes but is fully functional and professionally structured.

## 📂 Contents

- `Overall Export.sql`: Full database export (schema + data + relationships)
- [More files coming soon: screenshots, queries, and table exports]

## 🔧 Database Overview

- 6 relational tables: `users`, `games`, `purchases`, `reviews`, `friends`, `wishlists`
- Foreign key relationships (including a self-join on `friends`)
- Sample data inserted for realistic simulation
- Designed and tested in MySQL Workbench 8.0

## 📜 Usage

To recreate this database:
1. Open MySQL Workbench
2. Create a new schema (or use the default)
3. Load `Overall Export.sql`
4. Run the script to build and populate the database

## ✅ Features

- Data integrity with primary and foreign keys
- Real-world relational modeling
- Sample queries include: joins, counts, and filtering
