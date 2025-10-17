🐾 Veterinary Automation System (C# WinForms + SQL Server)

Veterinary Automation System is a complete desktop application developed using C# Windows Forms and SQL Server.
It is designed for veterinary clinics to manage animal data, stock operations, debt records, and pregnancy tracking — all within a single, modern, and user-friendly interface.

This system enables veterinarians to efficiently track clients, monitor pregnant animals, manage inventory, and handle customer debts while providing instant email and system notifications for upcoming births and important alerts.

💼 Main Features
🧍‍♂️ Animal Registration & Management

Add and manage animal records with owner details, ear tag (KupeNo), address, and species.

Validates input data (e.g., phone numbers must have 11 digits).

Automatically syncs with other modules (like pregnancy tracking).

📦 Stock Management

Full CRUD operations for products (feed, medicine, etc.).

Calculates profit automatically after each sale: (SalePrice - PurchasePrice) × Quantity.

Includes dynamic filtering by product name or price.

Supports in-place editing in DataGridView with live updates to the database.

💰 Debt Ledger (Veresiye System)

Track customer debts and payments.

Automatic updates to remaining balance after payment.

Search by name or phone number.

Multiple payment methods supported (cash, card, etc.).

🤰 Pregnancy Tracking

Tracks pregnancy records for each animal with due date calculation.

Color-coded alerts:

🟥 Red → Less than 15 days until birth

🟩 Green → More than 15 days

⚪ White → Unknown status

Sends automatic email notifications to the clinic when a birth date is near.

Includes notification sound similar to iPhone alerts.

⚙️ Technical Overview

Language: C#

Framework: Windows Forms (.NET Framework / .NET 6 compatible)

Database: Microsoft SQL Server

Libraries Used:

System.Data.SqlClient (Database operations)

System.Net.Mail (Email service)

System.Media (Notification sound)

NotifyIcon (System tray notifications)

🗃️ Database Structure

Key Tables:

HayvanKayit — animal and owner information

Gebelik — pregnancy records

stok — stock and profit tracking

Islemler — debt ledger transactions

mail — SMTP email configuration

🔔 Notifications & Automation

Automatic email alert when pregnancy due date < 15 days.

System tray popup notifications with sound.

All email credentials are fetched securely from the mail table.

Uses background timer tasks to refresh data every second.

💻 Installation & Setup

Restore veteriner SQL database using included scripts.

Update connectionString in App.config with your server name.

Build and run the project in Visual Studio.

Enjoy the full-featured veterinary automation experience.

🧠 Why This Project

This automation aims to simplify the digital transformation of veterinary clinics, reduce manual paperwork, and provide a centralized management solution that enhances both clinic efficiency and data reliability.

It was developed as a complete, production-ready project for Ondokuz Mayıs University (OMÜ) by Rıdvan Yağlıdere.

🏷️ Keywords

Veterinary Software, Clinic Management, C#, WinForms, SQL Server, Automation, Animal Record, Pregnancy Tracking, Stock Control, Debt Management
