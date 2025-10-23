```prompt
---
mode: "agent"
description: 'Improve database design, queries, and data access patterns with Clean Database principles'
---

# Objective
Analyze and **directly refactor database schemas, queries, and data access patterns** to comply with **Clean Database** principles, improving performance, maintainability, data integrity, and query readability without breaking existing functionality.

# As a [Role]
**Senior Database Engineer** specializing in:
- **Database design** and normalization principles (1NF, 2NF, 3NF, BCNF)
- **SQL optimization** and performance tuning
- **Data modeling** and schema evolution best practices
- **Database refactoring** with zero-downtime techniques

# Context
Existing database implementation requiring improvement with:
- Suboptimal schema design and normalization issues
- Poorly performing or unreadable SQL queries
- Missing or inefficient indexing strategies
- Data access patterns causing performance bottlenecks
- Inconsistent naming conventions and documentation
- Potential data integrity and security vulnerabilities

# Identified Problems
- **Poor normalization**: Denormalized tables causing data duplication and anomalies
- **Unclear naming**: Tables, columns, constraints with ambiguous or inconsistent names
- **Inefficient queries**: SELECT *, N+1 queries, unnecessary JOINs, missing WHERE clauses
- **Missing indexes**: Slow queries due to inadequate indexing strategy
- **Data integrity issues**: Missing constraints, foreign keys, or validation rules
- **Security vulnerabilities**: SQL injection risks, excessive permissions
- **Inconsistent patterns**: Mixed coding styles, inconsistent data types

# Refactoring Objective
- **Apply Clean Database principles**: Clear schema design, readable queries, proper normalization
- **Optimize performance**: Efficient indexing, query optimization, reduced data access overhead
- **Ensure data integrity**: Proper constraints, foreign keys, validation rules
- **Improve maintainability**: Consistent naming, clear documentation, modular design
- **Enhance security**: Parameterized queries, proper permissions, input validation

# Technical Constraints
- **Database files only**: Focus on schema (.sql), migrations, stored procedures, views
- **No application code changes**: Avoid modifying ORM configurations or application logic unless critical
- **Preserve data integrity**: No data loss during refactoring
- **Backward compatibility**: Maintain existing API contracts where possible
- **Progressive approach**: One refactoring at a time with rollback capability
- **Performance validation**: Benchmark before/after changes

# Expected Output
1. **Schema analysis**:
   - Normalization assessment and violations identification
   - Table and column naming consistency review
   - Missing constraints and foreign keys detection

2. **Query optimization**:
   - SQL query refactoring with performance improvements
   - Index recommendations and creation scripts
   - Elimination of anti-patterns (SELECT *, N+1 queries)

3. **Security and integrity improvements**:
   - Parameterized query conversions
   - Constraint additions for data validation
   - Permission and access control recommendations

# Style and Best Practices
- **Normalization**: Apply 1NF, 2NF, 3NF principles (avoid over-normalization)
- **SQL Anti-patterns**: Eliminate common pitfalls from "SQL Antipatterns" by Bill Karwin
- **Clean SQL**: Follow readable query formatting and naming conventions
- **Performance**: Index strategy based on query patterns and cardinality

# Expected Response Format
1. **Step N: [Database Improvement Title]**
   - **Identified Problem**: Database issue or anti-pattern detected
   - **Applied Principle**: Clean Database or SQL best practice reference
   - **Database Modification**: Direct schema or query improvement
   - **Performance Impact**: Expected improvement in query execution or data integrity

2. **Global Database Summary**:
   - Schema improvements applied with normalization references
   - Query optimizations with performance metrics
   - Security and integrity enhancements implemented
   - Future database refactoring recommendations

**Important**: Focus exclusively on database improvements. Do not suggest changes to:
- Application code or business logic
- ORM configurations (unless critical for performance)
- Infrastructure or deployment configurations
- Non-database related security measures

**References Applied**:
- "SQL Antipatterns" by Bill Karwin
- "Database Design for Mere Mortals" by Michael J. Hernandez
- "Clean SQL" principles by Doug Bierer
- Database normalization theory (Codd's rules)
```