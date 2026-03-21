# Feature One-Pager – Focus Bear

## Milestone: Writing Clear Feature Requirements

---

## Feature Name

**Focus Session Streak Tracker**

---

## Problem Statement

Many users start focus sessions but struggle to maintain consistency over time. They may use the app for a few days and then stop. Focus Bear currently helps users focus, but there is limited motivation for long-term habit building.

We need a feature that encourages users to maintain daily focus sessions and build long-term productivity habits.

---

## Target Users

- Students who want to build consistent study habits
- Remote workers who want to maintain daily deep work sessions
- People who are trying to reduce distractions and improve productivity
- Existing Focus Bear users who want to build long-term habits

---

## User Stories & Scenarios

**User Story 1:**
As a user, I want to see my daily focus streak so that I feel motivated to maintain my focus habit.

**User Story 2:**
As a user, I want to receive a reminder when my streak is about to break so that I don’t lose my progress.

**User Story 3:**
As a user, I want to see my longest streak so that I feel a sense of achievement.

**Scenario Example:**
A student uses Focus Bear every day to study. After completing at least one focus session per day for 5 days, the app shows a “5-day streak”. If the student does not complete a focus session the next day, the streak resets. This motivates the student to maintain daily usage.

---

## Wireframe / User Journey (Description)

**User Journey:**

1. User opens Focus Bear dashboard
2. User sees current streak (e.g., 🔥 5-day streak)
3. User starts a focus session
4. User completes the session
5. Streak increases to 6 days
6. If user does not complete a session, streak resets

[Wireframe link here](https://www.figma.com/proto/H5vlFujzumkmZzViivgxCm/Github-Repo--9?node-id=1-6&p=f&t=YGrKJ1kGYUlEePJd-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1)

Suggested wireframe elements:

- Streak counter on dashboard
- Progress bar for daily focus
- Reminder notification
- “Longest Streak” statistic

---

## Acceptance Criteria

- The system tracks daily focus session completion
- A streak increases when a user completes at least one focus session per day
- The streak resets if the user misses a day
- The dashboard displays:
    - Current streak
    - Longest streak
- The system sends a reminder notification if the user has not completed a focus session by a certain time (e.g., 7 PM)
- The feature works on both desktop and mobile versions

---

## Open Questions

- What is the minimum focus time required to count as a streak? (e.g., 25 minutes?)
- What time should the reminder notification be sent?
- Should users be allowed a “grace day” without losing their streak?
- Should streak rewards or badges be included?
- Where should the streak be displayed on the dashboard?

---

## Reflection

### 1. What was the hardest part of writing the one-pager?

The hardest part was deciding how much detail to include. If there is too much detail, the document becomes too long and difficult to read. If there is too little detail, developers and designers may not understand the feature clearly.

---

### 2. How did you decide what to include vs. leave out?

I focused on the most important information: the problem, target users, user stories, and acceptance criteria. Technical implementation details were not included because they should be discussed with engineers separately.

---

### 3. How would you present this one-pager to developers or designers?

I would present this one-pager in a short meeting and walk through:

- The problem
- The user journey
- The acceptance criteria

Then I would ask for feedback from developers and designers to confirm feasibility and improve the feature before development starts.

---

## Conclusion

This one-pager provides a clear overview of the feature, including the problem, users, user journey, and requirements.
It helps align the product, design, and engineering teams before development begins, ensuring everyone understands the feature and its goals.
