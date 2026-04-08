# Evaluating & Prioritising Backlog Items (#13)

## Overview

This task focuses on evaluating and prioritising backlog items from the Focus Bear Mac App roadmap using a structured prioritisation framework.

---

## Goal

To determine which backlog items should be prioritised based on:

- User impact
- Business value
- Effort required

---

## Why This Is Important

Prioritisation ensures:

- High-impact problems are solved first
- Engineering resources are used efficiently
- The team avoids working on low-value features

---

## Research & Learn

### 1. Common Backlog Prioritisation Frameworks

#### RICE (Used in this task)

- **Reach** → Number of users affected
- **Impact** → Level of improvement (low → high)
- **Confidence** → Certainty of estimates
- **Effort** → Development time/complexity

Best for: Data-driven prioritisation

---

#### MoSCoW Method

- **Must have** → Critical for release
- **Should have** → Important but not urgent
- **Could have** → Nice to have
- **Won’t have** → Not needed now

Best for: Roadmap planning and stakeholder communication

---

#### Kano Model

- **Basic Needs** → Expected features (must work)
- **Performance Needs** → Better performance = higher satisfaction
- **Delighters** → Unexpected features that impress users

Best for: Understanding user satisfaction vs expectations

---

### 2. How PMs Balance Business, Users, and Technical Feasibility

Product Managers balance three key factors:

- **User Needs**
    - Pain points from feedback and support tickets
    - Features improving experience and retention

- **Business Goals**
    - Revenue impact (e.g., subscription issues)
    - Growth, activation, and retention metrics

- **Technical Feasibility**
    - Engineering effort and complexity
    - Dependencies, risks, and maintainability

Effective prioritisation lies at the intersection of these three.

---

### 3. Factors That Determine Prioritisation

- **User Impact** → Number of users affected and severity
- **Business Value** → Revenue, retention, strategic alignment
- **Risk & Severity** → Critical bugs vs minor improvements
- **Effort vs Value** → High impact with low effort preferred
- **Frequency** → Recurring issues from users
- **Dependencies** → Blocking or enabling other features

---

## Framework Used: RICE Model

**RICE = Reach × Impact × Confidence ÷ Effort**

---

## Selected Backlog Items

### 1. Time Parsing Unit Tests (#1627)

- Reach: 9
- Impact: 2.5
- Confidence: 85%
- Effort: 3

**RICE Score:** 6.38

**Justification:**
A foundational component used across multiple features. Fixing this reduces widespread scheduling errors with relatively low effort.

---

### 2. Custom Blocking Schedule Unit Tests (#1624)

- Reach: 9
- Impact: 3
- Confidence: 90%
- Effort: 4

**RICE Score:** 6.08

**Justification:**
Core functionality that protects users from distractions. High risk if incorrect, directly impacting trust and product value.

---

### 3. Routine/Habit Scheduling Unit Tests (#1626)

- Reach: 8
- Impact: 2.5
- Confidence: 85%
- Effort: 5

**RICE Score:** 3.40

**Justification:**
Important for user engagement and habit consistency, but slightly less critical than blocking functionality.

---

### 4. Native Installer Integration (#2552)

- Reach: 8
- Impact: 3
- Confidence: 80%
- Effort: 5

**RICE Score:** 3.84

**Justification:**
Improves onboarding experience by reducing friction during installation, but requires cross-platform effort.

---

### 5. Focus Alignment Score Tests (#1628)

- Reach: 6
- Impact: 2
- Confidence: 80%
- Effort: 4

**RICE Score:** 2.40

**Justification:**
Enhances feedback accuracy but has lower impact compared to core system reliability tasks.

---

## Final Priority Ranking

| Rank | Item                                   | RICE Score |
| ---- | -------------------------------------- | ---------- |
| 1    | Time Parsing Unit Tests (#1627)        | 6.38       |
| 2    | Custom Blocking Schedule Tests (#1624) | 6.08       |
| 3    | Native Installer Integration (#2552)   | 3.84       |
| 4    | Routine/Habit Scheduling Tests (#1626) | 3.40       |
| 5    | Focus Alignment Score Tests (#1628)    | 2.40       |

---

## Reflection

### 1. What was the hardest decision?

Balancing **user-facing improvements vs backend reliability** was the most challenging. While installer integration improves onboarding, backend issues like time parsing affect multiple features and have broader impact.

---

### 2. How does prioritisation impact the development team?

- Helps the team focus on high-value tasks
- Reduces wasted effort on low-impact features
- Improves planning and workload distribution
- Minimises context switching

---

### 3. What trade-offs were made?

- Prioritised **system stability over new features**
- Selected **high-impact, low-effort tasks first**
- Delayed lower-impact improvements (e.g., scoring logic)

---

## Key Takeaways

- Prioritisation is critical for maximising product value
- Foundational systems often deliver the highest impact
- Structured frameworks (like RICE) support objective decision-making
- PMs must continuously balance user needs, business goals, and technical constraints

---
