# GreenCart

GreenCart is a full-stack e-commerce application for browsing products, managing a cart, placing orders, and handling seller operations from a dedicated dashboard.

## Project Overview

- **Customer experience:** browse product categories, view product details, manage cart, add addresses, and track orders.
- **Seller experience:** seller authentication with a separate seller area for product and order management flows.
- **Backend API:** Express + MongoDB service for authentication and business logic.
- **Frontend app:** React + Vite single-page application with route-based user and seller views.

## Tech Stack

- **Frontend:** React, React Router, Vite, Tailwind CSS
- **Backend:** Node.js, Express, MongoDB (Mongoose), JWT, Cookie-based auth

## Repository Structure

```text
GreenCart/
├── backend/   # Express API and database integration
└── frontend/  # React client application
```

## Getting Started

### Backend

1. Navigate to `/backend`
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables (for example: `MONGODB_URI`, `PORT`, auth-related secrets)
4. Start the server:
   ```bash
   npm start
   ```

### Frontend

1. Navigate to `/frontend`
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start development server:
   ```bash
   npm run dev
   ```
