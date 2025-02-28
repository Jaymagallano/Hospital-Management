# Hospital Management System

A web-based Hospital Management System built using the Laravel framework. It aims to simplify hospital management, including patient records, appointment scheduling, and the billing system.

## Features
- 🏥 **Patient Management** – Registration and tracking of patient information.
- 📅 **Appointment Scheduling** – Setting and managing appointments.
- 👩‍⚕️ **Doctor & Staff Management** – Managing accounts for doctor and staff.
- 📊 **Reports & Analytics** – Dashboard for monitoring patient operations.

## Requirements
Make sure the following are installed before starting the project:

- PHP 
- Composer
- Laravel >= 11
- MySQL
- Node.js & npm (for frontend dependencies)

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/username/hospital-management.git
cd hospital-management
```

### 2. Install dependencies
```bash
composer install
npm install && npm run dev
```

### 3. Setup Environment
Create a `.env` file and configure the database:
```bash
cp .env.example .env
php artisan key:generate
```
Update the database configuration in the `.env` file:
```env
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

### 4. Migrate Database
```bash
php artisan migrate --seed
```

### 5. Run the Application
```bash
php artisan serve
```
After this, open your browser and go to `http://127.0.0.1:8000`

## Default Admin Account
- **Email:** admin@hospital.com
- **Password:** password
