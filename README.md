# PlayOS — Playground Management Platform

**A NOVEXA product for the daily operations of indoor play centres.**

PlayOS brings front-desk activity, sales, customer accounts and operational reporting into one workspace. It supports real business operations at one location and is used by six staff members.

## Operational modules

| Module | Workflow |
|---|---|
| Customer registration | Register families and maintain customer records for repeat visits |
| Check-in and session tracking | Start timed sessions, see active visits and monitor time remaining |
| Point of sale | Record retail sales and session payments with supported payment methods |
| Memberships | Manage membership status and track usage |
| Digital wallet | Manage customer wallet credits and payments |
| Packages | Configure time-based play packages and apply them at check-in |
| Pauses and refunds | Pause eligible sessions and process authorized refunds |
| Birthdays and events | Record reservations and coordinate event details |
| CRM | View customer history and follow up on visits and memberships |
| Financial reporting | Review sales breakdowns, payment methods and daily close |
| Staff management | Organize staff access and operational responsibilities |
| Role-based access control | Restrict administrative, financial and operational features by role |

## Technology

The application uses Next.js 14, React 18 and TypeScript. The interface uses Tailwind CSS, Radix UI and Recharts. Supabase provides PostgreSQL, authentication and realtime updates, with row-level security and database functions. The repository also includes a PWA manifest and Electron packaging configuration.

## Architecture

The Next.js operations console uses domain-focused services to connect to Supabase authentication, realtime updates and PostgreSQL. Database functions support multi-step transactional workflows. See the [high-level architecture and system context](docs/architecture.md).

## Project status

PlayOS is the portfolio brand for the operational application. This public repository provides a product overview. The application source code is proprietary. Live operating records and customer data are excluded from the portfolio.

[NOVEXA](https://novexxa.dev)
