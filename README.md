# 🚀 Gologic Copilot PromptOps

> **Software Engineering Prompts Collection for GitHub Copilot**  
> Accelerate your DevOps, security, and architecture practices with specialized AI agents

## 📋 Overview

This repository contains a comprehensive collection of **GitHub Copilot agent prompts** to enhance the quality, security, and reliability of your applications. All prompts follow the standardized [`PROMPT.md`](PROMPT.md) format to ensure consistency and professionalism.

### 🎯 Project Objectives

- **Standardize** software engineering practices through AI
- **Accelerate** adoption of best practices (Clean Code, DevOps, SRE)
- **Secure** development with automated reviews
- **Simplify** implementation of modern architectures

## 📚 Prompts Catalog

### 🔧 **DevOps & Engineering**

| Prompt | Description | Use Cases | Expert Role |
|--------|-------------|-----------|-------------|
| [**CI Pipeline Builder**](/.github/prompts/ci-pipeline-builder.prompt.md) | Generate CI pipelines adapted to your orchestrator | GitHub Actions, GitLab CI, Azure DevOps, Jenkins | Senior DevOps Engineer |
| [**Clean Code Refactoring**](/.github/prompts/refactor-clean-code.prompt.md) | Improve code with Clean Code principles | Refactoring, technical debt, maintainability | Senior Software Engineer |

### 🛡️ **Security & Reliability**

| Prompt | Description | Specialization | Expert Role |
|--------|-------------|----------------|-------------|
| [**Security Code Review**](/.github/prompts/security-code-review.prompt.md) | Audit security with OWASP principles | AppSec, vulnerabilities, SSDLC | Security Engineer (AppSec) |
| [**SRE Guardian**](/.github/prompts/sre-guardian.prompt.md) | Improve reliability with SRE principles | Observability, resilience, DORA metrics | Senior Site Reliability Engineer |

## 🚀 How to Use

### 1. **Choose the right prompt**
Identify the improvement domain (architecture, security, CI/CD, etc.)

### 2. **Open in GitHub Copilot**
```bash
# Copy the prompt content into GitHub Copilot Chat
# Or use directly via @workspace
```

### 3. **Describe your context**
- Current state of your application
- Technologies used  
- Specific objectives

### 4. **Apply recommendations**
The agent will analyze your code and propose concrete improvements

## 📖 Standardized Format

All prompts follow the [`PROMPT.md`](PROMPT.md) format with **9 structured sections**:

- 🎯 **Objective** - Prompt purpose
- 👤 **As a [Role]** - Expert perspective and specialization
- 🏗️ **Context** - Current situation
- 🔍 **Identified Problems** - Pain points
- 💡 **Refactoring Objective** - Expected results
- ⚙️ **Technical Constraints** - Limitations and prerequisites
- 📐 **Expected Output** - Concrete deliverables
- 🧠 **Style and Best Practices** - Methodological references
- 🚀 **Expected Response Format** - Recommendations structure

## 🎭 Expert Roles

Each prompt adopts a specialized expert perspective:

- **👨‍💻 Senior DevOps Engineer** - CI/CD pipelines, orchestration, DORA metrics
- **🔒 Security Engineer (AppSec)** - OWASP, vulnerability assessment, DevSecOps  
- **⚡ Site Reliability Engineer** - SLI/SLO, observability, incident response
- **🏗️ Senior Software Engineer** - Clean Code, SOLID principles, refactoring

## 🏢 About Gologic

**Gologic** specializes in guiding companies toward technical and operational excellence. These prompts demonstrate our **AI-First** approach to:

- Accelerate best practices adoption
- Standardize software quality
- Reduce technical debt
- Optimize performance and security

---

### 🤝 Contributing

Contributions are welcome! Make sure to follow the [`PROMPT.md`](PROMPT.md) format to maintain consistency.

### 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.