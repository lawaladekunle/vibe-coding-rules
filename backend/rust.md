# Rust Backend Development Guide for AI Assistant

## Project Overview

- **Stack**: Rust-based backend development
- **Purpose**: Standardize AI-assisted code generation for Rust applications

## Coding Standards

### Rust Style

- Follow Rust Style Guide
- Use 4 spaces for indentation
- Use snake_case for variables and functions
- Use PascalCase for types and traits
- Use UPPER_SNAKE_CASE for constants
- Limit line length to 100 characters
- Use descriptive, meaningful names for functions and types
- Use proper ownership patterns
- Use proper borrowing rules
- Use proper lifetimes
- Use proper traits
- Use proper generics
- Use proper macros
- Use proper error handling

### Project Structure

```plaintext
src/
├── main.rs              # Application entry point
├── lib.rs               # Library root
├── api/                 # API endpoints
│   ├── mod.rs          # Module declaration
│   ├── routes.rs       # Route definitions
│   └── handlers.rs     # Request handlers
├── models/             # Data models
│   ├── mod.rs          # Module declaration
│   └── entities.rs     # Data structures
├── services/           # Business logic
│   ├── mod.rs          # Module declaration
│   └── business.rs     # Business operations
├── repositories/       # Data access
│   ├── mod.rs          # Module declaration
│   └── data.rs         # Data operations
├── config/            # Configuration
│   ├── mod.rs          # Module declaration
│   └── settings.rs     # App settings
└── utils/             # Utility functions
    ├── mod.rs          # Module declaration
    └── helpers.rs      # Helper functions
```

### Best Practices

- Follow Rust best practices
- Use proper ownership patterns
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

### Rust Version

- Use Rust 1.70+ for new projects
- Use proper async/await
- Use proper const generics
- Use proper type inference
- Use proper pattern matching
- Use proper macros
- Use proper traits
- Use proper modules

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

- Use proper SQLx/Diesel
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

- Use proper unit testing
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

- Use proper Cargo
- Implement proper environment management
- Use proper containerization
- Implement proper CI/CD
- Use proper version control
- Implement proper monitoring
- Use proper logging
- Implement proper error tracking

### Documentation

- Use proper rustdoc
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
