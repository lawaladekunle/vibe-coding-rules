# Go Backend Development Guide for AI Assistant

## Project Overview

- **Stack**: Go-based backend development
- **Purpose**: Standardize AI-assisted code generation for Go applications

## Coding Standards

### Go Style

- Follow Go Style Guide
- Use tabs for indentation
- Use camelCase for variables and methods
- Use PascalCase for exported names
- Use UPPER_SNAKE_CASE for constants
- Limit line length to 120 characters
- Use descriptive, meaningful names for functions and types
- Use proper error handling
- Use proper context handling
- Use proper goroutine management
- Use proper channel patterns
- Use proper interface design
- Use proper package organization
- Use proper dependency injection

### Project Structure

```plaintext
cmd/
└── api/                # Application entry point
    └── main.go        # Main function
internal/              # Private application code
    ├── api/          # API handlers
    ├── models/       # Data models
    ├── services/     # Business logic
    └── repository/   # Data access
pkg/                   # Public packages
    ├── middleware/   # HTTP middleware
    └── utils/        # Utility functions
api/                   # API definitions
    └── proto/        # Protocol buffers
test/                  # Test files
    └── integration/  # Integration tests
go.mod                 # Go module definition
```

### Best Practices

- Follow Go best practices
- Use proper dependency injection
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

### Go Version

- Use Go 1.21+ for new projects
- Use proper generics
- Use proper workspace mode
- Use proper embed directive
- Use proper fuzzing
- Use proper build constraints
- Use proper type parameters
- Use proper interface constraints

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

- Use proper GORM
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

- Use proper testing package
- Implement proper integration testing
- Use proper testify
- Implement proper mockery
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

- Use proper Go modules
- Implement proper environment management
- Use proper containerization
- Implement proper CI/CD
- Use proper version control
- Implement proper monitoring
- Use proper logging
- Implement proper error tracking

### Documentation

- Use proper godoc
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
