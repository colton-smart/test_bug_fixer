# AI Bug Fix Prompt

## Jira Key
BUG-117

## Summary
Dashboard widget order not saving on mobile viewport

## Description
**What broke:**
Widget order resets to default after saving on screens under 768px wide.

**Steps to reproduce:**
1. Log in as any agent
2. Navigate to /dashboard
3. Resize browser to mobile width
4. Drag widgets to a new order
5. Click Save Layout
6. Refresh — order has reset

**Where in the app:**
/dashboard — SavedSearch widget area

**Error output:**
Uncaught TypeError: Cannot read properties of undefined (reading 'columnCount') at DashboardController.js:482

**Affected area:**
DashboardController.js, likely the saveLayout() method

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

- Generated at: 2026-04-24 15:38:11 UTC
- Event ID: 1777045081
