# Kubernetes Infrastructure Development Guide for AI Assistant

## Project Overview

- **Stack**: Kubernetes-based container orchestration
- **Purpose**: Standardize AI-assisted code generation for Kubernetes infrastructure

## Coding Standards

### Kubernetes Style

- Follow Kubernetes Style Guide
- Use 2 spaces for indentation
- Use snake_case for variables
- Use camelCase for resource names
- Use UPPER_SNAKE_CASE for constants
- Limit line length to 100 characters
- Use descriptive, meaningful names for resources
- Use proper resource labels
- Use proper resource annotations
- Use proper resource selectors
- Use proper resource namespaces
- Use proper resource quotas
- Use proper resource limits
- Use proper resource requests

### Project Structure

```plaintext
k8s/
├── base/                # Base configurations
│   ├── deployment/
│   ├── service/
│   ├── ingress/
│   └── configmap/
├── overlays/            # Environment-specific overlays
│   ├── development/
│   ├── staging/
│   └── production/
├── namespaces/          # Namespace definitions
├── secrets/            # Secret management
├── storage/            # Storage configurations
├── networking/         # Network policies
├── monitoring/         # Monitoring setup
├── logging/           # Logging setup
└── security/          # Security policies
```

### Best Practices

- Follow Kubernetes best practices
- Use proper resource organization
- Implement proper resource management
- Use proper namespace isolation
- Implement proper security policies
- Use proper resource quotas
- Follow least privilege principle
- Use proper documentation
- Implement proper monitoring
- Use proper logging
- Implement proper backup
- Use proper disaster recovery

### Kubernetes Version

- Use Kubernetes 1.28+ for new clusters
- Use proper API versions
- Use proper CRD versions
- Use proper operator versions
- Use proper helm versions
- Use proper kubectl versions
- Use proper container runtime
- Use proper network plugins

### Resource Management

- Use proper resource requests
- Implement proper resource limits
- Use proper resource quotas
- Implement proper namespace quotas
- Use proper pod disruption budgets
- Implement proper pod anti-affinity
- Use proper node affinity
- Implement proper taints and tolerations

### Security

- Use proper RBAC
- Implement proper network policies
- Use proper pod security policies
- Implement proper secret management
- Use proper service accounts
- Implement proper audit logging
- Use proper security contexts
- Implement proper admission controllers

### Networking

- Use proper service types
- Implement proper ingress rules
- Use proper network policies
- Implement proper DNS policies
- Use proper load balancing
- Implement proper service mesh
- Use proper CNI plugins
- Implement proper network isolation

### Storage

- Use proper storage classes
- Implement proper volume claims
- Use proper persistent volumes
- Implement proper storage quotas
- Use proper backup strategies
- Implement proper data migration
- Use proper storage monitoring
- Implement proper storage security

### Monitoring

- Use proper metrics collection
- Implement proper alerting
- Use proper logging
- Implement proper tracing
- Use proper dashboarding
- Implement proper SLOs
- Use proper health checks
- Implement proper auto-scaling

### Testing

- Use proper integration testing
- Implement proper chaos testing
- Use proper load testing
- Implement proper security testing
- Use proper compliance testing
- Implement proper disaster recovery testing
- Use proper performance testing
- Implement proper reliability testing

### Performance

- Use proper resource optimization
- Implement proper scaling strategies
- Use proper caching
- Implement proper load balancing
- Use proper network optimization
- Implement proper storage optimization
- Use proper pod optimization
- Implement proper cluster optimization

### Build & Deployment

- Use proper CI/CD integration
- Implement proper GitOps practices
- Use proper version control
- Implement proper change management
- Use proper deployment strategies
- Implement proper rollback procedures
- Use proper monitoring
- Implement proper alerting

### Documentation

- Use proper inline documentation
- Implement proper README files
- Use proper API documentation
- Implement proper architecture documentation
- Use proper troubleshooting guides
- Implement proper runbooks
- Use proper change logs
- Implement proper version history

### Maintenance

- Use proper upgrade procedures
- Implement proper backup procedures
- Use proper scaling procedures
- Implement proper recovery procedures
- Use proper monitoring procedures
- Implement proper maintenance windows
- Use proper patch management
- Implement proper security updates
