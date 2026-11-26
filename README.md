# Rocket Catalog

Digital catalog for a sublimation and custom-printing business: mugs,
t-shirts, mousepads, and personalized items for businesses. Customers can
browse products by category, see promotions, and place orders via WhatsApp.

## Tech Stack

- **Frontend:** React + Vite
- **Backend:** Node.js + Express
- **Database:** PostgreSQL with Prisma ORM
- **Local infrastructure:** Docker

## Project Structure

- `backend/`: API and database schema
- `frontend/`: catalog user interface
- `docker-compose.yml`: PostgreSQL database for local development

## Getting Started

1. Copy `.env.example` to `.env` and fill in the values.
2. Start the database: `docker compose up -d`

## Status

Work in progress. Database schema designed; next step: set up Prisma and
the API.
