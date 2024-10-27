# RetroFilm
RetroFilm is a discovery and review platform that allows moviegoers to get detailed information about their favorite movies.

## Features
- **Movie Search and Review:** View movies with information such as release date, IMDb score, director, leading actors, movie duration, category, trailer and watch links.
- **Extensive Content:** A large movie archive consisting of classics, cult productions and innovative works.
- **Dynamic Movie Pages:** Detail pages automatically created for each movie based on data entered by administrators.
- **Message Management:** Admin users can view and delete messages received via the contact page.

## Installation Guide

XAMPP or an alternative development environment that supports PHP/MySQL is required to run this project on your local server.

### 1. Required Software
- [Download XAMPP](https://www.apachefriends.org/index.html) and install it on your computer. - Start XAMPP and run Apache and MySQL services.

### 2. Import database
- Go to **http://localhost/phpmyadmin** from your browser.

- Click on **Import** tab from the top menu.

- Click on “Choose File” button, select **RetroFilm.sql** file and click on “Go” button.

- This will automatically create database named `retrofilm` and add all tables and content.

### 3. Copy Site Files to Htdocs Folder
- Copy “RetroFilm” folder to **C:\xampp\htdocs** directory.

### 4. Run the site
- Open the project by going to **http://localhost/RetroFilm/index.php** from your browser.

### 5. Access Admin Panel
- You can manage messages sent via the contact page by logging in to Admin Panel. - **Username:** `admin`

- **Password:** `admin`

## Developer Notes
This project was developed to provide a user-friendly platform for moviegoers to discover their favorite movies. Administrator privileges are designed to facilitate content management of the platform.

---

**Note:** If you are using a different hosting environment, you can update the database connection settings from the **db.php** file.