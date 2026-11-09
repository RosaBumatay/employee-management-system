# Employee Management System (EMS)
## Product Backlog

**Document Version:** 1.0  
**Document Status:** Initial Draft – For Refinement  
**Product Owner:** To be assigned  
**Project Manager:** Project Lead  
**Methodology:** Agile / Scrum

---

## 1. Purpose

The Product Backlog is the prioritized list of features, improvements, and work items proposed for the Wrio Byte Employee Management System.

It provides a shared reference for the Product Owner and development team when discussing requirements, estimating effort, planning sprints, and tracking product progress.

This is an initial backlog. Items, priorities, estimates, and sprint assignments must be reviewed with the development team before implementation.

## 2. Product Goal

Develop a functional web-based Employee Management System that centralizes employee records and supports basic HR processes, including department management, attendance monitoring, leave management, and reporting.

## 3. Priority Definitions

- **Must Have:** Essential for the initial MVP.
- **Should Have:** Important, but may follow essential features.
- **Could Have:** Useful enhancement if time and resources allow.
- **Won't Have:** Excluded from the initial release.

## 4. Product Backlog Items

| ID | Epic / Feature | Product Backlog Item | Priority | Initial Status |
|---|---|---|---|---|
| PB-01 | Project Setup | Establish application repository and development structure | Must Have | Not Started |
| PB-02 | Authentication | Implement user login and logout | Must Have | Not Started |
| PB-03 | User Management | Create and manage user accounts | Must Have | Not Started |
| PB-04 | Access Control | Implement Administrator, HR Staff, and Employee roles | Must Have | Not Started |
| PB-05 | Employee Management | Create employee profiles | Must Have | Not Started |
| PB-06 | Employee Management | View and search employee records | Must Have | Not Started |
| PB-07 | Employee Management | Update employee information | Must Have | Not Started |
| PB-08 | Employee Management | Delete or deactivate employee records according to approved policy | Should Have | Not Started |
| PB-09 | Organization Management | Create and manage departments | Must Have | Not Started |
| PB-10 | Organization Management | Manage employee positions | Must Have | Not Started |
| PB-11 | Attendance | Record employee attendance | Must Have | Not Started |
| PB-12 | Attendance | View and monitor attendance records | Must Have | Not Started |
| PB-13 | Leave Management | Submit employee leave applications | Must Have | Not Started |
| PB-14 | Leave Management | Review and approve or reject leave applications | Must Have | Not Started |
| PB-15 | Leave Management | Display leave application status | Must Have | Not Started |
| PB-16 | Dashboard | Display employee and HR summary information | Should Have | Not Started |
| PB-17 | Reporting | Generate basic employee and attendance reports | Should Have | Not Started |
| PB-18 | Reporting | Export selected reports or records | Could Have | Not Started |
| PB-19 | Quality Assurance | Test role-based permissions and access restrictions | Must Have | Not Started |
| PB-20 | Quality Assurance | Execute functional testing and document defects | Must Have | Not Started |
| PB-21 | Documentation | Prepare basic user documentation | Should Have | Not Started |
| PB-22 | Deployment | Prepare a demonstrable application deployment or local setup | Must Have | Not Started |

## 5. Initial User Stories

### PB-02: User Login

**User Story:** As an authorized user, I want to log in securely so that I can access the system according to my role.

**Acceptance Criteria:**
- Users can submit valid login credentials.
- Invalid credentials produce an appropriate error.
- Successful login provides access to authorized features.
- Users can log out.

### PB-05: Create Employee Profile

**User Story:** As an HR Staff member, I want to create an employee profile so that employee information is stored centrally.

**Acceptance Criteria:**
- Authorized HR Staff can access the employee creation form.
- Required fields are validated.
- A valid employee record can be saved.
- The saved employee appears in the employee list.

### PB-11: Record Attendance

**User Story:** As an authorized user, I want to record employee attendance so that attendance information can be monitored.

**Acceptance Criteria:**
- Attendance records can be entered using the approved attendance process.
- Each record is associated with an employee and date.
- Required information is validated.
- Authorized HR Staff can view attendance records.

### PB-13: Submit Leave Application

**User Story:** As an Employee, I want to submit a leave application so that I can formally request time off.

**Acceptance Criteria:**
- An authenticated employee can submit a leave request.
- Required leave details are validated.
- Successful submissions are stored with Pending status.
- The employee can view the request status.

### PB-14: Process Leave Application

**User Story:** As an HR Staff member, I want to review leave applications so that I can approve or reject requests.

**Acceptance Criteria:**
- Authorized HR Staff can view pending requests.
- HR Staff can approve or reject a request.
- The system records the updated status.
- The employee can view the result.

## 6. Proposed Sprint Grouping

The following grouping is a preliminary planning proposal, not a confirmed commitment.

| Sprint | Proposed Focus | Example Backlog Items |
|---|---|---|
| Sprint 1 | Core employee management | PB-01 to PB-10 |
| Sprint 2 | Attendance and leave management | PB-11 to PB-15 |
| Sprint 3 | Dashboard, reports, and quality improvements | PB-16 to PB-22 |

Sprint scope must be validated against developer capacity, technical dependencies, and estimates.

## 7. Estimation and Refinement

Effort estimates have not yet been assigned.

During backlog refinement, the development team should:

1. Review each backlog item.
2. Ask questions to clarify requirements.
3. Identify technical dependencies.
4. Break large items into smaller tasks.
5. Estimate effort using an agreed method, such as story points.
6. Confirm acceptance criteria.
7. Recommend priority adjustments where necessary.

The Product Owner is responsible for backlog ordering and priority decisions, with input from the Project Manager and development team.

## 8. Definition of Ready

A backlog item may be considered ready for sprint planning when:

- Its purpose is clear.
- The user story or requirement is understandable.
- Acceptance criteria are documented.
- Dependencies are identified.
- The item is sufficiently small to estimate and complete within a sprint.
- The team has enough information to begin work.

## 9. Definition of Done

A backlog item may be considered complete when:

- The agreed functionality is implemented.
- Acceptance criteria are met.
- Relevant tests have been completed.
- Identified critical defects are resolved.
- Code has been reviewed according to the team's agreed process.
- Documentation is updated where needed.
- The Product Owner accepts the completed work.

The team should agree on any additional quality requirements before development begins.

## 10. Backlog Maintenance

The Product Backlog will be reviewed and updated throughout the project.

Changes may include:

- Adding new requirements.
- Updating priorities.
- Splitting large items.
- Removing duplicate or obsolete items.
- Revising acceptance criteria.
- Updating estimates and status.

## 11. Approval

| Role | Name | Status |
|---|---|---|
| Product Owner | To be assigned | Pending |
| Project Manager | Project Lead | Pending |
| Development Team | To be assigned | Pending |

---

**Prepared for:** Portfolio Project  
**Document:** Product Backlog v1.0  
**Status:** Initial Draft – For Refinement
