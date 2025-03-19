# Terraform Infrastructure Development Guide for AI Assistant

## Project Overview

- **Stack**: Terraform-based infrastructure development
- **Purpose**: Standardize AI-assisted code generation for infrastructure as code

## Coding Standards

### Terraform Style

- Follow HashiCorp Terraform Style Guide
- Use 2 spaces for indentation
- Use snake_case for variables and locals
- Use PascalCase for resource names
- Use UPPER_SNAKE_CASE for constants
- Limit line length to 100 characters
- Use descriptive, meaningful names for resources and variables
- Use proper variable types
- Use proper data source references
- Use proper resource dependencies
- Use proper module structure
- Use proper state management
- Use proper workspace management
- Use proper backend configuration

### Project Structure

```plaintext
terraform/
├── environments/           # Environment-specific configurations
│   ├── dev/
│   ├── staging/
│   └── prod/
├── modules/               # Reusable modules
│   ├── networking/
│   ├── compute/
│   ├── database/
│   └── security/
├── state/                # State file configurations
├── variables/            # Variable definitions
├── outputs/             # Output definitions
├── versions.tf          # Provider and version constraints
├── main.tf              # Main configuration
├── variables.tf         # Variable declarations
└── outputs.tf           # Output declarations
```

### Best Practices

- Follow infrastructure as code best practices
- Use proper state management
- Implement proper variable validation
- Use proper module composition
- Implement proper resource tagging
- Use proper naming conventions
- Follow DRY principles
- Use proper documentation
- Implement proper security practices
- Use proper version control
- Implement proper testing
- Use proper CI/CD integration

### Terraform Version

- Use Terraform 1.5+ for new projects
- Use proper provider versions
- Use proper module versions
- Use proper state file versions
- Use proper workspace features
- Use proper variable validation
- Use proper dynamic blocks
- Use proper for_each loops

### Resource Management

- Use proper resource naming
- Implement proper resource tagging
- Use proper resource dependencies
- Implement proper resource lifecycle
- Use proper resource data sources
- Implement proper resource outputs
- Use proper resource variables
- Implement proper resource validation

### State Management

- Use proper backend configuration
- Implement proper state locking
- Use proper state file organization
- Implement proper state migration
- Use proper state file security
- Implement proper state backup
- Use proper state file versioning
- Implement proper state file cleanup

### Security

- Use proper secret management
- Implement proper access control
- Use proper encryption
- Implement proper network security
- Use proper security groups
- Implement proper IAM policies
- Use proper key management
- Implement proper audit logging

### Testing

- Use proper unit testing
- Implement proper integration testing
- Use proper plan validation
- Implement proper state validation
- Use proper module testing
- Implement proper variable testing
- Use proper output testing
- Implement proper security testing

### Performance

- Use proper resource optimization
- Implement proper state optimization
- Use proper module optimization
- Implement proper variable optimization
- Use proper output optimization
- Implement proper plan optimization
- Use proper apply optimization
- Implement proper destroy optimization

### Build & Deployment

- Use proper CI/CD integration
- Implement proper environment management
- Use proper version control
- Implement proper change management
- Use proper deployment strategies
- Implement proper rollback procedures
- Use proper monitoring
- Implement proper alerting

### Documentation

- Use proper inline documentation
- Implement proper README files
- Use proper variable documentation
- Implement proper output documentation
- Use proper module documentation
- Implement proper resource documentation
- Use proper example documentation
- Implement proper architecture documentation

### Monitoring & Maintenance

- Use proper resource monitoring
- Implement proper state monitoring
- Use proper cost monitoring
- Implement proper performance monitoring
- Use proper security monitoring
- Implement proper compliance monitoring
- Use proper change monitoring
- Implement proper drift detection
