# Study Hut Coaching Center

A website for a coaching center, built with PHP and MySQL. Team project by Rachita Dewanjee and
Jannatul Ferdous.

## Pages
- **Home:** about the center, experienced teachers, projector-based teaching, exam procedure,
  available rooms
- **Sign up:** student registration form (name, roll number, class, phone, email, institute, address)
  saved to MySQL
- **Login**
- **Student profiles:** list of registered students loaded from the database
- **Join** and **Location** pages

## Tech
PHP, MySQL (`mysqli`), HTML, CSS, Bootstrap, JavaScript.

## Run
1. Install XAMPP (or any PHP + MySQL server) and copy this folder into `htdocs`.
2. In phpMyAdmin, create a database named `study_hut` with a `student_profile` table for the
   registration fields.
3. Open `http://localhost/<folder>/index.html` in a browser.
