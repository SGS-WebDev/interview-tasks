# Backend Developer Challenge: Product Catalog CRUD API 📦

## Overview

Welcome! In this challenge, you'll build a RESTful CRUD API for managing a product catalog using PHP.

This challenge focuses on core backend development skills - creating well-structured APIs, handling data validation, and following REST conventions.

You may use any PHP framework or approach you're comfortable with - Laravel, Symfony, Slim, or even vanilla PHP with a router. Choose what lets you work most effectively!

## Time Expectation

- ~4 hours for core requirements
- Additional time for bonus features (optional)

## Core Requirements

### 1. Product Management Endpoints

Create RESTful endpoints for managing products:

**`GET /api/products`** - List all products
- Support basic pagination (limit/offset or page-based)
- Return product count with results

**`GET /api/products/{id}`** - Get single product
- Return 404 if product doesn't exist

**`POST /api/products`** - Create new product
- Validate required fields
- Return created product with 201 status

**`PUT /api/products/{id}`** - Update product
- Update all or partial fields
- Return updated product

**`DELETE /api/products/{id}`** - Delete product
- Return 204 on success
- Return 404 if product doesn't exist

### 2. Product Model

Products should include:
- `id` (auto-generated)
- `name` (required, max 255 chars)
- `description` (optional, text)
- `price` (required, decimal, positive)
- `quantity` (required, integer, non-negative)
- `sku` (unique product identifier, required)
- `created_at` (timestamp)
- `updated_at` (timestamp)

### 3. Data Validation

- Validate all inputs appropriately
- `name`: Required, string, max 255 characters
- `price`: Required, numeric, greater than 0
- `quantity`: Required, integer, 0 or greater
- `sku`: Required, unique, alphanumeric
- Return clear validation error messages

### 4. Error Handling

- Return appropriate HTTP status codes
- Consistent JSON error format
- Handle common errors gracefully:
  - 400 for bad requests
  - 404 for not found
  - 422 for validation errors
  - 500 for server errors

### 5. Database

- Use any SQL database (MySQL, PostgreSQL, SQLite)
- Include migration files or SQL schema
- Add some seed data (optional but helpful)

### 6. Documentation

- README with:
    - Quick setup instructions
    - How to run the application
    - API endpoint documentation
    - Example requests and responses

### 7. Project Setup

- Structure the project professionally
- Include proper configuration management
- Consider development workflow and tools

## Bonus Features (Optional)

If you finish early, consider adding:

- Search/filter products by name or SKU
- Sort products by different fields
- Basic authentication (API key or similar)
- Bulk operations (create/update multiple)
- Soft deletes with restore capability
- Basic unit tests
- Docker setup
- API versioning

## Submission Guidelines

### What We're Looking For

#### 🎯 Focus on These Core Areas:

1. **Working CRUD Operations** (Most Important)
    - All endpoints function correctly
    - Proper HTTP methods and status codes
    - Data persists correctly

2. **Code Quality**
    - Clean, readable PHP code
    - Good project structure
    - Separation of concerns

3. **Data Validation**
    - Comprehensive input validation
    - Clear error messages
    - Consistent validation rules

4. **RESTful Design**
    - Following REST conventions
    - Consistent API structure
    - Logical endpoint design

#### 💡 Nice to Have:

- Advanced querying features
- Performance optimizations
- Comprehensive testing
- Development tooling

## 💡 Getting Started Tips

1. **Start with the database schema** - get your product table right
2. **Build one endpoint at a time** - start with GET /products
3. **Test as you go** - use Postman or curl to verify each endpoint
4. **Keep it simple** - nail the basics before adding features
5. **Follow REST conventions** - use proper HTTP methods and status codes

## ⏱️ Time Management Suggestion

- 30 min: Setup and database design
- 45 min: GET endpoints (list and single)
- 45 min: POST endpoint with validation
- 45 min: PUT and DELETE endpoints
- 45 min: Error handling, pagination, and documentation

## 📤 Submission

1. Create a new GitHub repository
2. Include database schema/migrations
3. Add clear setup instructions in your README
4. Provide API documentation with curl examples
5. Make sure the repository is public
6. Send us the repository link

## ❓ Questions?

If something's unclear, make reasonable assumptions and document them in your README. We value clean, working code that follows good API design principles.

---

**Remember:** This challenge is about demonstrating your ability to build clean, well-structured APIs. Focus on getting the CRUD operations working correctly with proper validation and error handling.

Good luck! 🚀