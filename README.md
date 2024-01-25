# Marketplace API

Welcome to the Marketplace API repository! This API provides functionalities for managing items, user authentication, and purchases.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [API Endpoints](#api-endpoints)
- [Authentication](#authentication)
- [Rate Limiting](#rate-limiting)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This API is built using Node.js, Express, and integrates JSON Web Token (JWT) for authentication. It offers various endpoints to manage items, handle user authentication, and track purchases.

## Features

- User authentication with JWT
- CRUD operations for items
- Purchase tracking
- Rate limiting for API requests

## Getting Started

Follow these steps to set up and run the API locally:

1. Clone the repository: `git clone https://github.com/your-username/marketplace-api.git`
2. Install dependencies: `npm install`
3. Start the server: `npm start`
4. Access the API at `http://localhost:3000`

## API Endpoints

- **GET /items**: Retrieve all items
- **GET /items/:id**: Retrieve a specific item by ID
- **POST /items**: Create a new item
- **DELETE /items/:id**: Delete an item by ID
- **POST /purchases**: Make a purchase

For detailed API documentation, explore [Swagger Documentation](http://localhost:3000/api-docs).

## Authentication

The API uses JWT for user authentication. To log in and receive a token, use the `/login` endpoint.
