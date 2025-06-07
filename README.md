Gym Management System 💪

Welcome to the Gym Management System! 🚀 Built with Laravel, this app simplifies gym operations by managing members, trainers, memberships, and more in one place! 😎
Features ✨

🧑‍🤝‍🧑 Member Management: Add, edit, or view member details and attendance.
🏋️ Trainer Management: Handle trainer schedules and assignments.
💸 Membership & Payments: Track plans, renewals, and payments.
📊 Dashboard: View stats like membership trends and revenue.
🔒 Secure Login: Role-based access for admins, trainers, and members.

Tech Stack 🛠️

Frontend: HTML, CSS, JavaScript, Bootstrap
Backend: Laravel (PHP)
Database: MySQL

Get Started in 5 Minutes! ⏱️
Prerequisites 📋

PHP ≥ 7.4
Composer
MySQL
Git
A code editor (like VSCode)
XAMPP/WAMP for local server setup

Setup Steps 🚀

Clone the Repo:
git clone https://github.com/NischalShrestha07/Gym-Management-System.git
cd Gym-Management-System


Install Dependencies:
composer install


Set Up Database:

Create a MySQL database (e.g., gym_db).
Import database.sql (if provided) or run migrations:php artisan migrate




Configure Environment:

Copy .env.example to .env and update with your database details:cp .env.example .env

Example .env:DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=gym_db
DB_USERNAME=your_user
DB_PASSWORD=your_password




Generate App Key & Run the App:
php artisan key:generate
php artisan serve


Open http://localhost:8000 in your browser! 🌐



How to Use It? 🖱️

Admins: Log in (e.g., admin/admin123) to manage members, trainers, and more from the dashboard.
Members: View profiles, attendance, or workout plans.
Trainers: Check schedules and update member plans.

Want to Contribute? 🤝

Fork the repo 🍴.
Create a branch: git checkout -b my-cool-feature.
Commit changes: git commit -m "Added cool feature".
Push: git push origin my-cool-feature.
Open a pull request! 🎉

License 📜
MIT License. See LICENSE for details.
Contact 📬

Author: Nischal Shrestha
GitHub: NischalShrestha07

Happy gym managing! 🏋️‍♀️
