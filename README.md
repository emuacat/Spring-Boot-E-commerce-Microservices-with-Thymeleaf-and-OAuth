
# Spring Boot E-commerce Microservices with Thymeleaf and OAuth

Develop a full-stack e-commerce application using Spring Boot and Thymeleaf. The backend will be structured as microservices, and the frontend will utilize Thymeleaf templates. The application will be secured using Spring Security and OAuth.

![Standalone Project Cover](./standalone-project-cover.jpg)

## Overview

Spring Boot is an open-source, Java-based framework ideal for creating microservices. In combination with Thymeleaf, a modern server-side Java template engine, we can develop interactive web applications. This project aims to set up a basic e-commerce system where users can view items, add them to a cart, and manage their cart items. Furthermore, to ensure the security of user data and transactions, we will implement OAuth2 authentication.

## Steps to Deploy the Application

### 1. **Initialization**
- Introduction to the project and its objectives.

### 2. **Setting Up the Core Components**
- Create the `Item` entity to represent products.
- Establish a repository for the `Item` entity.
- Set up the `User` class to represent customers.
- Establish a repository for the `User` class.
- Develop the `CartItem` class to represent individual items in a user's cart.
- Create a `Cart` entity to manage user's items.

### 3. **Building Functional Components**
- Implement an `Inventory Service` to manage available items.
- Expand the service functionalities.
- Introduce the capability to remove items from the cart.

