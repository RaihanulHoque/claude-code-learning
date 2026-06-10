# Laravel Bug Investigation Prompt Library

## Objective

Use Claude Code to systematically investigate, diagnose, and resolve bugs in Laravel applications.

The goal is not to guess.

The goal is to identify the root cause.

---

# General Bug Investigation Prompt

Act as a Senior Laravel Engineer.

Help me investigate the following issue.

Analyze:

* Possible root causes
* Related code paths
* Database impact
* Edge cases
* Production risks

Provide:

1. Most likely causes
2. How to verify each cause
3. Recommended debugging steps
4. Suggested fix

Do not jump directly to a solution.

Start with investigation.

---

# Production Error Investigation

Analyze this production error.

Consider:

* Application logs
* Stack traces
* Database queries
* Queue jobs
* Scheduled commands
* Recent code changes

Provide:

1. Root cause hypotheses
2. Evidence needed
3. Verification steps
4. Fix recommendations

Rank hypotheses from most likely to least likely.

---

# Queue Job Investigation

Investigate why this Laravel Job is failing.

Review:

* Job code
* Retry behavior
* Queue configuration
* Dependencies
* External API calls
* Database operations

Check for:

* Timeouts
* Memory issues
* Missing records
* Race conditions
* Failed dependencies

Provide a debugging plan.

---

# Reporting Issue Investigation

Review this reporting logic.

Symptoms:

* Incorrect totals
* Missing records
* Duplicate records
* Slow execution

Analyze:

* Query logic
* Date filtering
* Aggregation logic
* Joins
* Grouping

Identify possible root causes.

Provide validation steps.

---

# API Integration Investigation

Investigate this API issue.

Check:

* Request payload
* Response payload
* Authentication
* Rate limiting
* Network failures
* Data mapping

Provide:

1. Possible failure points
2. Validation steps
3. Logging improvements
4. Fix recommendations

---

# Database Investigation

Review this Laravel code and database interaction.

Check for:

* Missing records
* Incorrect relationships
* Foreign key issues
* Transaction issues
* Race conditions
* Data consistency problems

Provide root-cause analysis.

---

# Performance Investigation

Investigate this slow operation.

Analyze:

* Database queries
* Eager loading
* Collection processing
* Loops
* API requests
* Queue usage

Identify bottlenecks.

Suggest how to measure and verify each finding.

---

# Root Cause Analysis Prompt

Do not immediately propose a fix.

Instead:

1. Explain the symptom.
2. List possible causes.
3. Rank causes by likelihood.
4. Explain how to verify each one.
5. Identify the most probable root cause.
6. Then recommend a fix.

Focus on evidence-based debugging.

---

# Personal Debugging Checklist

Before implementing any fix:

* Reproduce the issue.
* Verify logs.
* Verify database state.
* Verify recent code changes.
* Verify environment differences.
* Verify assumptions.
* Confirm root cause.

Fixing symptoms is easy.

Finding the root cause is the real skill.
