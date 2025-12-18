# Lesson 12 – Scatter Diagrams for Root Cause Analysis  
**Project+ (PK0-005) | Topic 12A – Resolve Issues**

---

## Why Scatter Diagrams Appear in Issue Management

In Lesson 12, scatter diagrams are introduced **immediately after Root Cause Analysis**.  
This is intentional.

Scatter diagrams are **not statistics tools for analysts** — they are **investigation tools for project managers**.

Their purpose is to help a PM answer one key question:

> **“Are two factors related strongly enough that one might be contributing to an issue?”**

They help narrow down **where to investigate**, not decide **what the root cause is**.

---

## Project Context (Used for All Charts)

**Project:** Customer Analytics Dashboard (Cloud-based)  
**Phase:** Mid-project execution  
**Problem:** Defects are higher than expected  

The PM suspects multiple possible causes and uses scatter diagrams to test assumptions.

---

## Scatter Chart 1 – Positive Correlation  
### *Requirement Volatility vs Defects*

### What is being compared
- **X-axis:** Unplanned requirements (%) per sprint  
- **Y-axis:** Defects found per sprint  

### What the chart shows
- As unplanned requirements increase, defects also increase
- The data points form an upward trend
- **R² value is high**, indicating a strong relationship

### Interpretation
This suggests a **positive correlation** between requirement volatility and defects.

This means:
- Projects with more requirement changes tend to experience more defects
- Requirement instability is a **likely contributing factor**

### What this does NOT prove
- It does NOT prove that requirement changes *cause* defects
- It does NOT identify the exact root cause

### Why a PM uses this
To justify deeper investigation into:
- Requirements management
- Change control effectiveness
- Stakeholder behavior

---

## Scatter Chart 2 – Negative Correlation  
### *Automation Coverage vs Defects*

### What is being compared
- **X-axis:** Automated test coverage (%)  
- **Y-axis:** Defects found  

### What the chart shows
- As automation coverage increases, defects decrease
- The data forms a downward trend
- **R² value is high**, showing a strong relationship

### Interpretation
This shows a **negative correlation**:
- More automation is associated with fewer defects

### What this does NOT prove
- Automation alone fixes quality issues
- Increasing automation guarantees defect reduction

### Why a PM uses this
To support decisions such as:
- Investing in automated testing
- Prioritizing test automation work
- Defending automation budget requests

---

## Scatter Chart 3 – No Correlation  
### *Meetings vs Defects*

### What is being compared
- **X-axis:** Number of meetings per sprint  
- **Y-axis:** Defects found  

### What the chart shows
- Data points are scattered randomly
- No visible trend
- **R² ≈ 0**, indicating no relationship

### Interpretation
There is **no measurable relationship** between meetings and defects.

### Why this matters
This disproves a common management assumption:
> “More meetings will improve quality.”

### PM takeaway
- Meetings are not a root cause of defects
- Increasing meetings will not fix the issue
- Time should be spent elsewhere

---

## Understanding R² (R-Squared)

**R² measures relationship strength, not causation.**

| R² Value | Meaning |
|--------|--------|
| 0.0 | No relationship |
| Low (≈0.3) | Weak relationship |
| Medium (≈0.5) | Moderate relationship |
| High (≥0.8) | Strong relationship |

Even with a high R²:
- Causation is **not guaranteed**
- Further analysis is required

---

## Why Project Managers Use Scatter Diagrams

Project managers use scatter diagrams to:

- Validate or challenge assumptions
- Focus Root Cause Analysis
- Avoid emotional or anecdotal decisions
- Support prioritization and escalation discussions

They answer:
> “Is this factor worth investigating further?”

They do **not** answer:
> “What is the root cause?”

---

## Exam Key Takeaways (Project+)

- Scatter diagrams show **correlation only**
- Correlation does **not** imply causation
- R² indicates **strength of relationship**
- Scatter diagrams support Root Cause Analysis
- They are used during the **Analyze the Issue** phase

---

## Summary

Scatter diagrams help project managers:
- Reduce guesswork
- Focus investigation
- Avoid chasing false causes

They are an **evidence-based starting point**, not a final answer.

---

**End of Lesson 12 – Scatter Diagrams & Root Cause Analysis**

