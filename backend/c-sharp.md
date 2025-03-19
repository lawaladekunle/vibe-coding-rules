# C# Backend Development Guide for AI Assistant

## Project Overview

- **Stack**: C#-based backend development
- **Purpose**: Standardize AI-assisted code generation for C# applications

## Coding Standards

### C# Style

- Follow C# Style Guide
- Use 4 spaces for indentation
- Use camelCase for variables and methods
- Use PascalCase for classes and properties
- Use UPPER_SNAKE_CASE for constants
- Limit line length to 120 characters
- Use descriptive, meaningful names for functions and classes
- Use proper access modifiers
- Use proper attributes
- Use proper generics
- Use proper enums
- Use proper interfaces
- Use proper abstract classes
- Use proper exception handling

### Project Structure

```plaintext
src/
├── Company.API/              # API project
│   ├── Controllers/          # API controllers
│   ├── Models/              # Data models
│   ├── Services/            # Business logic
│   ├── Repositories/        # Data access
│   ├── Configurations/      # Configuration
│   └── Program.cs           # Entry point
├── Company.Core/            # Core project
│   ├── Entities/           # Domain entities
│   ├── Interfaces/         # Core interfaces
│   └── Services/           # Core services
├── Company.Infrastructure/  # Infrastructure project
│   ├── Data/              # Data access
│   ├── Services/          # External services
│   └── Logging/           # Logging
└── Company.Tests/          # Test project
    ├── Unit/              # Unit tests
    └── Integration/       # Integration tests
```

### Best Practices

- Follow C# best practices
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

### C# Version

- Use C# 11+ for new projects
- Use proper record types
- Use proper pattern matching
- Use proper nullable reference types
- Use proper init-only setters
- Use proper top-level statements
- Use proper file-scoped namespaces
- Use proper global using directives

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

- Use proper Entity Framework Core
- Implement proper migrations
- Use proper connection pooling
- Implement proper transaction management
- Use proper query optimization
- Implement proper indexing
- Use proper caching
- Implement proper backup strategies

### Authentication & Security

- Use proper ASP.NET Core Identity
- Implement proper session management
- Use proper password hashing
- Implement proper CSRF protection
- Use proper input validation
- Implement proper output encoding
- Use proper security headers
- Implement proper audit logging

### Testing

- Use proper xUnit
- Implement proper integration testing
- Use proper Moq
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

- Use proper .NET CLI
- Implement proper environment management
- Use proper containerization
- Implement proper CI/CD
- Use proper version control
- Implement proper monitoring
- Use proper logging
- Implement proper error tracking

### Documentation

- Use proper XML documentation
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
