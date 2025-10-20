---
mode: "agent"
description: 'Generate CI pipeline adapted to project and chosen orchestration tool'
---

# Objective
Generate a **Continuous Integration (CI)** pipeline adapted to the project context (application, serverless, Infrastructure-as-Code) by first asking for the orchestration tool to adapt syntax and best practices.

# As a [Role]
**Senior DevOps Engineer** specializing in:
- **CI/CD pipeline design** and automation
- **Multi-platform orchestration** (GitHub Actions, GitLab CI, Azure DevOps, Jenkins)
- **Security integration** and DevSecOps practices
- **DORA metrics** and observability implementation

# Context
Project requiring CI pipeline with:
- Source code without automated pipeline or obsolete pipeline
- Need for build, test, publish automation
- Multiple orchestration tools possible (GitHub Actions, GitLab CI, etc.)
- Varied technology stack depending on project type
- Modern security and observability requirements

# Identified Problems
- **No defined orchestration tool**: Different YAML syntax per platform
- **Missing or obsolete pipeline**: No build/test automation
- **Insufficient security**: No vulnerability scanning or secrets management
- **Lack of observability**: No DORA metrics or traceability
- **Manual configuration**: Non-reproducible deployment steps

# Refactoring Objective
- **Identify orchestrator**: Ask for CI/CD tool before generation
- **Adapted pipeline**: Platform-specific syntax and best practices
- **Integrated security**: Scans, secrets management, compliance
- **Observability**: Metrics, logs, artifacts, alerts

# Technical Constraints
- **Ask for orchestrator**: GitHub Actions, GitLab CI, Azure DevOps, Jenkins, etc.
- **Technology agnostic**: Adaptable to any language/framework
- **Security mandatory**: No plain secrets, integrated scans
- **Reproducibility**: Pipeline executable locally and in CI

# Expected Output
1. **Initial configuration**:
   - Question about CI/CD orchestration tool
   - Detection of project type and technology stack

2. **Complete YAML pipeline**:
   - File adapted to chosen orchestrator
   - Structured Build → Test → Publish steps
   - Secrets and environment variables management

3. **Integrated best practices**:
   - Security scans (Trivy, Snyk)
   - Automated tests with coverage
   - Versioned and signed artifacts

# Style and Best Practices
- **KISS**: Keep It Simple, Stupid - minimal viable pipeline
- **DRY**: Don't Repeat Yourself - avoid duplication
- **Security by design**: integrated security from the start
- **DORA metrics**: Lead Time, Deployment Frequency, MTTR, Change Fail Rate

# Expected Response Format
1. **Initial question**: What CI/CD orchestration tool are you using?
2. **Generated pipeline**:
   - Complete YAML file with comments
   - Step-by-step explanation (build/test/publish)
3. **Recommendations**:
   - Security and performance improvements
   - Metrics and observability
