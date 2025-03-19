# Elixir Backend Development Guide for AI Assistant

## Project Overview

- **Stack**: Elixir-based backend development
- **Purpose**: Standardize AI-assisted code generation for Elixir applications

## Coding Standards

### Elixir Style

- Follow Elixir Style Guide
- Use 2 spaces for indentation
- Use snake_case for variables and functions
- Use PascalCase for modules
- Use UPPER_SNAKE_CASE for constants
- Limit line length to 100 characters
- Use descriptive, meaningful names for functions and modules
- Use proper pattern matching
- Use proper pipe operator
- Use proper guard clauses
- Use proper protocols
- Use proper behaviours
- Use proper macros
- Use proper error handling

### Project Structure

```plaintext
lib/
├── my_app/              # Application namespace
│   ├── web/            # Web-related code
│   │   ├── controllers/  # Controllers
│   │   ├── views/       # Views
│   │   └── templates/   # Templates
│   ├── accounts/       # Context module
│   │   ├── user.ex     # User schema
│   │   └── user.exs    # User functions
│   ├── core/           # Core functionality
│   │   └── utils.ex    # Utility functions
│   └── application.ex  # Application module
├── config/             # Configuration files
│   ├── config.exs      # General config
│   ├── dev.exs         # Development config
│   └── prod.exs        # Production config
├── test/               # Test files
│   └── my_app/         # Test modules
├── priv/               # Private files
│   └── repo/          # Database files
├── assets/             # Frontend assets
└── mix.exs            # Project configuration
```

### Best Practices

- Follow Elixir best practices
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

### Elixir Version

- Use Elixir 1.15+ for new projects
- Use proper type specs
- Use proper behaviours
- Use proper protocols
- Use proper macros
- Use proper compile-time features
- Use proper metaprogramming
- Use proper pattern matching

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

- Use proper Ecto
- Implement proper migrations
- Use proper connection pooling
- Implement proper transaction management
- Use proper query optimization
- Implement proper indexing
- Use proper caching
- Implement proper backup strategies

### Authentication & Security

- Use proper Guardian
- Implement proper session management
- Use proper password hashing
- Implement proper CSRF protection
- Use proper input validation
- Implement proper output encoding
- Use proper security headers
- Implement proper audit logging

### Testing

- Use proper ExUnit
- Implement proper integration testing
- Use proper Mox
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

- Use proper Mix
- Implement proper environment management
- Use proper containerization
- Implement proper CI/CD
- Use proper version control
- Implement proper monitoring
- Use proper logging
- Implement proper error tracking

### Documentation

- Use proper ExDoc
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
