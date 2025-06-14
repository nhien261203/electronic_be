# Nexus Project

This project consists of:

- **Backend**: Laravel (`nexus-be`) – serves APIs and handles business logic.
- **Frontend**: ReactJS with Vite and TailwindCSS (`nexus-fe`) – consumes APIs and renders UI.

---

## 📦 Backend – Laravel (`nexus-be`)

### ✅ Yêu cầu:
- PHP >= 8.1
- Composer
- MySQL or MariaDB

### 🔧 Cài đặt:

```bash
cd nexus-be
cp .env.example .env
composer install
php artisan key:generate
php artisan migrate
php artisan serve
