# Simple Transaction API

## Overview
This is a simple CRUD (Create, Read, Update, Delete) API built with Node.js, Fastify, MySQL, and Knex. It's designed for educational purposes and demonstrates basic API operations. The API manages financial transactions, supporting both credit and debit entries.

## Features
- **Create Transactions**: Add new credit or debit transactions.
- **List Transactions**: Retrieve a list of all transactions.
- **Summary**: Get a summary of transactions, where credits are positive and debits are negative.

## Technologies Used
- **Node.js**: A JavaScript runtime built on Chrome's V8 JavaScript engine.
- **Fastify**: A fast and low overhead web framework for Node.js.
- **MySQL**: A robust and reliable database management system.
- **Knex**: A SQL query builder for JavaScript.

## Getting Started

### Prerequisites
- Node.js
- MySQL Database

### Installation
1. Clone this repository.
   
   Run:

   ```bash
   npm install

### Configuring the Database
- Create a MySQL database and note the credentials.
- Set up your database configuration in a `.env` and `.env.test` files based off of the `.env.example` and `.env.test.example` file.

  The API will be available at `http://localhost:[PORT]` depending on the `PORT` configuration you set on your `.env`.

### API Endpoints
- `POST /transactions`: Create a new transaction.
- `GET /transactions`: List all transactions.
- `GET /transactions/summary`: Get a summary of all transactions.
