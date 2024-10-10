# Backend Deployment Starter Project

This repository contains starter code for the Back-End Deployment module. It demonstrates how to deploy a back-end server using databases and migrations.

## Features
- Server setup with database connection
- Knex migrations and seed files for database management

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Thinkful-Ed/starter-backend-deployment-render.git
   ```
2. Copy the environment variables:
   ```bash
   cp .env.sample .env
   ```
3. Update the `.env` file with your database connection URL.
4. Install dependencies:
   ```bash
   npm install
   ```
5. Run the migrations:
   ```bash
   npx knex migrate:latest
   ```
6. Seed the database:
   ```bash
   npx knex seed:run
   ```

## Technologies
- **Node.js**: JavaScript runtime for building server-side applications.
- **Express**: Web framework for managing server routes.
- **Knex.js**: SQL query builder for managing database interactions.
