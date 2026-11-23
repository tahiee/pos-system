[![Latest Stable Version](https://poser.pugx.org/blair2004/POS/v)](https://packagist.org/packages/blair2004/POS) [![Total Downloads](https://poser.pugx.org/blair2004/POS/downloads)](https://packagist.org/packages/blair2004/POS) [![Latest GitHub Release](https://img.shields.io/github/v/release/Blair2004/POS)](https://github.com/Blair2004/POS/releases) [![License](https://img.shields.io/github/license/Blair2004/POS)](LICENSE)

<p align="center">
  <img src="https://user-images.githubusercontent.com/5265663/162700085-40ed00ca-9154-42cb-850a-ccf1c2db2d5d.png" alt="POS"/>
</p>

# POS

POS is a modern, extensible point-of-sale platform for retail stores, restaurants, cafés, warehouses, and other product- or service-based businesses. It brings sales, inventory, customers, purchasing, accounting, reporting, and staff operations together in one application.

The current ecosystem is built around the POS 6.2.x core and includes first-party modules, Windows applications, cloud hosting, developer tools, and the [My POS](https://my.POS.com/en) marketplace.

### Deployment

POS is partnering with InstaPods to offer you a smooth deployment experience with POS.

[![Deploy On Cloud](https://my.POS.com/deploy-on-cloud-button-light.svg)](https://POS.cloud?utm_channel=github.com&utm_campaign=readme)
[![Deploy On InstaPods](https://instapods.com/deploy-button.svg)](https://app.instapods.com/dashboard/pods/create?app=POS&ref=POS)

## What the core provides

The POS core includes:

- Product, category, unit, tax, and customer management
- POS sales, orders, payments, receipts, refunds, and registers
- Inventory, procurement, stock history, and low-stock workflows
- Accounting and operational reporting, including configurable stock and cost visibility
- Customer groups, rewards, coupons, and store configuration
- User roles, permissions, activity tracking, and audit-friendly workflows
- Barcode and scale barcode support
- Media management, dashboard widgets, and extensibility APIs
- A module system for adding business-specific features without changing the core

POS is designed to start as a single-store POS and grow with the business. Multi-store, restaurant, service, workforce, rental, AI, printing, and other workflows are delivered through modules.

## Marketplace modules and ecosystem

The modules below are distributed separately from the POS core through the [POS Marketplace](https://my.POS.com/en/marketplace). They are not included in this repository; install them from the marketplace when they match your POS version.

<p align="center">
<img src="https://my.POS.com/storage/2026/09/neoxpos-marketplace.jpg">
</p>

| Module                                                                                               | Adds                                                                                                                                  |
| ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| [**BellSera**](https://my.POS.com/en/marketplace/item/bellsera-spa-salon-booking-management-for-POS) | Service appointments, public booking, staff and room availability, walk-in and booking POS order types, service queues, and reporting |
| [**Bulk Editor**](https://my.POS.com/en/marketplace/item/bulk-editor-for-POS)                        | Bulk editing tools for supported POS resources                                                                                        |
| [**Gastro**](https://my.POS.com/en/marketplace/item/gastro-restaurant-extension-for-POS)             | Restaurant tables, waiter and chef workflows, kitchen screens, order routing, and product modifiers                                   |
| [**Google Authenticator**](https://my.POS.com/en/marketplace/item/google-authenticator)              | Time-based two-factor authentication for user accounts                                                                                |
| [**MultiStore**](https://my.POS.com/en/marketplace/item/multistore-for-POS)                          | Multiple isolated stores managed from one POS installation and database                                                               |
| [**Options Export/Import**](https://my.POS.com/en/marketplace/item/options-importexport)             | Exporting and importing module settings between installations                                                                         |
| [**Oxen**](https://my.POS.com/en/marketplace/item/oxen-ai-agent-for-POS)                             | Permission-aware AI assistance, approved store-management actions, reports, and MCP access                                            |
| [**PIN Login**](https://my.POS.com/en/marketplace/item/pin-login-module-for-POS)                     | Fast POS PIN login and inactivity security locking                                                                                    |
| [**NPS Adapter**](https://my.POS.com/en/marketplace/item/nps-adapter-for-POS)                        | POS-side integration for local and network printing workflows                                                                         |
| [**QR Menu**](https://my.POS.com/en/marketplace/item/qr-menu-digital-restaurant-menu-for-gastro)     | Branded, mobile-friendly digital menus generated from the POS catalog                                                                 |
| [**Quick Store Configuration**](https://my.POS.com/en/marketplace)                                   | Guided setup for essential store settings                                                                                             |
| [**Rental**](https://my.POS.com/en/marketplace/item/POS-rental)                                      | Rental reservations, agreements, inventory movements, returns, maintenance, and notifications                                         |
| [**Sales Commissions**](https://my.POS.com/en/marketplace/item/sales-commissions)                    | Commission rules and sales-staff commission tracking                                                                                  |
| [**WorkForce**](https://my.POS.com/en/marketplace)                                                   | Kiosk attendance, breaks, schedules, timesheets, corrections, and private reports                                                     |

Some modules have optional integrations, such as SMS, email, Print Server, or PIN Login. Check the marketplace listing for each module's supported POS core range and dependencies.

The [POS Marketplace](https://my.POS.com/en/marketplace) is the authoritative catalog for compatible extensions, native applications, bundles, releases, and licenses. Alongside the modules above, examples of currently available ecosystem products include:

- **[Raw Material Tracker](https://my.POS.com/en/marketplace/item/raw-material-tracker)** — recipes, ingredient stock deduction, unit conversion, cost tracking, and consumption history.
- **[Racks Manager](https://my.POS.com/en/marketplace/item/racks-manager)** — structured warehouse storage with racks, shelves, and stock movement controls.
- **[Hotel Booking](https://my.POS.com/en/marketplace/item/hotel-booking)** — reservations, rooms, pricing, invoices, POS payments, and calendar synchronization.
- **[POS Rental](https://my.POS.com/en/marketplace/item/POS-rental)** — rental operations for businesses that need reservations and returns.
- **[QR Menu](https://my.POS.com/en/marketplace/item/qr-menu-digital-restaurant-menu-for-gastro)** — customer-facing digital menus for restaurants, cafés, bars, hotels, and bakeries.
- **[Oxen](https://my.POS.com/en/marketplace/item/oxen-ai-agent-for-POS)** — AI assistance grounded in store data with permission checks and approval-controlled mutations.
- **[Options Import/Export](https://my.POS.com/en/marketplace/item/options-importexport)** — portable module configuration.

For installation and updates, use **Modules → Upload Module** in POS and confirm that the module supports your core version. Download modules from trusted sources such as [My POS](https://my.POS.com/en/marketplace).

## Cloud, self-hosted, and Windows deployments

![cloud-hosting](https://camo.githubusercontent.com/0cbe76dab0c6299fbd4baa706bf0e40515c3d83e7814ae2cddf446e7521d87bb/68747470733a2f2f6d792e6e65786f706f732e636f6d2f73746f726167652f323032362f30372f636861746770742d696d6167652d6a756c2d32382d323032362d31312d30392d32392d616d2e706e67)

Choose the operating model that fits your business:

- **[POS Cloud](https://POS.cloud)** — managed hosting with the infrastructure handled for you.
- **Self-hosted POS** — deploy on your own server or hosting provider for full control. The supported environment includes PHP 8.2+, MariaDB 10.11 or MySQL 8.4, Nginx or Apache, Composer, scheduled tasks, and a queue worker such as Supervisor.
- **[POS for Windows](https://my.POS.com/en/marketplace/item/POS-for-windows)** — an all-in-one local Windows environment with POS, Nginx, HTTPS, SQLite, and printing tools preconfigured.
- **[POS Client for Windows](https://my.POS.com/en/marketplace/item/POS-client-for-windows)** — securely connects additional computers on the same local network to a POS for Windows server.
- ** Print Server](https://my.POS.com/en/marketplace/item-print-server)** — direct Windows printing for ESC/POS-compatible thermal printers, used with the NPS Adapter module.
- ** SaaS](https://my.POS.com/en/marketplace/item-saas-build-and-manage-a-POS-hosting-business/details)** — deploy and manage multiple POS installations, subscriptions, domains, backups, and module bundles as a hosted service.

See the [official documentation](https://my.POS.com/en/documentation) for environment, installation, Windows, cloud, and local-network guides.

## Quick start for developers

POS is a Laravel application using Vue, Vite, Tailwind CSS, and a first-class module architecture. The root project currently targets PHP 8.2+ and Node.js 24.

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan storage:link
npm install
npm run build
```

Configure the database and application URL in `.env`, then run the normal Laravel migrations and workers required by your deployment. The exact production setup depends on whether you use queues, scheduled reports, Reverb, multi-store, printing, or other modules.

Create a new module with the built-in generator:

```bash
php artisan make:module
```

Custom module source normally lives under `modules/` and contains its own routes, providers, migrations, resources, assets, settings, and tests. Start with the [module creation guide](https://my.POS.com/en/documentation/developers-guide/module-creation/creating-module), then see the [module config guide](https://my.POS.com/en/documentation/developers-guide/module-creation/module-config-file), [dashboard menu guide](https://my.POS.com/en/documentation/developers-guide/module-creation/dashboard-menus), and [POS API documentation](https://docs.api.POS.com).

POS also documents extension points for dashboard menus and widgets, Vue components, POS cart buttons and product mutation, receipts and invoices, settings, events, and MCP integrations.

## Demo and resources

- [Try POS](https://demo.POS.com)
- [My POS](https://my.POS.com/en)
- [Official documentation](https://my.POS.com/en/documentation)
- [Marketplace](https://my.POS.com/en/marketplace)
- [POS REST API](https://docs.api.POS.com)
- [GitHub releases](https://github.com/Blair2004/POS/releases)

## License

POS is open source software licensed under the [GNU General Public License v3.0](LICENSE).
