# Employee Management System (EMS)
## Requirements Gathering Document

**Document Version:** 1.0  
**Document Status:** Draft – For Requirements Validation  
**Project Manager:** Project Lead  
**Methodology:** Agile / Scrum

---

## 1. Purpose

This document defines the initial business, functional, and non-functional requirements for the Wrio Byte Employee Management System.

It will serve as a reference for the Product Owner, Project Manager, designers, developers, and QA team during planning, design, development, and testing.

The requirements are preliminary and must be reviewed and validated before being treated as approved development specifications.

## 2. Project Background

The Wrio Byte Employee Management System is a proposed web application intended to centralize selected employee management processes.

The initial version will focus on employee information, department and position management, attendance monitoring, leave requests and approvals, and basic reporting.

The project is being developed as a portfolio initiative to demonstrate practical project management and software development collaboration.

## 3. Business Requirements

| ID | Business Requirement | Priority |
|---|---|---|
| BR-01 | The system shall provide a centralized platform for employee information. | Must Have |
| BR-02 | The system shall support role-based access for administrators, HR staff, and employees. | Must Have |
| BR-03 | The system shall help HR staff manage employee attendance records. | Must Have |
| BR-04 | The system shall support employee leave applications and approval workflows. | Must Have |
| BR-05 | The system shall provide a dashboard and basic reports for monitoring HR information. | Should Have |
| BR-06 | The system shall help reduce repetitive manual HR administration tasks. | Should Have |

## 4. User Roles

### 4.1 Administrator
The Administrator manages system-level access and configuration.

Expected permissions:
- Manage user accounts.
- Assign and manage user roles.
- Access employee and department records.
- Manage system settings where applicable.
- View administrative dashboard information.

### 4.2 HR Staff
HR Staff manage employee records and routine HR activities.

Expected permissions:
- Create and update employee profiles.
- View employee information.
- Manage departments and positions.
- Monitor attendance records.
- Review and process leave applications.
- View and generate basic HR reports.

### 4.3 Employee
Employees access their own information and employee-facing features.

Expected permissions:
- Log in and log out.
- View their own employee profile.
- View their attendance information.
- Submit leave applications.
- View leave request status.

Access permissions must be validated during system design to ensure users cannot view or modify information outside their authorization.

## 5. Functional Requirements

### 5.1 Authentication and User Management

| ID | Requirement | Priority |
|---|---|---|
| FR-01 | The system shall allow authorized users to log in using valid credentials. | Must Have |
| FR-02 | The system shall allow users to log out securely. | Must Have |
| FR-03 | The system shall support Administrator, HR Staff, and Employee roles. | Must Have |
| FR-04 | The system shall restrict access to features based on assigned user roles. | Must Have |

### 5.2 Employee Profile Management

| ID | Requirement | Priority |
|---|---|---|
| FR-05 | Authorized users shall be able to create employee profiles. | Must Have |
| FR-06 | Authorized users shall be able to view employee records. | Must Have |
| FR-07 | Authorized users shall be able to update employee information. | Must Have |
| FR-08 | Authorized users shall be able to delete or deactivate employee records according to the approved data policy. | Should Have |

Proposed employee information fields may include:
- Employee ID
- First name
- Last name
- Email address
- Contact number
- Department
- Position
- Employment status
- Date hired

The final list of fields will be confirmed during requirements validation.

### 5.3 Department and Position Management

| ID | Requirement | Priority |
|---|---|---|
| FR-09 | Authorized users shall be able to create, view, update, and manage departments. | Must Have |
| FR-10 | Authorized users shall be able to assign positions to employee records. | Must Have |

### 5.4 Attendance Management

| ID | Requirement | Priority |
|---|---|---|
| FR-11 | The system shall support attendance record creation and monitoring. | Must Have |
| FR-12 | Authorized HR users shall be able to view attendance information. | Must Have |
| FR-13 | Employees shall be able to view their own attendance records. | Should Have |

The attendance process, including whether records are entered manually or through a digital check-in/check-out feature, will be finalized during design.

### 5.5 Leave Management

| ID | Requirement | Priority |
|---|---|---|
| FR-14 | Employees shall be able to submit leave applications. | Must Have |
| FR-15 | Employees shall be able to view the status of their leave applications. | Must Have |
| FR-16 | Authorized HR users shall be able to review and approve or reject leave applications. | Must Have |
| FR-17 | The system shall maintain leave request records and their status. | Must Have |

### 5.6 Dashboard and Reporting

| ID | Requirement | Priority |
|---|---|---|
| FR-18 | The system shall display a dashboard with relevant HR summaries. | Should Have |
| FR-19 | Authorized users shall be able to view basic employee and attendance reports. | Should Have |
| FR-20 | The system should support exporting selected reports or records. | Could Have |

## 6. Non-Functional Requirements

| ID | Category | Requirement |
|---|---|---|
| NFR-01 | Security | The system must authenticate users before granting access to protected features. |
| NFR-02 | Access Control | The system must enforce role-based permissions. |
| NFR-03 | Performance | Common user actions should respond within an acceptable time under the expected demo workload. |
| NFR-04 | Usability | The interface should be understandable and easy to navigate for its intended users. |
| NFR-05 | Compatibility | The web application should support current major desktop browsers. |
| NFR-06 | Reliability | The system should handle invalid inputs and errors without unexpected data loss. |
| NFR-07 | Privacy | The project demonstration and testing must use synthetic employee data rather than real personal employee information. |
| NFR-08 | Maintainability | The application should use organized, documented code and a maintainable project structure. |

Specific performance, security, and compatibility targets will be defined during technical planning.

## 7. User Stories and Acceptance Criteria

### User Story 1: Employee Profile Management

**As an HR Staff member,** I want to create and update employee profiles so that employee information can be maintained in one system.

Acceptance criteria:

- Authorized HR Staff can create a new employee profile.
- Required fields must be validated before saving.
- The new employee record appears in the employee list.
- Authorized HR Staff can edit existing employee information.
- Unauthorized users cannot access restricted employee management functions.

### User Story 2: Leave Application

**As an Employee,** I want to submit a leave application so that I can formally request time off.

Acceptance criteria:

- An authenticated employee can open the leave application form.
- The employee can provide the required leave details.
- The system validates required fields.
- A successful submission is saved with a pending status.
- The employee can view the submitted request and its status.

### User Story 3: Leave Approval

**As an HR Staff member,** I want to review leave applications so that I can approve or reject employee requests.

Acceptance criteria:

- Authorized HR Staff can view submitted leave requests.
- HR Staff can approve or reject a pending request.
- The system updates the request status.
- The employee can view the updated status.
- Unauthorized users cannot approve or reject requests.

### User Story 4: Attendance Monitoring

**As an HR Staff member,** I want to view employee attendance records so that I can monitor attendance information.

Acceptance criteria:

- Authorized HR Staff can access attendance records.
- Records display the relevant employee and attendance date.
- The system provides a clear way to identify available attendance information.
- Employees can only view their own attendance records if that feature is enabled.

## 8. Project Constraints

- The project has an initial target duration of eight weeks.
- Development resources and team composition are not yet finalized.
- The technology stack has not yet been selected.
- The initial release is limited to the agreed MVP scope.
- Development and deployment choices will depend on technical feasibility and resource availability.

## 9. Project Assumptions

- A development team will be assembled or assigned.
- Stakeholders will be available to review and validate requirements.
- Developers will help estimate implementation effort.
- Synthetic data will be used for development and demonstration.
- The project will use GitHub for source control and documentation and Trello for task tracking.

## 10. MoSCoW Prioritization

The project will use MoSCoW prioritization:

- **Must Have:** Essential features required for the initial MVP.
- **Should Have:** Important features that may be scheduled after essential functionality.
- **Could Have:** Useful enhancements included if time and resources permit.
- **Won't Have (for this release):** Features excluded from the initial release.

### Initial MVP Priorities

| Feature | Priority |
|---|---|
| Authentication and logout | Must Have |
| Role-based access | Must Have |
| Employee profile management | Must Have |
| Department and position management | Must Have |
| Attendance management | Must Have |
| Leave application and approval | Must Have |
| Dashboard summaries | Should Have |
| Basic reports | Should Have |
| Report export | Could Have |
| Payroll processing | Won't Have |
| Biometric integration | Won't Have |
| Native mobile application | Won't Have |

## 11. Requirements Validation Process

The requirements will be validated through the following activities:

1. Review the business requirements with the Project Owner or Product Owner.
2. Confirm user roles and access permissions.
3. Review functional and non-functional requirements.
4. Clarify ambiguous requirements with relevant stakeholders.
5. Review technical feasibility with developers.
6. Prioritize requirements for the initial Product Backlog.
7. Define and confirm acceptance criteria.
8. Record approval and update the document when changes are agreed.

## 12. Change Management

Any proposed requirement change should be documented and reviewed for its impact on:

- Project scope
- Schedule
- Development effort
- Technical design
- Testing requirements

Approved changes will be reflected in the requirements document and Product Backlog.

## 13. Review and Approval

This document is an initial draft and is not yet an approved final specification.

| Role | Name | Approval / Date |
|---|---|---|
| Project Manager | Project Lead | Pending |
| Product Owner | To be assigned | Pending |
| HR Representative | To be assigned | Pending |
| Technical Lead / Developer | To be assigned | Pending |

---

**Prepared for:** Portfolio Project  
**Document:** Requirements Gathering Document v1.0  
**Status:** Draft – For Requirements Validation
