# PocketTanks-Java-Release

Pocket Tanks Java Project – Final Version:

A multiplayer artillery battle game inspired by the classic Pocket Tanks, built using Java Applet, JSP & Servlets, and MySQL. Players can register, log in, and engage in strategic turn-based tank battles where accuracy and terrain destruction earn points.

🎮 Features:
User Registration & Login – Players can create accounts and log in to play.
Multiplayer Gameplay – Turn-based shooting with realistic projectile physics.
Scoring System – Points awarded based on damage to opponents and terrain.
Admin Module – Manage player accounts (future: blocking/banning).
Persistent Data – Player stats and game results stored in MySQL.

🛠 Tech Stack:
Frontend: Java Applet, HTML Forms
Backend: JSP, Servlets
Database: MySQL
IDE: Eclipse Helios/Europa


📂 Project Structure:

PocketTanks/
│
├── src/                # Java source code (Applet, Servlets, Game Logic)
├── WebContent/         # JSP pages, HTML forms
├── assets/             # Images, sound files
├── sql/                # Database schema & seed data
└── README.md           # Project documentation


🚀 How to Run:

Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/pocket-tanks-java-final.git
cd pocket-tanks-java-final
Set Up Database

Import the .sql file from the sql/ folder into MySQL.

Update database credentials in the config file (dbConfig.java or similar).
Run on Eclipse
Open the project in Eclipse Helios/Europa.
Set up Apache Tomcat server in Eclipse.
Deploy and run the app.
