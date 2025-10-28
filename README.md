🎉 Event Management System
📌 Overview

The Event Management System is a web-based application built using PHP and MySQL that allows users to create, manage, and register for events. It provides an easy-to-use interface for both event organizers and participants, streamlining the entire event process — from event creation to participant registration and feedback collection.

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: PHP (Core PHP, no frameworks)

Database: MySQL

Server: XAMPP / WAMP / LAMP

🎯 Features
👨‍💼 Admin Panel

Login/Logout authentication

Create, update, and delete events

Manage user registrations

View all upcoming and past events

Manage event categories

👥 User Panel

User registration and login

Browse all available events

View event details (date, venue, description, etc.)

Register for events

Cancel registration

Give feedback or ratings after the event




⚙️ Installation & Setup

Download or clone the repository:

git clone https://github.com/yourusername/event-management-system.git


Move the project to your web server directory:

For XAMPP: C:\xampp\htdocs\event-management-system

For WAMP: C:\wamp\www\event-management-system

Create a MySQL database:

Open phpMyAdmin

Create a database named event_db

Import the provided SQL file: event_db.sql

Configure database connection:
Open the config.php file and update credentials:

<?php
$conn = mysqli_connect("localhost", "root", "", "event_db");
if (!$conn) {
    die("Connection failed: " . mysqli_connect_error());
}
?>


Run the project:
Open your browser and go to

http://localhost/event-management-system/
