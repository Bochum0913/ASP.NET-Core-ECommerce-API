# ASP.NET Core E-Commerce API

A RESTful e-commerce backend application built with C# and ASP.NET Core.  
The project provides APIs for managing products, brands, branches, orders, user registration, and authentication.

## Features

- Product management
- Brand management
- Branch management
- Order processing
- User registration and login
- JWT-based authentication
- SQL Server database integration
- Entity Framework Core data access and migrations
- RESTful API endpoints
- Swagger API documentation

## Technologies

- C#
- ASP.NET Core 5
- Entity Framework Core
- Microsoft SQL Server
- REST APIs
- JWT Authentication
- Swagger / Swashbuckle
- Git

## Project Structure

- `Controllers/` – API controllers for products, brands, branches, orders, authentication, and registration
- `DAL/` – Data access layer
- `Migrations/` – Entity Framework Core database migrations
- `APIHelpers/` – API helper functionality
- `Helpers/` – Shared helper classes
- `wwwroot/` – Static application resources
- `Program.cs` – Application entry point
- `Startup.cs` – Application configuration and service registration

## API Controllers

The application includes controllers for:

- Products
- Brands
- Branches
- Orders
- User Login
- User Registration

## Authentication

The API uses JWT Bearer Authentication to support authenticated access to application resources.

## Database

The application uses Microsoft SQL Server with Entity Framework Core for data access and database migrations.

## API Documentation

Swagger / Swashbuckle is included for API documentation and endpoint testing.

## What I Learned

Through this project, I gained hands-on experience with:

- Building RESTful APIs with ASP.NET Core
- Structuring a backend application using controllers and a data access layer
- Connecting an ASP.NET Core application to SQL Server
- Using Entity Framework Core and database migrations
- Implementing JWT-based authentication
- Working with JSON-based API requests and responses
- Testing and debugging API endpoints
