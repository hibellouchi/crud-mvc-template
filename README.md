# crud-mvc-template

Simple PHP CRUD template using MVC architecture.

_Just for educational purpuses_.

# Techs

- PHP 7
- MariaDB
- Apache2
- phpMyAdmin
- Bootstrap 4
- JQuery 3.4

# Installation

- Set up Apache
  - Opt1: Create a <a href="https://httpd.apache.org/docs/2.4/vhosts/examples.html">virtualhost</a> with its own <code>documentroot "/srv/http/crud-mvc-template"</code>
  - Opt2: Edit httpd.conf file and set main _DocumentRoot_ directive:
    <code>DocumentRoot "/srv/http/crud-mvc-template"</code> for Linux.
    <code>DocumentRoot "C:/xampp/htdocs/crud-mvc-template"</code> for XAMPP on Windows.
  - Set _AllowOverride_ to _AllowOverride All_
- Edit DB credentials in /app/config.php
- Import database in /assets/crud.example.sql
#   E l e c t r o n i q u e - m v c  
 