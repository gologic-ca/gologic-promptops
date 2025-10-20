# 🎯 Objective
Describe in one sentence what you want to accomplish.  
> Example: "Refactor the project structure to separate business, infrastructure, and presentation layers."

# 👤 As a [Role]
Define the expertise and perspective from which the AI should analyze and respond.  
> Example:  
> - **Senior Software Engineer** specializing in clean architecture and SOLID principles  
> - **DevOps Engineer** expert in CI/CD pipelines and infrastructure automation  
> - **Security Engineer** focused on application security and OWASP best practices  
> - **Site Reliability Engineer** with expertise in observability and system resilience  

# 🏗️ Context
Briefly describe the current state of the code or architecture.  
> Example:  
> - Monolithic Node.js application with Express  
> - Business and data layers intertwined  
> - Difficulty testing or evolving the codebase

# 🔍 Identified Problems
List the pain points you want to address.  
> Example:  
> - Tight coupling between modules  
> - Lack of modularity / testability  
> - Duplications in business logic  
> - Difficulty integrating new services

# 💡 Refactoring Objective
Explain the technical and organizational goals.  
> Example:  
> - Extract independent services  
> - Improve maintainability  
> - Facilitate unit testing  
> - Prepare for future cloud migration  

# ⚙️ Technical Constraints
Specify technologies, frameworks, or limitations.  
> Example:  
> - TypeScript  
> - REST API  
> - No new external dependencies  

# 📐 Expected Output
Describe what you want Copilot to generate.  
> Example:  
> - A new file structure  
> - Examples of refactored code structure  
> - Suggestions for module separation  
> - Coherent component naming  

# 🧠 Style and Best Practices
> - Follow **SOLID** principles  
> - Respect **12-Factor App** methodology  
> - Favor dependency injection  
> - Follow existing naming conventions  

# 🚀 Expected Response Format
Indicate how you want Copilot to respond.  
> Example:  
> - As a plan (structure + explanation)  
> - With commented code examples  
> - Listing progressive migration steps

---

💬 **PromptOps Tip:**
You can store this template in a `/prompts/refactoring-architecture.md` file and call it in Copilot Chat with this **9-section structure** for maximum precision and role-based expertise.
