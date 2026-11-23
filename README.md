# Aino POS

Aino POS is a point-of-sale platform for retail stores, built on Laravel and Vue. It brings sales, inventory, customers, purchasing, reporting, and staff operations together in one application.

This is a self-hosted, local installation. There is no cloud service, marketplace, or external account tied to this setup.

## What it provides

- Product, category, unit, tax, and customer management
- POS sales, orders, payments, receipts, refunds, and registers
- Inventory, procurement, and stock history
- Reporting, including sales and stock visibility
- User roles and permissions (admin, store administrator, cashier, customer)
- Barcode support
- Media management and dashboard widgets

## Running locally

Requirements: PHP 8.4, Composer, Node.js, and either MySQL or SQLite.

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan storage:link
npm install
npm run build
```

Configure the database connection in `.env`, then run:

```bash
php artisan migrate
php artisan ns:setup --store_name="My Store" --admin_username="admin" --admin_email="admin@example.com" --admin_password="your-password" --no-interaction
```

Start the server:

```bash
php -S 127.0.0.1:8000 -t public
```

Then open `http://127.0.0.1:8000` in your browser and log in with the admin account created above.

## Sample data

To populate the catalog with sample categories and products for testing:

```bash
php artisan ns:categories:generate --count=10
php artisan ns:products:generate --count=40 --unit-group=<unit_group_id>
```
