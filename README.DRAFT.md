# databinding

CodeIgniter 3 web app for stadium match ticketing and member sales.

## Features
- Member registration and login
- Match schedules and ticket purchase
- Promotions and discounts
- Member profile management
- Admin dashboard
- Admin modules: teams, stadiums, seat classes, capacity, schedules, users, sales

## Tech stack
- PHP (CodeIgniter 3)
- MySQL/MariaDB
- Bootstrap assets

## Setup
1. Create a MySQL database.
2. Import `etiket.sql`.
3. Update `application/config/database.php` and align the database name (`db_etiket` vs `etiket`).
4. Set `base_url` in `application/config/config.php`.
5. Serve the folder with Apache/Nginx and open `index.php`.

## Notes
- Sample admin accounts exist in `etiket.sql` (table `login`).
