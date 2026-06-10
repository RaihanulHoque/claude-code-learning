# Codebase Analysis Workflow

## Objective

Use Claude Code to quickly understand an unfamiliar codebase, identify key business logic, and reduce onboarding time for new projects.

---

## What I Want To Understand

When entering a new project, I want answers to the following questions:

### Business

* What problem does this application solve?
* Who are the users?
* What are the core business workflows?

---

### Architecture

* Which framework is used?
* How is the project structured?
* What design patterns are used?
* Are there services, repositories, jobs, events, or middleware?

---

### Data Layer

* What are the main database tables?
* How are models related?
* Which entities are most important?

---

### Application Flow

* How does a request travel through the system?
* Which controllers handle requests?
* Which services contain business logic?
* Which jobs run asynchronously?

---

### Integrations

* What external APIs are used?
* What webhooks exist?
* Are there scheduled tasks?
* Are queues being used?

---

## Initial Analysis Prompt

Analyze this codebase and explain:

1. Project purpose
2. Overall architecture
3. Important directories
4. Main models and relationships
5. Services and business logic
6. Jobs, queues and scheduled tasks
7. External integrations
8. Potential technical debt
9. Recommended starting points for a new developer

Provide the explanation as if onboarding a new team member.

---

## Laravel-Specific Analysis Prompt

Analyze this Laravel application.

Identify:

* Models
* Controllers
* Services
* Jobs
* Middleware
* Events
* Scheduled Commands
* API Integrations

Also explain:

* Core business workflows
* Most important database relationships
* Potential bottlenecks
* Areas that may require refactoring

---

## My Analysis Process

### Step 1

Review project structure.

Focus on:

```text
app/
routes/
database/
config/
resources/
```

---

### Step 2

Identify main business entities.

Examples:

* User
* Tenant
* Order
* Facility
* MarketingSource

---

### Step 3

Understand relationships.

Questions:

* Who owns what?
* Which models are central?
* What data drives the application?

---

### Step 4

Trace one complete workflow.

Example:

Tenant Move-In

Request
→ Controller
→ Service
→ Model
→ Database
→ Queue Job
→ Notification

---

### Step 5

Identify background processes.

Check:

* Queue Workers
* Scheduled Commands
* Cron Jobs
* Event Listeners
* Notifications

---

### Step 6

Identify integrations.

Examples:

* Payment Providers
* External APIs
* Webhooks
* Third-party Services

---

## Things Claude Often Finds Quickly

* Hidden business logic
* Large controllers
* Missing services
* Circular dependencies
* N+1 query risks
* Unused code
* Duplicate logic

---

## Important Observation

Claude Code can accelerate understanding significantly, but architectural conclusions should always be validated through direct code inspection and testing.

The goal is not to replace understanding.

The goal is to reach understanding faster.

---

## Future Improvements

* Legacy System Analysis Workflow
* SaaS Application Analysis Workflow
* API-First Project Analysis Workflow
* Microservice Analysis Workflow
* Database Schema Analysis Workflow
