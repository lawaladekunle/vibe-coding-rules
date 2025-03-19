# C Backend Development Guide for AI Assistant

## Project Overview

- **Stack**: C-based backend development
- **Purpose**: Standardize AI-assisted code generation for C applications

## Coding Standards

### C Style

- Follow C Style Guide
- Use 4 spaces for indentation
- Use snake_case for variables and functions
- Use PascalCase for types and structs
- Use UPPER_SNAKE_CASE for constants and macros
- Limit line length to 100 characters
- Use descriptive, meaningful names for functions and types
- Use proper header guards
- Use proper include guards
- Use proper function declarations
- Use proper type definitions
- Use proper struct definitions
- Use proper enum definitions
- Use proper error handling

### Project Structure

```plaintext
src/
├── main.c              # Application entry point
├── include/            # Header files
│   ├── api.h          # API declarations
│   ├── models.h       # Data model declarations
│   ├── services.h     # Service declarations
│   └── utils.h        # Utility declarations
├── api/               # API implementation
│   ├── routes.c       # Route handlers
│   └── handlers.c     # Request handlers
├── models/            # Data models
│   └── entities.c     # Data structures
├── services/          # Business logic
│   └── business.c     # Business operations
├── utils/             # Utility functions
│   └── helpers.c      # Helper functions
└── tests/             # Test files
    └── test_*.c       # Test implementations
```

### Best Practices

- Follow C best practices
- Use proper memory management
- Implement proper error handling
- Use proper logging
- Implement proper transaction management
- Use proper caching
- Implement proper security
- Use proper performance optimization
- Follow SOLID principles
- Use proper design patterns
- Implement proper testing
- Use proper documentation

### C Version

- Use C11 for new projects
- Use proper atomic operations
- Use proper alignment specifiers
- Use proper static assertions
- Use proper generic selections
- Use proper complex numbers
- Use proper type-generic math
- Use proper bounds checking

### API Development

- Use proper REST principles
- Implement proper API versioning
- Use proper HTTP methods
- Implement proper status codes
- Use proper request validation
- Implement proper response formatting
- Use proper error handling
- Implement proper rate limiting

### Database Interaction

- Use proper SQLite/PostgreSQL
- Implement proper migrations
- Use proper connection pooling
- Implement proper transaction management
- Use proper query optimization
- Implement proper indexing
- Use proper caching
- Implement proper backup strategies

### Authentication & Security

- Use proper JWT handling
- Implement proper session management
- Use proper password hashing
- Implement proper CSRF protection
- Use proper input validation
- Implement proper output encoding
- Use proper security headers
- Implement proper audit logging

### Testing

- Use proper Unity
- Implement proper integration testing
- Use proper mocking
- Implement proper test containers
- Use proper test coverage
- Implement proper performance testing
- Use proper security testing
- Implement proper load testing

### Performance

- Use proper caching
- Implement proper async operations
- Use proper connection pooling
- Implement proper query optimization
- Use proper memory management
- Implement proper garbage collection
- Use proper profiling
- Implement proper monitoring

### Build & Deployment

- Use proper Make/CMake
- Implement proper environment management
- Use proper containerization
- Implement proper CI/CD
- Use proper version control
- Implement proper monitoring
- Use proper logging
- Implement proper error tracking

### Documentation

- Use proper Doxygen
- Implement proper API documentation
- Use proper architecture documentation
- Implement proper README files
- Use proper deployment guides
- Implement proper troubleshooting guides
- Use proper maintenance guides
- Implement proper code comments

### Security

- Use proper authentication
- Implement proper authorization
- Use proper data encryption
- Implement proper input validation
- Use proper output encoding
- Implement proper security headers
- Use proper audit logging
- Implement proper vulnerability scanning
