# DailyDesk

DailyDesk is a personal productivity web app built using PHP and Bootstrap. It is designed to work offline and provides essential tools to help users organize their daily life efficiently.

---

## Features

- **Dashboard** – Overview of daily tasks and reminders.
- **To-Do List** – Create, edit, and track your tasks.
- **Journal Notes** – Save personal thoughts, reflections, or notes, with the ability to upload images.
- **Budget Tracker** – Log and monitor income and expenses.
- **Profile Settings** – Manage user details, including username, password, and profile picture.

---

## Tech Stack

- **Frontend**: Bootstrap 5, HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL

---

## Installation

1. Clone the Repository:
   ```bash
   git clone https://github.com/yourusername/DailyDesk.git

2. Move it to your local server directory (htdocs in XAMPP).

3. Import the database from /sql/schema.sql into phpMyAdmin and name it daily_desk.

4. Run localhost/your_folder_name/index in your browser.

---

## Database Structure

**Main Tables:**

- **users** – Stores user information (e.g., username, email, password hash, profile picture).
- **tasks** – Stores to-do items with priority and status.
- **journal_entries** – Stores journal notes, tags, and optional images.
- **budget_entries** – Tracks income and expenses with categories and descriptions.

**Relationships:**
- All tables are linked to the users table via user_id with ON DELETE CASCADE to ensure data integrity.

---

## Author

**Rookie Developer Ryan ✨**
