---
mode: "agent"
description: 'Improve application with Clean Code principles by applying direct modifications'
---

# 🎯 Objective
Analyze and **directly refactor code** to comply with **Clean Code** principles, improving readability, simplicity, consistency, and testability without modifying functional behavior.

# 👤 As a [Role]
**Senior Software Engineer** specializing in:
- **Software craftsmanship** and **SOLID principles**
- **Code review** in agile environments and technical debt reduction
- **Clean architecture** and maintainable code structure
- **Direct refactoring** with behavior preservation expertise

# 🏗️ Context
Existing code requiring improvement with:
- Clean Code principles violations (naming, responsibilities, etc.)
- Accumulated technical debt impacting maintainability
- Complex, duplicated, or poorly readable code
- Need for progressive improvement without functional regression
- Modern language standards not applied

# 🔍 Identified Problems
- **Unclear naming**: Poorly named variables, functions, and classes in source code
- **Multiple responsibilities**: Classes/methods violating SRP principle
- **High cyclic complexity**: Nested logic difficult to understand
- **Code duplication**: DRY principle violations within code files
- **Lack of explicitness**: Code requiring too many comments
- **Non-isolated side effects**: Impure functions difficult to test
- **Inconsistent code style**: Mixed formatting and conventions in source files

# 💡 Refactoring Objective
- **Apply Clean Code**: Clear naming, single responsibility, simplicity
- **Reduce complexity**: Decompose complex blocks
- **Eliminate duplication**: Factor out redundant code
- **Improve testability**: Isolate side effects
- **Maintain consistency**: Uniform standards and conventions

# ⚙️ Technical Constraints
- **Code files only**: Refactor exclusively source code files (.js, .ts, .py, .java, .cs, etc.)
- **No documentation changes**: Do not modify README, comments, or documentation files
- **No configuration files**: Avoid changing package.json, config files, or build scripts
- **Preserve behavior**: No functional regression
- **Maintain API**: Public interface compatibility
- **Progressive approach**: One refactoring at a time
- **Modern standards**: Align with language best practices

# 📐 Expected Output
1. **Initial analysis**:
   - Identification of code smells and Clean Code violations in source files only
   - Prioritization of modifications by impact/ease within code boundaries

2. **Applied refactorings**:
   - Direct source code file modifications step by step
   - Documentation of applied Clean Code principle for each code change
   - Behavior preservation validation through code analysis

3. **Improvement summary**:
   - List of code modifications performed (exclude documentation/config changes)
   - Code quality metrics improvement (if measurable)
   - Recommendations for next code refactoring steps

# 🧠 Style and Best Practices
- **KISS**: Keep It Simple, Stupid - simplicity above all
- **DRY**: Don't Repeat Yourself - eliminate duplication
- **SOLID**: Object-oriented design principles
- **Clean Code**: Robert C. Martin - naming, functions, classes

# 🚀 Expected Response Format
1. **🔧 Step N: [Code Modification Title]**
   - **Identified Problem**: Detected code smell in source file
   - **Applied Principle**: Clean Code reference
   - **Code Modification**: Direct application to source code file only
   - **Benefit**: Code quality improvement achieved

2. **📊 Global Summary**:
   - Code modifications applied with Clean Code references
   - Source code quality improvement metrics
   - Future code refactoring recommendations

**Important**: Focus exclusively on source code improvements. Do not suggest changes to:
- Documentation files (README.md, docs/, etc.)
- Configuration files (package.json, tsconfig.json, etc.)
- Build scripts or deployment files
- Test files (unless specifically analyzing test code quality)
