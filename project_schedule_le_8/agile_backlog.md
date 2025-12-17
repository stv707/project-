
# Lesson 8 – Agile Backlog Example  
Mobile App Development Project

---

## Context: Why Agile Backlogs Exist

An agile backlog represents **evolving work**, not fixed scope.

While a WBS defines *what must be delivered* for the project,  
the **agile backlog defines how value is delivered incrementally**.

This example demonstrates how work is structured from **Epic → Feature → User Story → Task**.

---

## Project Overview

**Project Name:** Mobile Fitness Tracking App  
**Delivery Model:** Agile (Scrum)  
**Sprint Length:** 2 weeks  
**Team Size:** 6 members

---

## Backlog Hierarchy Overview

```

Epic
└── Feature
└── User Story
└── Tasks

```

- **Epic**: Large business objective
- **Feature**: Capability that delivers value
- **User Story**: Small, testable unit of value
- **Task**: Technical steps to complete a story

---

## Epic 1 – User Account Management

### Epic Description
Enable users to securely register, log in, and manage their account.

---

### Feature 1.1 – User Registration

#### Feature Description
Allow new users to create an account using email and password.

---

#### User Story 1.1.1 – User Registration via Email

**User Story:**  
> As a new user,  
> I want to register using my email address,  
> so that I can access the app securely.

**Acceptance Criteria:**
- User can submit registration form
- Password meets security rules
- Confirmation message displayed

---

##### Tasks
- Design registration UI screen
- Implement email validation logic
- Implement backend registration API
- Store user credentials securely
- Write unit tests
- Perform basic security checks

---

### Feature 1.2 – User Login

#### User Story 1.2.1 – User Login

**User Story:**  
> As a registered user,  
> I want to log in using my credentials,  
> so that I can access my fitness data.

**Acceptance Criteria:**
- Login succeeds with valid credentials
- Error shown for invalid credentials
- Session is securely maintained

---

##### Tasks
- Create login screen UI
- Implement authentication API
- Handle session tokens
- Add error handling
- Write automated tests

---

## Epic 2 – Activity Tracking

### Epic Description
Enable users to record and view fitness activities.

---

### Feature 2.1 – Record Activity

#### User Story 2.1.1 – Record Workout Activity

**User Story:**  
> As a user,  
> I want to record my workout activity,  
> so that I can track my fitness progress.

**Acceptance Criteria:**
- User can enter activity type and duration
- Activity is saved successfully
- Confirmation is displayed

---

##### Tasks
- Design activity input screen
- Implement activity data model
- Create backend API endpoint
- Persist activity data
- Write functional tests

---

### Feature 2.2 – View Activity History

#### User Story 2.2.1 – View Activity History

**User Story:**  
> As a user,  
> I want to view my past activities,  
> so that I can monitor my progress over time.

**Acceptance Criteria:**
- Activities displayed in chronological order
- Data loads within acceptable time
- Empty state handled gracefully

---

##### Tasks
- Design activity list UI
- Fetch activity data from backend
- Implement pagination or lazy loading
- Add loading and error states
- Perform UI testing

---

## Epic 3 – Notifications and Reminders

### Feature 3.1 – Workout Reminders

#### User Story 3.1.1 – Receive Workout Reminder

**User Story:**  
> As a user,  
> I want to receive workout reminders,  
> so that I stay consistent with my fitness routine.

**Acceptance Criteria:**
- User can enable or disable reminders
- Notifications sent at configured times
- Notifications work on iOS and Android

---

##### Tasks
- Add reminder settings UI
- Integrate push notification service
- Configure notification schedules
- Test notifications on devices

---

## How This Backlog Is Used

- **Product Owner** prioritizes Epics and Features
- **Team** selects User Stories for each sprint
- **Tasks** are created and adjusted by the team
- Backlog evolves as feedback is received

The backlog is **never final**.

---

## WBS vs Agile Backlog (Quick Reminder)

| WBS | Agile Backlog |
|---|---|
| Fixed scope | Evolving scope |
| Deliverable-focused | Value-focused |
| Created during planning | Maintained throughout project |
| Used by PM | Used by Product Owner & Team |

---

## Reflection Questions for Students

1. Why are tasks **not** visible to stakeholders?
2. Can a User Story belong to more than one Epic?
3. What happens if tasks change but the story remains the same?
4. Which level of the backlog changes most frequently?
5. Why is it dangerous to treat the backlog as a fixed plan?

---

## Key Takeaway

A backlog is not a to-do list.  
It is a **value delivery mechanism**.

The higher you go in the hierarchy,  
the more stable the work becomes.

The lower you go,  
the more flexibility the team needs.

---
