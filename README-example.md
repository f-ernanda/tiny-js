# ACME Product Catalog API

A RESTful API to manage ACME Corporation's extensive catalog of innovative (and sometimes explosive) products.

![ACME Logo Demo][logo]

## 💻 About the project

This project was born from a need to modernize ACME's legacy product management system. After several incidents involving misplaced dynamite orders and rocket-powered roller skates being sent to the wrong addresses, I decided it was time for a proper API.

In practice, it's a REST API that:

- Lists products with filtering and pagination
- Retrieves detailed product information by ID
- Creates and manages product categories
- Updates inventory levels across warehouses
- Tracks product availability and stock status

## 🎨 Implemented features

The API currently supports:

- CRUD operations for ACME's diverse product line
- Category organization (from rocket-powered items to spring-loaded traps)
- Real-time stock levels across multiple warehouses
- Search and filtering to find the perfect explosive device (or magnet) quickly
- Interactive Swagger / OpenAPI documentation

This project is built with NestJS, TypeScript, TypeORM, and PostgreSQL.

## 🎯 What I learned

Working on this project helped me understand several important backend concepts.

In particular, I learned a lot about:

- How modules, controllers, and services work together
- How to handle one-to-many and many-to-many associations between products and categories
- How to structure RESTful endpoints and maintain consistency
- Strategies in writing both unit tests for business logic and e2e tests for full API flows
- Implementation of global exception filters for consistent error responses

It was particularly valuable to see how architectural decisions impact code maintainability as the project grows.

## 🌟 Current state

- Project status: **in progress 🚧**
- Next steps:
  - Add authentication and authorization (JWT)
  - Implement product reviews and ratings system
  - Add GraphQL endpoint alongside REST
  - Create admin dashboard for inventory management
  - Add warning labels API for hazardous products

## 🏁 Getting started

You can run this project locally by following these steps:

```bash
# Clone the repository
git clone https://github.com/acme-corp/product-catalog-api.git
cd product-catalog-api

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env

# Run database migrations
npm run migration:run

# Start the development server
npm run start:dev
```

The API will be available at `http://localhost:3000`.

## 🌐 Online version

The API is available at:
👉 https://api.acme-corp.com/v1

Interactive API documentation (Swagger):
👉 https://api.acme-corp.com/docs

## 📃 License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for more information.

---

🌱

<!-- links -->

[logo]: https://placehold.co/800x400?text=ACME+Product+Catalog+API
