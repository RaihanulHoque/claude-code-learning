# Laravel Code Review Prompt

## Objective

Review Laravel code for bugs, security issues, performance concerns, maintainability problems, and Laravel best practices.

---

## General Review Prompt

Review the following Laravel code as a senior Laravel engineer.

Analyze:

### Business Logic

* Does the code correctly solve the problem?
* Are edge cases handled?
* Is there missing validation?

### Security

* SQL Injection risks
* Mass assignment vulnerabilities
* Authorization issues
* Authentication issues
* Sensitive data exposure

### Performance

* N+1 query problems
* Inefficient queries
* Unnecessary loops
* Repeated database calls
* Large collection processing

### Laravel Best Practices

* Eloquent usage
* Query Builder usage
* Validation placement
* Service separation
* Dependency Injection
* Queue usage

### Maintainability

* Naming conventions
* Function complexity
* Duplicate logic
* Readability
* SOLID principles

Provide:

1. Issues found
2. Severity (Low / Medium / High)
3. Recommended fixes
4. Refactored examples where appropriate

---

## Pull Request Review Prompt

Review this Pull Request.

Focus on:

* Bugs
* Regression risks
* Performance issues
* Security concerns
* Code quality
* Missing tests

Provide:

### Summary

Brief explanation of what the code does.

### Findings

List all issues with severity.

### Recommendations

Suggested improvements before approval.

### Approval Status

* Approve
* Approve with Changes
* Request Changes

Explain why.

---

## Query Optimization Prompt

Review the following Laravel query.

Check for:

* N+1 issues
* Missing eager loading
* Unnecessary joins
* Indexing considerations
* Query complexity

Provide optimized alternatives.

---

## Job & Queue Review Prompt

Review this Laravel Job.

Check:

* Failure handling
* Retry strategy
* Idempotency
* Queue safety
* Memory usage
* Large dataset processing

Suggest improvements.

---

## API Review Prompt

Review this Laravel API implementation.

Check:

* Validation
* Authentication
* Authorization
* Response consistency
* Error handling
* Performance
* API best practices

Provide recommendations.

---

## Personal Review Checklist

Before accepting any Claude suggestion:

* Verify business requirements.
* Verify edge cases.
* Verify production impact.
* Verify database implications.
* Verify backward compatibility.

Claude assists the review.

The engineer owns the decision.
