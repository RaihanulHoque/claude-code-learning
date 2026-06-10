# Code Review Workflow

## Objective

Use Claude Code as a code review assistant to identify potential issues, improve code quality, and reduce review time while maintaining engineering judgment.

---

## Review Areas

### 1. Business Logic

Check:

* Does the code solve the intended problem?
* Are edge cases handled?
* Is there any missing validation?
* Are error conditions considered?

---

### 2. Security

Check:

* SQL Injection risks
* Mass assignment vulnerabilities
* Authorization issues
* Authentication issues
* Input validation
* Sensitive data exposure

---

### 3. Performance

Check:

* N+1 query problems
* Unnecessary database queries
* Repeated calculations
* Inefficient loops
* Large collection processing

---

### 4. Readability

Check:

* Method length
* Variable naming
* Function responsibilities
* Duplicate logic
* Complex conditions

---

### 5. Laravel Best Practices

Check:

* Eloquent usage
* Query optimization
* Service separation
* Dependency Injection
* Validation placement
* Queue usage

---

## Claude Code Review Prompt

Review the following Laravel code.

Focus on:

* Bugs
* Security issues
* Performance concerns
* N+1 query risks
* Validation problems
* Laravel best practices
* Edge cases
* Code readability

Provide:

1. Issue description
2. Severity (Low / Medium / High)
3. Recommended solution
4. Example improvement if applicable

---

## My Review Process

### Step 1

Read the code myself.

### Step 2

Identify the purpose of the code.

### Step 3

Review with Claude Code.

### Step 4

Compare my findings with Claude's findings.

### Step 5

Apply engineering judgment before accepting suggestions.

---

## Important Observation

Claude Code should be treated as a review partner, not as the final reviewer.

The responsibility for correctness, security, and maintainability still belongs to the engineer.

---

## Future Improvements

* PHP Review Workflow
* Laravel Review Checklist
* API Review Checklist
* Database Query Review Checklist
* Security Review Workflow
