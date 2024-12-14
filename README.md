# CRUD-App-Backend
Backend for a CRUD application using Node.js and MongoDB.

## Overview
This project provides a backend API for managing product data. It includes operations to create, read, update, and delete products in a MongoDB database. The application is built using the following technologies:
- **Node.js**: Backend runtime environment
- **Express.js**: Web framework for building APIs
- **MongoDB**: NoSQL database for storing product data

## Features
- Add new products with details like name, quantity, price, and image.
- Fetch all product data or specific product details by ID.
- Update product information.
- Delete products from the database.

## Project Structure
project/ ├── controllers/ │ └── product.controller.js # Handles business logic for products ├── models/ │ └── product.model.js # Defines the schema for products ├── routes/ │ └── product.routes.js # Manages API routes for products ├── config/ │ └── database.js # Database connection logic ├── middlewares/ │ └── errorHandler.js # Centralized error handling middleware ├── .env # Environment variables (e.g., MongoDB URI) ├── index.js # Main entry point of the application ├── package.json # Dependencies and scripts