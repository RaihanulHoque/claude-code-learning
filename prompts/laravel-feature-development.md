# Laravel Feature Development Prompt Library

## Objective

Use Claude Code to design, plan, implement, review, and improve Laravel features while maintaining code quality and scalability.

The goal is not simply generating code.

The goal is building production-ready features.

---

# Feature Planning Prompt

Act as a Senior Laravel Architect.

Help me design the following feature.

Provide:

1. Feature overview
2. Database design
3. Model relationships
4. Business logic flow
5. API endpoints (if applicable)
6. Validation requirements
7. Security considerations
8. Edge cases
9. Suggested implementation plan

Focus on maintainability and scalability.

---

# Feature Breakdown Prompt

Break this feature into implementation tasks.

Provide:

### Database Tasks

* Migrations
* Tables
* Indexes

### Backend Tasks

* Models
* Services
* Controllers
* Jobs
* Events

### Frontend Tasks

* Forms
* API calls
* Validation

### Testing Tasks

* Unit tests
* Feature tests

Provide tasks in implementation order.

---

# Full Feature Development Prompt

Act as a Senior Laravel Engineer.

Build the following feature.

Requirements:

* Follow Laravel best practices.
* Use clean architecture principles.
* Keep business logic outside controllers.
* Use dependency injection where appropriate.
* Include validation.
* Consider future scalability.

Generate:

1. Migration
2. Model
3. Request Validation
4. Service Class
5. Controller
6. Routes
7. Tests

Explain architectural decisions.

---

# Existing Feature Enhancement Prompt

Review this existing feature.

Analyze:

* Current implementation
* Limitations
* Technical debt
* Performance concerns

Suggest:

* Improvements
* Refactoring opportunities
* Additional edge case handling
* Better architecture if necessary

Provide implementation recommendations.

---

# API Feature Development Prompt

Design a Laravel API feature.

Include:

* Routes
* Request validation
* Authentication
* Authorization
* Error handling
* Response structure

Provide example requests and responses.

Follow REST principles.

---

# Queue-Based Feature Prompt

Design this feature using Laravel Queues.

Consider:

* Background processing
* Failure handling
* Retry strategy
* Idempotency
* Performance

Provide architecture and implementation recommendations.

---

# Reporting Feature Prompt

Design a reporting feature.

Consider:

* Data sources
* Query performance
* Aggregation logic
* Filtering
* Pagination
* Export requirements

Suggest scalable implementation approaches.

---

# Feature Review Prompt

Review this feature implementation.

Evaluate:

* Business logic
* Security
* Performance
* Maintainability
* Test coverage
* User experience

Provide:

1. Strengths
2. Risks
3. Suggested improvements

---

# Personal Feature Development Checklist

Before implementation:

* Understand the business goal.
* Identify edge cases.
* Design the database properly.
* Plan for scalability.
* Consider security.
* Consider reporting requirements.
* Consider future maintenance.

Before deployment:

* Test happy path.
* Test edge cases.
* Verify permissions.
* Verify performance.
* Verify rollback strategy.

Good software is not just code.

Good software solves business problems reliably.
