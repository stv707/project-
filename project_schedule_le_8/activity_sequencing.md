# Lesson 8 – WBS Sequencing Example  
Sequence the Activities (Mobile App Project)

---

## Context: Why Sequencing Matters

A Work Breakdown Structure (WBS) defines **what must be delivered**.  
Sequencing defines **the logical order** in which those deliverables must occur.

A schedule without sequencing is just a list.  
Sequencing turns a list into a **plan**.

---

## Project Scenario

**Project:** Mobile Fitness Tracking App  
**Platforms:** iOS and Android  
**Delivery Model:** Agile with fixed launch date  
**Key Constraint:** App Store submission must occur before marketing launch

The PM must determine **which deliverables depend on others**, and **which can occur in parallel**.

---

## Step 1: Identify WBS Work Packages

From the WBS, the PM selects the relevant **work packages** that drive the schedule:

```

A. Project Kickoff Completed
B. UX/UI Design Approved
C. Backend APIs Available
D. Mobile App Core Features Implemented
E. Integration Testing Completed
F. Security Review Completed
G. App Store Submission Completed
H. Production Release Completed

```

These are **deliverables**, not tasks.

---

## Step 2: Identify Logical Dependencies

The PM now asks one question repeatedly:

> “What must be finished before this can begin?”

---

### Dependency Analysis

| ID | Deliverable | Must Follow |
|---|---|---|
| A | Project Kickoff Completed | None |
| B | UX/UI Design Approved | A |
| C | Backend APIs Available | A |
| D | Mobile App Core Features Implemented | B, C |
| E | Integration Testing Completed | D |
| F | Security Review Completed | E |
| G | App Store Submission Completed | F |
| H | Production Release Completed | G |

This table alone explains **80% of scheduling logic**.

---

## Step 3: Identify Dependency Types

Now we classify **why** the dependency exists.

---

### Mandatory Dependencies (Hard Logic)

These cannot be bypassed.

- Backend APIs must exist **before** integration testing
- Security review must complete **before** app submission
- App Store approval must occur **before** public release

These are driven by:
- Technical reality
- Regulations
- External constraints

---

### Discretionary Dependencies (Soft Logic)

These are **choices**, not laws.

- Waiting for full UI approval before starting backend work
- Completing all features before starting any testing

A skilled PM challenges these:
> “Can we test incrementally instead of waiting?”

---

## Step 4: Sequential Relationships (FS, SS, FF, SF)

Now the PM defines **how activities overlap**.

---

### Finish-to-Start (FS) – Most Common

```

Backend APIs Available → Integration Testing Completed

```

Testing cannot start until APIs exist.

---

### Start-to-Start (SS)

```

Backend Development Starts ↔ Mobile Development Starts

```

Both teams begin work after kickoff, even though neither finishes first.

---

### Finish-to-Finish (FF)

```

Mobile Feature Completion ↔ Integration Testing Completion

```

Testing finishes only when development finishes.

---

### Start-to-Finish (SF) – Rare, but real

```

Legacy App Support → New App Live

```

Support for the old app ends only after the new app starts.

---

## Step 5: Build the Sequence Flow

Putting it together, the **logical sequence** looks like this:

```

A → (B + C) → D → E → F → G → H

```

Meaning:
- Kickoff enables parallel design and backend work
- Both must complete before core features finalize
- Testing, security, and release follow in strict order

This sequence protects **quality and compliance**, not just speed.

---

## Step 6: Identify Parallel Opportunities

The PM looks for safe overlap to reduce duration:

| Parallel Activities | Why It Works |
|---|---|
| UX Design & Backend Development | Independent skills |
| Mobile Dev & Backend Dev | API contracts defined early |
| Security Prep & Testing | Early findings reduce rework |

Parallelism increases speed **only when dependencies are respected**.

---

## Step 7: Validate with the Team

The PM reviews the sequence with:
- Developers
- QA
- Security
- Operations

Key validation questions:
- Is any dependency assumed but not required?
- Is anything missing?
- Where would rework occur if assumptions are wrong?

This prevents **schedule optimism**.

---

## Common Sequencing Mistakes (Real World)

1. Treating preferences as mandatory dependencies  
2. Sequencing everything FS “to be safe”  
3. Ignoring external dependencies (App Store, vendors)  
4. Sequencing tasks instead of deliverables  
5. Forgetting operational handover dependencies  

All five cause delays.

---

## Reflection Questions for Students

1. Which dependencies in this example are **mandatory vs discretionary**?
2. Where could the PM safely introduce overlap?
3. Which dependency is most risky if violated?
4. How would sequencing change if the launch date were flexible?
5. What dependency exists that is **outside the PM’s control**?

---

## Key Lesson

Sequencing is not about drawing arrows.

It is about **understanding reality**,  
**challenging assumptions**,  
and **protecting outcomes**.

A good PM sequences work to enable success —  
not to create the illusion of control.

---
