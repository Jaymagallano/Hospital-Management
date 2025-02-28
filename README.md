# Hospital Management System

Isang web-based na Hospital Management System gamit ang Laravel framework. Ito ay may layuning gawing mas madali ang pag-manage ng ospital, kabilang ang patient records, appointment scheduling, at billing system.

## Features
- 🏥 **Patient Management** – Pagrehistro at pag-track ng impormasyon ng pasyente.
- 📅 **Appointment Scheduling** – Pag-set at pag-manage ng appointments.
- 💳 **Billing System** – Automated na pag-generate ng medical bills.
- 👩‍⚕️ **Doctor & Staff Management** – Pag-manage ng accounts ng doctors at hospital staff.
- 📊 **Reports & Analytics** – Dashboard para sa monitoring ng hospital operations.

## Requirements
Siguraduhin na naka-install ang mga sumusunod bago simulan ang project:

- PHP >= 8.0
- Composer
- Laravel >= 11
- MySQL
- Node.js & npm (para sa frontend dependencies)

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
Gumawa ng `.env` file at i-configure ang database:
```bash
cp .env.example .env
php artisan key:generate
```
I-update ang database configuration sa `.env` file:
```env
DB_DATABASE=hospital_db
DB_USERNAME=root
DB_PASSWORD=yourpassword
```

### 4. Migrate Database
```bash
php artisan migrate --seed
```

### 5. Run the Application
```bash
php artisan serve
```
Pagkatapos nito, buksan ang browser at pumunta sa `http://127.0.0.1:8000`

## Default Admin Account
- **Email:** admin@hospital.com
- **Password:** password

## Contributing
Kung gusto mong mag-contribute, mag-fork ng repository at gumawa ng pull request.

## License
[MIT License](LICENSE)
