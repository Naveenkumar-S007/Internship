# Internship Management System

## Overview

Internship Management System is a simple demo project designed for learning Frappe Framework and ERPNext v15 customization concepts.

This project demonstrates how custom modules can be created using DocTypes, Link Fields, Reports, and Workspaces within the Frappe Framework.

---

## Objectives

* Learn Frappe Application Structure
* Understand Module Creation
* Create Custom DocTypes
* Configure Link Fields
* Design Workspaces
* Generate Reports
* Maintain Project Documentation in GitHub

---

## Project Structure

```text
Internship-Management/

├── README.md
├── docs/
│   ├── doctypes.md
│   ├── workspace.md
│   └── reports.md
│
└── screenshots/
```

---

## Modules

### Department

Stores department information.

Fields:

* Department Name
* Description

### Mentor

Stores mentor information.

Fields:

* Mentor Name
* Email
* Department

### Intern

Stores intern details.

Fields:

* Intern Name
* Email
* College
* Mentor
* Status

### Task

Stores tasks assigned to interns.

Fields:

* Task Title
* Intern
* Due Date
* Status

---

## Relationships

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

## Workspace

### Internship Dashboard

Shortcuts:

* Department
* Mentor
* Intern
* Task

---

## Reports

### Intern Summary Report

Displays:

* Intern Name
* College
* Mentor
* Status

### Task Report

Displays:

* Task Title
* Intern
* Due Date
* Status

---

## Technologies Used

* Frappe Framework v15
* ERPNext v15
* Python
* MariaDB
* GitHub

---

## Learning Outcomes

Through this project, the following concepts were explored:

* Custom App Design
* Module Creation
* DocType Design
* Link Fields
* Workspace Configuration
* Report Creation
* GitHub Repository Management

---

## Future Enhancements

* Attendance Management
* Performance Reviews
* Internship Certificates
* Notifications
* Workflow Automation
* Dashboard Charts

---

## Author

Naveen Kumar S

MCA Graduate | Software Developer Aspirant

GitHub:
https://github.com/Naveenkumar-S007
