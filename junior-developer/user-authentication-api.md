# Backend Developer Challenge: User Authentication API 🔐

## Overview

Welcome! In this challenge, you'll build a secure user authentication system as a REST API using PHP.

This challenge focuses specifically on authentication - demonstrating your understanding of security best practices, proper password handling, and session management.

You may use any PHP framework or approach you're comfortable with - Laravel, Symfony, Slim, or even vanilla PHP. Choose what lets you work most effectively!

## Time Expectation

- ~4 hours for core requirements
- Additional time for bonus features (optional)

## Core Requirements

### 1. User Registration Endpoint

**`POST /api/register`**
- Accept email and password
- Validate input (email format, password strength)
- Hash passwords properly (never store plain text!)
- Create user account
- Return appropriate response

### 2. User Login Endpoint

**`POST /api/login`**
- Accept email and password
- Verify credentials
- Generate and return authentication token/session
- Handle invalid credentials gracefully

### 3. User Profile Endpoint

**`POST /api/profile`** (protected)
- Require authentication
- Return current user's information
- Demonstrate that your auth system works

### 4. Logout Endpoint

**`POST /api/logout`** (protected)
- Invalidate the user's session/token
- Return confirmation

### 5. Data Models

**User Model:**
- `id`
- `email` (unique)
- `password` (hashed)
- `created_at`
- `updated_at`

### 6. Security Requirements

- **Password Security**:
  - Use proper hashing (bcrypt, Argon2, etc.)
  - Never store or log plain text passwords
  
- **Input Validation**:
  - Validate email format
  - Enforce reasonable password requirements
  - Sanitize all inputs

- **Error Handling**:
  - Don't leak information (e.g., "email not found" vs "invalid credentials")
  - Return consistent error formats

### 7. Documentation

- README with:
    - Quick setup instructions
    - How to run the application
    - API documentation with example requests/responses
    - Any security considerations

### 8. Project Setup

- Structure the project professionally
- Include database migrations/schema
- Consider what tools and configurations ensure security
- Think about development workflow

## Bonus Features (Optional)

If you finish early, consider adding:

- Password reset functionality
- Email verification
- Rate limiting on auth endpoints
- Refresh token mechanism
- Account lockout after failed attempts
- Basic unit tests for auth logic
- Docker setup

## Submission Guidelines

### What We're Looking For

#### 🎯 Focus on These Core Areas:

1. **Security Implementation** (Most Important)
    - Proper password hashing
    - Secure session/token handling
    - Protection against common vulnerabilities

2. **Working Authentication Flow**
    - Registration works correctly
    - Login/logout flow functions properly
    - Protected endpoints require authentication

3. **Code Quality**
    - Clean, readable PHP code
    - Logical organization
    - Consistent style

4. **Input Validation & Error Handling**
    - Comprehensive input validation
    - Helpful error messages
    - Secure error responses

#### 💡 Nice to Have:

- Advanced security features
- Comprehensive testing
- Performance considerations
- Development tooling

## 💡 Getting Started Tips

1. **Start with the database** - design your user table first
2. **Get password hashing right** - this is critical for security
3. **Test with Postman/curl** - ensure your endpoints work correctly
4. **Keep it simple** - a working basic auth system beats a broken complex one
5. **Document your security choices** - explain why you chose certain approaches

## ⏱️ Time Management Suggestion

- 30 min: Setup and database design
- 1 hour: Registration endpoint with proper hashing
- 1 hour: Login/logout functionality
- 1 hour: Authentication middleware and protected endpoint
- 30 min: Testing and documentation

## 📤 Submission

1. Create a new GitHub repository
2. Include database schema/migrations
3. Add clear setup instructions in your README
4. Document your API endpoints with examples
5. Make sure the repository is public
6. Send us the repository link

## ❓ Questions?

If something's unclear, make reasonable assumptions and document them in your README. We appreciate practical solutions and clear thinking about security trade-offs.

---

**Remember:** This challenge is all about demonstrating secure coding practices. Focus on getting the security fundamentals right - proper password handling, secure sessions, and protecting against common vulnerabilities.

Good luck! 🚀