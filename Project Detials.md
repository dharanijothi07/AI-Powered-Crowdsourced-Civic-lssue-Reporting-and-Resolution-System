# AI-Powered Crowdsourced Civic Issue Reporting and Resolution System

## 1. Approved Project Title

**AI-Powered Crowdsourced Civic Issue Reporting and Resolution System**

---

## 2. Problem Statement

Citizens often face difficulties in reporting civic issues such as potholes, garbage accumulation, water leakage, damaged streetlights, and traffic problems. Existing complaint systems are slow, lack transparency, and do not provide effective tracking. A smart system is needed to streamline issue reporting, prioritization, and resolution.

---

## 3. Project Objectives

* Enable citizens to report civic issues easily through a web/mobile platform.
* Use AI to automatically classify reported issues.
* Prioritize complaints based on severity and location.
* Route complaints to the appropriate government department.
* Provide real-time status tracking for citizens.
* Improve transparency and accountability in civic issue management.

---

## 4. Module List

### Module 1: User Management

* User Registration
* User Login
* Profile Management

### Module 2: Issue Reporting

* Submit Complaint
* Upload Images
* Location Detection

### Module 3: AI-Based Classification

* Issue Categorization
* Severity Prediction
* Duplicate Complaint Detection

### Module 4: Complaint Management

* Complaint Assignment
* Status Updates
* Resolution Tracking

### Module 5: Admin Dashboard

* Monitor Complaints
* Generate Reports
* Manage Users

### Module 6: Notification System

* Complaint Acknowledgement
* Status Update Alerts
* Resolution Notifications

---

## 5. Use Case Diagram

### Actors:

1. Citizen
2. Admin
3. Government Department

### Use Cases:

* Register/Login
* Report Issue
* Upload Evidence
* Track Complaint Status
* Receive Notifications
* Review Complaints
* Assign Complaints
* Update Resolution Status
* Generate Reports

---

## 6. Table List

### Users

| Field Name | Type    |
| ---------- | ------- |
| user_id    | INT     |
| name       | VARCHAR |
| email      | VARCHAR |
| password   | VARCHAR |
| phone      | VARCHAR |

### Complaints

| Field Name    | Type    |
| ------------- | ------- |
| complaint_id  | INT     |
| user_id       | INT     |
| issue_type    | VARCHAR |
| description   | TEXT    |
| location      | VARCHAR |
| image_path    | VARCHAR |
| status        | VARCHAR |
| date_reported | DATE    |

### Departments

| Field Name   | Type    |
| ------------ | ------- |
| dept_id      | INT     |
| dept_name    | VARCHAR |
| officer_name | VARCHAR |

### Resolution

| Field Name    | Type |
| ------------- | ---- |
| resolution_id | INT  |
| complaint_id  | INT  |
| resolved_date | DATE |
| remarks       | TEXT |

---

## 7. ER Diagram

### Entities:

* User
* Complaint
* Department
* Resolution

### Relationships:

* One User can create many Complaints.
* One Complaint belongs to one Department.
* One Complaint has one Resolution.
* One Department handles many Complaints.

User (1) ------ (M) Complaint

Department (1) ------ (M) Complaint

Complaint (1) ------ (1) Resolution

---

## Technology Stack

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Java / Spring Boot

### Database

* MySQL

### AI Technologies

* Machine Learning
* Natural Language Processing (NLP)
* Image Classification

### Tools

* GitHub
* VS Code
* MySQL Workbench

---

## Expected Outcome

The system will help citizens report civic issues efficiently while enabling authorities to resolve them faster through AI-driven prioritization, automated classification and real-time tracking.
