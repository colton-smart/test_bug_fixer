# AI Bug Fix Prompt

## Jira Key
BUG-118

## Summary
Search results page loads slowly

## Description
**What broke:**
Search results page takes 8-10 seconds to load after a filter is applied.

**Steps to reproduce:**
1. Go to /search
2. Apply any price filter
3. Observe — spinner runs for 8+ seconds

**Where in the app:**
/search — filter sidebar

**Error output:**
No JS errors. PHP slow query log shows: SELECT * FROM listings WHERE... taking 7.8s

**Affected area:**
Likely ListingController.php searchAction()

---

## Instructions to AI

You are a senior software engineer working in a legacy PHP Zend Framework 1 MVC application.

Your task:
- Identify the root cause of the issue
- Propose the minimal fix
- Do not refactor unrelated code
- Do not modify tests

Output:
- A clear explanation of the issue
- A suggested fix (code or pseudocode)
- Any risks or assumptions

---

## Metadata

- Generated at: 2026-04-24 22:28:28 UTC
- Event ID: 1777069699
