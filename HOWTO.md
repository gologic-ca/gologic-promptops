# PromptOps Demo - Lunch & DevOps

## Introduction

> *"We've moved from a world where everyone codes... to a world where everyone prompts.*  
> *But without framework, without governance, AI quickly becomes creative chaos.*  
> *PromptOps is our way of bringing order — transforming the prompt into an engineering asset, in service of AI performance."*

### Paradigm Shift
We're transitioning from **"code is the source of truth"** to **"intent is the source of truth"**.  
With AI, the specification becomes the source of truth and determines what gets built.

## What is PromptOps?

**PromptOps is an industrialization concept for IT prompts** — it allows gathering functional and non-functional requirements in prompt form, making them reusable, multi-business, and versionable over time to be applied to all types of code.

### Meta Format
**Prompt Contract Template**: [PROMPT.md](https://github.com/gologic-ca/gologic-copilot-promptops/blob/main/PROMPT.md)

---

## Demonstration Plan
### **Demo: PromptOps Clean Code Refactoring**

#### 1. **Context Setting - Why PromptOps for Clean Code?**

**Objective**: Show that Copilot alone can produce correct code, but rarely clean code.

| Approach | Prompt | Result |
|----------|--------|---------|
| **Raw AI** | `"refactor this code"` | Random, Partial, Lacks precision |
| **PromptOps** | [Structured Prompt](https://github.com/gologic-ca/gologic-promptops/blob/main/.github/prompts/refactor-clean-code.prompt.md) | Precise, Considers constraints, Role-based scope |

**Goal**: Create clear contrast between "raw" AI and "tooled" AI.

#### 2. **Structured Prompt Usage**

**Objective**: Demonstrate intelligent and justified refactoring through structured prompting.

**Prompt**: [refactor-clean-code.prompt.md](https://github.com/gologic-ca/gologic-promptops/blob/main/.github/prompts/refactor-clean-code.prompt.md)

**Features**:
- **Precise**: Considers constraints and works within defined role/scope
- **Deterministic**: Provides repeatable, documented refactoring
- **Format-aware**: Copilot processes this format repeatedly and precisely

**Pro Tips**:
- Ask for comments explaining why each change was made
- Show that the prompt provides deterministic and documented refactoring

#### 3. **Multi-Context Application**

**Objective**: Demonstrate prompt applicability across different languages/code types.

**Usage Flow**:
1. Import `gologic-promptops` project
2. Launch `/refactor-clean-code`

**Test Repositories**:
- **Python**: [aws-lambda-python-examples](https://github.com/gologic-ca/aws-lambda-python-examples)
- **Terraform**: [formation-terraform](https://github.com/gologic-ca/formation-terraform)

#### 4. **Industrial Scale Refactoring**

**Objective**: Show usage in typical PR/issue workflow.

**Issue**: [Workshop-dette-technique](https://github.com/gologic-ca/Workshop-dette-technique/issues)

**Goal**: Demonstrate PromptOps = Guided Refactoring + AI Code Review.

#### 5. **Self-Evaluating Prompts**

**Objective**: Show that prompts can be continuously improved.

**Meta-Prompt**: *"Analyze this prompt according to Clean Prompting principles and suggest improvements."*

**Goal**: Realize that PromptOps is living and evolutionary.

---

## Available Prompts

| Prompt | Purpose | Link |
|--------|---------|------|
| **Clean Code** | Code refactoring & quality | [refactor-clean-code.prompt.md](https://github.com/gologic-ca/gologic-copilot-promptops/blob/main/.github/prompts/refactor-clean-code.prompt.md) |
| **OWASP Security** | Security code review | [security-code-review.prompt.md](https://github.com/gologic-ca/gologic-copilot-promptops/blob/main/.github/prompts/security-code-review.prompt.md) |
| **Pipeline Builder** | CI/CD optimization | [ci-pipeline-builder.prompt.md](https://github.com/gologic-ca/gologic-copilot-promptops/blob/main/.github/prompts/ci-pipeline-builder.prompt.md) |

---

## Use Cases by Business Line
*PromptOps use cases organized by our 3 business lines: Software Engineering, SDLC & CI/CD, Platform Engineering*

### Software Engineering

| Use Case | Objective | Impact |
|----------|-----------|--------|
| **AI-Guided Refactoring** | Modernize legacy code according to Clean Architecture principles | Reduced technical debt, consistent code quality |
| **Unit & Functional Test Generation** | Systematically increase test coverage | Fewer regressions, faster QA cycles |
| **Living Code Documentation** | Auto-generate technical documentation from source code and comments | Up-to-date docs, accelerated onboarding |
| **Security & Compliance Review** | Detect security flaws, exposed secrets, vulnerable dependencies | Built-in security "by design" |

### SDLC & CI/CD

| Use Case | Objective | Impact |
|----------|-----------|--------|
| **CI/CD Pipeline Generation & Optimization** | Create consistent GitHub Actions workflows compliant with internal standards | Fewer errors, faster deployments |
| **Pipeline Review Automation** | Audit and improve existing CI/CD pipeline quality | More stable pipelines, reduced cloud costs |
| **Changelog & Release Notes Generation** | Standardize version notes for each deployment | Clearer communication between Dev, Ops, and Product |
| **AI Delivery Criteria Validation** | Automate quality criteria validation before production | Reinforced CI/CD governance |

### Platform Engineering

| Use Case | Objective | Impact |
|----------|-----------|--------|
| **Assisted Migration & Re-platforming** | Migrate tools (Bitbucket → GitHub, Jenkins → GitHub Actions, Nexus → Artifactory) | Accelerated migration, less rework |
| **Observability & Assisted Diagnostics** | Detect bottlenecks in systems and pipelines | Reduced MTTR, increased resilience |
| **Cloud & License Cost Optimization** | Analyze and reduce operational costs | Tangible savings, financial visibility |
| **AI Playbook & Runbook Generation** | Auto-document incidents, resolutions, and standard procedures | Knowledge transfer and operational reliability |

---

## References

| Resource | Link | Description |
|----------|------|-------------|
| **Continuous AI** | [githubnext.com/projects/continuous-ai](https://githubnext.com/projects/continuous-ai/) | GitHub Next's continuous AI integration |
| **Awesome Copilot** | [github.com/github/awesome-copilot](https://github.com/github/awesome-copilot/) | Curated list of Copilot resources |
| **Speckit** | [Spec-driven Development](https://github.blog/ai-and-ml/generative-ai/spec-driven-development-with-ai-get-started-with-a-new-open-source-toolkit/) | AI-powered spec-driven development toolkit |
| **PromptOps Blog** | [promptops.dev](https://promptops.dev/article/Best_practices_for_designing_effective_prompts_for_language_models.html) | Best practices for prompt engineering |