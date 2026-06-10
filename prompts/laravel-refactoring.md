# Laravel Refactoring Prompt Library

## Objective

Use Claude Code to improve code quality, readability, maintainability, and scalability while preserving existing functionality.

---

# General Refactoring Prompt

Act as a Senior Laravel Engineer.

Refactor the following code while preserving all existing functionality.

Focus on:

* Readability
* Maintainability
* Separation of concerns
* Laravel best practices
* SOLID principles
* Performance improvements
* Testability

Requirements:

* Do not change business logic.
* Do not introduce breaking changes.
* Explain every major improvement.
* Highlight any potential risks.

Provide:

1. Refactored code
2. Explanation of changes
3. Benefits of the refactoring

---

# Large Controller Refactoring

Review this Laravel Controller.

Identify:

* Business logic that should move to Services
* Repeated code
* Validation improvements
* Query optimization opportunities

Refactor the controller into:

* Controller
* Service Layer
* Request Validation

Explain the responsibilities of each component.

---

# Service Class Refactoring

Review this Service class.

Focus on:

* Method size
* Single Responsibility Principle
* Duplicate logic
* Dependency management
* Testability

Recommend a cleaner structure.

Provide refactored code.

---

# Reporting Function Refactoring

Review this reporting code.

Focus on:

* Database query optimization
* Large collection processing
* Memory usage
* Maintainability
* Reusable components

Identify:

* Expensive operations
* Duplicate calculations
* Opportunities for caching

Provide a refactored implementation.

---

# Eloquent Query Refactoring

Review this Laravel query.

Check:

* N+1 query risks
* Missing eager loading
* Query complexity
* Readability

Provide:

1. Problems found
2. Optimized query
3. Expected benefits

---

# Job & Queue Refactoring

Review this Laravel Job.

Focus on:

* Retry handling
* Failure handling
* Memory efficiency
* Batch processing
* Idempotency

Suggest a production-ready implementation.

---

# Legacy Code Modernization

Review this legacy Laravel code.

Refactor it using:

* Modern Laravel practices
* Dependency Injection
* Request Validation
* Service classes
* Collection methods
* Clean architecture principles

Preserve all existing functionality.

Explain:

* Technical debt found
* Improvements made
* Future maintenance benefits

---

# Personal Refactoring Checklist

Before accepting Claude's refactoring:

* Verify business logic remains unchanged.
* Verify all edge cases still work.
* Verify performance implications.
* Verify database queries.
* Verify API responses.
* Verify backward compatibility.

The goal is not shorter code.

The goal is cleaner, safer, and more maintainable code.
