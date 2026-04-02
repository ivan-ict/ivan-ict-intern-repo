# Understanding How the Backlog Works at Focus Bear

**Milestone:** Backlog Management & Prioritisation
**Project:** Mac App Roadmap

---

## 1. What is a Product Backlog vs Roadmap?

### Product Backlog

The product backlog is a **prioritised list of work items** that the team may work on in the future.
It includes:

- Feature requests
- Bug reports
- Improvements
- Technical debt
- Research tasks

The backlog is **detailed and task-level**, and items are regularly updated, refined, and prioritised.

### Roadmap

The product roadmap is a **high-level plan** that shows the overall product direction and major goals over time (e.g., This month, This quarter, Long term).

| Roadmap         | Backlog        |
| --------------- | -------------- |
| High-level      | Detailed       |
| Strategic       | Tactical       |
| Time-based      | Priority-based |
| Shows direction | Shows tasks    |

**Summary:**
Roadmap = where we are going
Backlog = what we are working on

---

## 2. Types of Items in the Backlog

From reviewing the GitHub Project board, backlog items generally fall into these categories:

| Type            | Description                | Example                      |
| --------------- | -------------------------- | ---------------------------- |
| Feature Request | New functionality          | New onboarding flow          |
| Bug             | Something not working      | App crashes on startup       |
| Improvement     | Enhance existing feature   | Improve UI layout            |
| Technical Debt  | Code or system improvement | Refactor sync system         |
| Research        | Investigation tasks        | Research notification system |

---

## 3. Backlog Structure in GitHub Projects (Focus Bear)

Focus Bear uses **GitHub Projects** to manage backlog items with the following key fields:

| Field               | Purpose                  |
| ------------------- | ------------------------ |
| Status              | Shows stage of work      |
| Priority            | Based on RICE score      |
| Effort              | Estimated work size      |
| RICE Score          | Used to prioritise tasks |
| Sub-issues progress | Progress tracking        |

### Status Workflow (Important)

Backlog items move through these stages:

1. **Unprioritised** – Idea or task added but not prioritised yet
2. **Needs clarification** – More information required
3. **This month / This quarter / Long term** – Added to roadmap timeline
4. **In Progress** – Developer is working on it
5. **For Dev QA** – Ready for developer testing
6. **Ready for QA** – Ready for QA team
7. **QA in Progress** – QA testing
8. **QA Failed** – Issues found
9. **QA Passed/Done** – Completed

This shows a **clear workflow from idea → development → testing → done**.

---

## 4. Backlog Management Tools Used

Focus Bear uses the following tools:

| Tool            | Purpose                            |
| --------------- | ---------------------------------- |
| GitHub Issues   | Store backlog items                |
| GitHub Projects | Manage workflow & prioritisation   |
| RICE Scoring    | Prioritisation method              |
| Discord         | Customer feedback & bug reports    |
| PostHog         | Product analytics & user behaviour |

---

## 5. How Backlog Items Move Through the Workflow

### Workflow Summary

| Stage                | Description                                          |
| -------------------- | ---------------------------------------------------- |
| Idea / Feedback      | Feature idea, bug report, or improvement is reported |
| GitHub Issue Created | Task is added to backlog                             |
| Unprioritised        | Waiting for review and scoring                       |
| Needs Clarification  | More details required                                |
| RICE Scoring         | PM assigns Reach, Impact, Confidence, Effort         |
| Roadmap Assignment   | This Month / This Quarter / Long Term                |
| In Progress          | Developer working on task                            |
| Dev QA               | Developer testing                                    |
| Ready for QA         | Ready for QA team                                    |
| QA in Progress       | QA testing                                           |
| QA Passed            | Task completed                                       |
| Release              | Included in next app version                         |

---

## 6. Reflection

### What did you notice about how the backlog is organised?

The backlog is organised using GitHub Projects with clear fields such as Status, Priority, Effort, and RICE Score. The workflow is structured and shows the full lifecycle of a task from idea to completion. The RICE scoring system is used to prioritise tasks objectively.

### What are the biggest challenges in backlog management?

- Too many unprioritised tasks
- Some tasks may lack clear descriptions
- Prioritisation requires accurate RICE scoring
- Communication between product, development, and QA is necessary to move tasks forward

### How would you improve the backlog?

- Ensure every issue has a clear description and acceptance criteria
- Regular backlog grooming sessions
- Recalculate RICE scores regularly
- Group tasks by feature area (e.g., onboarding, analytics, UI)
- Add labels for bug / feature / improvement

---

## 7. Summary

The Focus Bear backlog is managed in GitHub Projects and prioritised using the RICE framework. Tasks move through a structured workflow from unprioritised ideas to development, QA, and completion. This system helps the team prioritise high-impact work and manage product development efficiently.
