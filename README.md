# PizzaPoint — Restaurant Management System

A Point-of-Sale (POS) system built for pizza/restaurant businesses, developed in **C#** with a **SQL Server** backend. Handles order management, billing, and receipt printing for cashier/counter operations.

## Features

- Cashier/order entry screen for taking customer orders
- Product & menu management (add/edit items, prices)
- Bill generation with print-ready receipt output (PDF)
- Sales tracking and order history
- User/login management for staff access

## Tech Stack

- **Language**: C#
- **Database**: SQL Server (see `PizzaPoint.sql` for schema)
- **IDE/Build**: Visual Studio (`.sln` solution file)

## Getting Started

1. Clone the repository

```
git clone https://github.com/hyder147/POS-of-pizza-restraunat.git
```

2. Open `PizzaPoint.sln` in Visual Studio

3. Set up the database
   - Create a new SQL Server database
   - Run `PizzaPoint.sql` to create the schema and tables
   - Update the connection string in the app's config to point to your database

4. Build and run the solution from Visual Studio

## Sample Output

A sample generated bill (`Bill1.pdf`) is included in this repo, showing the receipt format produced by the system for a small thermal/receipt printer.

## Screenshots

*(Add your own screenshots of the login screen, order entry, product management, and billing views here)*

## Future Improvements

- Migrate to a web-based interface (ASP.NET Core MVC)
- Add role-based access control (admin vs cashier)
- Add inventory tracking tied to sales
- Cloud-hosted database option for multi-branch use
