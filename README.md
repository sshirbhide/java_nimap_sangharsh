Project: Nimap Product-Category Management System
The Nimap Product-Category Management System is a Spring Boot-based application that facilitates seamless management of product categories. It allows users to create, read, update, and delete product categories and the products under each category using RESTful APIs. This project is designed for efficient handling of product and category data in an enterprise setup or e-commerce platforms.

Description
The application is built using Spring Boot, ensuring modular, scalable, and easy-to-maintain code. It integrates with MySQL to store and manage data, ensuring reliable performance even with a large dataset. The API structure provides easy integration with frontend interfaces or third-party services, enabling robust product and category management.

This project demonstrates core backend functionalities using technologies like Spring Boot, JPA (Java Persistence API), and Hibernate for managing database interactions.

Key Features
CRUD Operations for Categories:

Create, retrieve, update, and delete categories via API endpoints.
Categories can be associated with multiple products (one-to-many relationship).
CRUD Operations for Products:

Add products within specific categories.
Update product details like name and price.
Retrieve and delete products individually or as part of a category.
REST API with JSON:

Provides a clean REST API design that supports JSON data formats for easy integration with client-side applications.
Database Integration:

Uses MySQL as the database to manage and store categories and products.
JPA/Hibernate handles database operations and ensures seamless interaction between the application and the database.
Pagination:

Implements server-side pagination to efficiently handle large data sets when retrieving product lists.
One-to-Many Relationships:

Configured one-to-many relationships between categories and products using JPA annotations.
Technologies Used
Java: Core programming language.
Spring Boot: Framework for rapid application development.
Spring Data JPA: Manages database persistence and interactions.
Hibernate: ORM (Object-Relational Mapping) tool for interacting with the database.
MySQL: Database used to store application data.
Maven: Dependency management and build tool.
API Endpoints Overview
Categories:

GET /api/categories: Retrieve all categories.
GET /api/categories/{id}: Retrieve category by ID.
POST /api/categories: Create a new category.
PUT /api/categories/{id}: Update an existing category.
DELETE /api/categories/{id}: Delete a category by ID.
Products:

GET /api/products: Retrieve all products.
GET /api/products/{id}: Retrieve product by ID.
POST /api/products: Create a new product.
PUT /api/products/{id}: Update an existing product.
DELETE /api/products/{id}: Delete a product by ID.
