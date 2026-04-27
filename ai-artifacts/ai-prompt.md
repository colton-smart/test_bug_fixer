# AI Bug Fix Prompt

## Jira Key
BUGS-11

## Summary
Client Manager - Add New Client - Popup Window

## Description
When a user is on the Client Manager, on a smaller (laptop-sized) screen, selecting “Add New Client” opens the window underneath the main masthead, obscuring the title and close option.
The goal would be that the title and close option of the pop up would not be obscured on smaller screens.
This happens with logged in users (members) and the suffix of the url is /client.manager
The suspected area would be ClientManagerController.php or ClientManagerModel.php or the views associated.

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

- Generated at: 2026-04-27 17:09:32 UTC
- Event ID: 1777309760398
