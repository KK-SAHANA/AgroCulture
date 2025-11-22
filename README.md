🌾 AgroCulture – PHP & SQL Based Farming Platform

AgroCulture is a lightweight web application built using PHP, MySQL, CSS, and JavaScript to support farmers and consumers through an online agricultural marketplace.
Farmers can upload products, buyers can browse and purchase, and the system helps streamline agricultural commerce.

📌 Features
👨‍🌾 Farmer Features

Upload agricultural products

Edit/View profile

Manage uploaded items

View product reviews

🛒 Buyer Features

Browse available crops/products

Add items to cart

Buy products

Leave reviews and feedback

📰 Blog Module

Farmers/Users can write blog posts

Read and view community blogs

🔐 Login System

Secure login and signup using PHP sessions

User-specific dashboards

🛠️ Tech Stack
Frontend

HTML

CSS

JavaScript

Bootstrap

Backend

PHP (Core PHP, no framework)

Database

MySQL

agroculture.sql is included for importing the database.

📂 Project Structure
AgroCulture/
│── Blog/
│── ImagesAg/
│── Login/
│── Profile/
│── bootstrap/
│── css/
│── fonts/
│── images/
│── js/
│── agroculture.sql
│── db.php
│── index.php
│── menu.php
│── market.php
│── myCart.php
│── review.php
│── uploadProduct.php
│── README.md

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/KK-SAHANA/AgroCulture.git
cd AgroCulture

2️⃣ Import the database

Open phpMyAdmin

Create a database (example: agroculture)

Click Import

Select agroculture.sql

Click Go

3️⃣ Configure database connection

Open db.php and edit your MySQL credentials:

$servername = "localhost";
$username = "root";
$password = "";     
$dbname = "agroculture";
$conn = mysqli_connect($servername, $username, $password, $dbname);

4️⃣ Run the project

Place the project in your server directory:

For XAMPP:

C:\xampp\htdocs\AgroCulture


Then start:

Apache

MySQL

Open in browser:

http://localhost/AgroCulture
