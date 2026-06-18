# DocTypes Documentation

## Overview

This document describes the DocTypes used in the Internship Management System.

---

# 1. Department

Stores department information within the organization.

## Fields

| Field Name      | Field Type |
| --------------- | ---------- |
| Department Name | Data       |
| Description     | Small Text |

## Example

| Department Name      |
| -------------------- |
| Software Development |
| Testing              |
| Human Resources      |
| Research             |

---

# 2. Mentor

Stores mentor details responsible for guiding interns.

## Fields

| Field Name  | Field Type        |
| ----------- | ----------------- |
| Mentor Name | Data              |
| Email       | Data              |
| Department  | Link (Department) |

## Relationship

```text
Mentor → Department
```

---

# 3. Intern

Stores intern information.

## Fields

| Field Name  | Field Type    |
| ----------- | ------------- |
| Intern Name | Data          |
| Email       | Data          |
| College     | Data          |
| Mentor      | Link (Mentor) |
| Status      | Select        |

## Status Options

```text
Applied
Selected
Active
Completed
```

## Relationship

```text
Intern → Mentor
```

---

# 4. Task

Stores tasks assigned to interns.

## Fields

| Field Name | Field Type    |
| ---------- | ------------- |
| Task Title | Data          |
| Intern     | Link (Intern) |
| Due Date   | Date          |
| Status     | Select        |

## Status Options

```text
Open
Working
Completed
```

## Relationship

```text
Task → Intern
```

---

# Entity Relationship Flow

```text
Department
    ↓
Mentor
    ↓
Intern
    ↓
Task
```

---

# Learning Concepts Covered

* DocType Creation
* Data Fields
* Select Fields
* Link Fields
* Relationships
* ERP Data Structure
* Frappe Framework Basics

---

# Conclusion

These DocTypes form the foundation of the Internship Management System and demonstrate how data can be linked and managed using the Frappe Framework and ERPNext.
