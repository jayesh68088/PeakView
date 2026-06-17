# PeakView

PeakView is a full-stack inventory and sales management project.

## Structure

- `PeakView-Frontend/` - React dashboard for sign in, sign up, inventory, sales, analytics, invoices, and account profile views.
- `PeakView-Backend/` - NestJS microservice backend for auth, users, inventory, sales, payments, notifications, and reservations.

## Frontend

```bash
cd PeakView-Frontend
npm install
npm start
```

## Backend

```bash
cd PeakView-Backend
npm install
docker compose up
```

The backend expects service-specific environment files under `PeakView-Backend/apps/*/.env`. Those files are intentionally ignored and should not be committed.
