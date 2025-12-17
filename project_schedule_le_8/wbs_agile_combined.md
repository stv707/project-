# WBS + Agile Combined Example  
Mobile App Development Project

---

## Why This Example Exists

Many people incorrectly believe:
- WBS = Waterfall / Non-IT
- Agile = Software / No WBS

In reality, **successful software projects use BOTH**:
- **WBS** to define and control scope
- **Agile backlog** to execute and adapt

This example shows how they coexist in a **single mobile app project**.

---

## Project Context

**Project:** Mobile Fitness Tracking App  
**Platforms:** iOS & Android  
**Delivery Approach:** Hybrid (Predictive + Agile)  
**Launch Constraint:** Fixed marketing launch date

---

## Step 1: Use WBS to Define Project Scope (The “What”)

The Project Manager starts with a **WBS** to answer:

> “What must exist before we declare this project complete?”

### Level 1 – Project

```

1.0 Mobile App Delivered

```

### Level 2 – Major Deliverables (WBS)

```

1.1 Project Governance Established
1.2 Mobile App Frontend Delivered
1.3 Backend Services Delivered
1.4 Integrations Completed
1.5 Security & Compliance Approved
1.6 Testing & Quality Completed
1.7 App Released
1.8 Operations Handover Completed

```

➡ This WBS:
- Sets **scope boundaries**
- Prevents “forgotten work”
- Is relatively stable

---

## Step 2: Stop WBS at the Right Level

Notice what the PM **does NOT do**:
- No user stories
- No UI tasks
- No technical subtasks

Why?
Because WBS answers **WHAT must be delivered**, not **HOW it will be built**.

That’s where Agile comes in.

---

## Step 3: Map WBS Deliverables to Agile Epics

Each **WBS Level 2 deliverable** becomes one or more **Agile Epics**.

| WBS Deliverable | Agile Epic |
|---|---|
| 1.2 Mobile App Frontend Delivered | User Experience & UI |
| 1.3 Backend Services Delivered | Core Backend Services |
| 1.4 Integrations Completed | External Integrations |
| 1.5 Security & Compliance Approved | Security & Privacy |
| 1.6 Testing & Quality Completed | Quality Assurance |

➡ WBS provides **structure**  
➡ Agile provides **flexibility**

---

## Step 4: Break Epics into Features

### Epic: User Experience & UI

**Features:**
- User registration & login
- Activity tracking screens
- User profile management
- Accessibility support

These features **can change**, but the epic (frontend delivered) does not.

---

## Step 5: Convert Features into User Stories

### Feature: User Registration

**User Stories:**
- As a new user, I want to register using email
- As a user, I want password strength validation
- As a user, I want clear error messages

These stories are:
- Small
- Testable
- Negotiable

---

## Step 6: Tasks Live ONLY at the Team Level

For one user story, tasks might be:

- Design registration UI
- Implement API endpoint
- Add validation logic
- Write unit tests

⚠️ These tasks:
- Are NOT in the WBS
- Are NOT shown to stakeholders
- Change frequently

---

## Step 7: Execution Flow (How It Actually Runs)

### Governance & Scope
- WBS defines **what “done” means**
- Sponsor approves scope at WBS level

### Delivery
- Agile backlog drives sprint planning
- Team pulls user stories into sprints
- Tasks evolve daily

### Control
- PM tracks progress against **WBS deliverables**
- Team tracks progress via **burndown & velocity**

Both views are valid — for different audiences.

---

## Step 8: Why This Hybrid Model Works

### Without WBS
- Backlog grows endlessly
- Scope creep is invisible
- “Almost done” lasts forever

### Without Agile
- Requirements freeze too early
- Late feedback causes rework
- Team morale drops

Using both:
- WBS controls **scope**
- Agile controls **execution**

---

## Real-Life Example of Interaction

- Stakeholder asks:  
  > “Are we on track to deliver the mobile app?”

PM answers using **WBS**:
- Frontend: 80% complete
- Backend: 75% complete
- Security: in progress

- Team asks:  
  > “What do we work on next sprint?”

Product Owner answers using **Agile backlog**:
- Select top-priority stories

Same project. Two lenses.

---

## Key Takeaway for Students

- WBS defines **project completion**
- Agile defines **value delivery**
- They are not competitors
- They are partners

If you remove either one,  
you create blind spots.

---

## Final Reflection Question

> If your backlog looks healthy but you cannot clearly say  
> what “project complete” means — what are you missing?

Think carefully.
---
