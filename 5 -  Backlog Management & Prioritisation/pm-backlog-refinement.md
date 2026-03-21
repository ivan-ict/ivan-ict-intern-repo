# Refining a Backlog Item for Development – Focus Bear

## Milestone: Backlog Management & Prioritisation

## Refining a Backlog Item for Development

---

## Goal

The goal of this task is to learn how to refine backlog items by adding clear details so that developers can easily understand, estimate, and implement the feature without confusion.

---

## Why is this important?

Vague backlog items create confusion, cause delays, and increase the risk of building the wrong feature. A well-refined backlog item includes a clear problem statement, user story, acceptance criteria, and technical considerations. This helps developers understand what needs to be built and when the task is considered complete.

---

## Research & Learn

### 1. What information should a well-defined backlog item include?

A well-defined backlog item should include:

- Title
- Problem statement
- User story
- Acceptance criteria
- Priority
- Technical considerations
- Design considerations
- Definition of Done

These details help the development team clearly understand the scope and expected outcome of the task.

### 2. How do PMs work with developers and designers to clarify feature requests?

PMs work closely with developers and designers by:

- Explaining the user problem
- Discussing possible solutions
- Asking developers about technical feasibility
- Asking designers about user experience and interface design
- Refining acceptance criteria together
- Answering questions during backlog refinement meetings

This collaboration ensures that the feature is realistic, useful, and technically feasible.

### 3. Why is it important to write clear acceptance criteria?

Acceptance criteria define what conditions must be met for a task to be considered complete. Clear acceptance criteria:

- Help developers understand what to build
- Help testers know what to test
- Prevent misunderstandings
- Reduce rework
- Make it easier to confirm when the feature is done

---

## Task – Refined Backlog Item

### Original Backlog Item (Unrefined)

**"Improve notification message"**

This backlog item is unclear because it does not specify:

- Which notification?
- What is the problem?
- What should be improved?
- How do we know when it is done?

---

## Refined Backlog Item

### Title

Improve Focus Session Reminder Notification Message

### Priority

Medium – This feature improves usability and user experience but does not block core functionality.

### Problem Statement

The current focus session reminder notification message is unclear and not very actionable. Users may not understand what they should do when the notification appears (start focus session, take a break, or return to work). This can reduce the effectiveness of reminders and negatively affect the user experience.

This backlog item aims to improve the clarity and usefulness of the reminder notification message so users can immediately understand the next action.

### User Story

**As a user**, I want to receive a clear and actionable reminder notification so that I know exactly what I should do next and can continue my focus session without confusion.

### Acceptance Criteria (Given–When–Then Format)

1. **Given** the user has a scheduled focus session,
   **When** the reminder notification appears,
   **Then** the notification message clearly tells the user what action to take.

2. **Given** the notification appears,
   **When** the user reads the message,
   **Then** the message uses simple and clear language.

3. **Given** the notification appears,
   **When** the user clicks the action button,
   **Then** the app opens the correct screen (focus session or break screen).

4. **Given** the notification is displayed,
   **When** viewed on desktop or mobile,
   **Then** the notification is readable and properly formatted.

5. **Given** the new notification message is implemented,
   **When** the feature is tested,
   **Then** the notification appears at the correct scheduled time.

### Technical Considerations

- The notification system must trigger based on the user’s schedule
- The notification should support deep linking to the correct screen
- The feature must work on desktop and mobile platforms
- Developers may need to modify the notification UI component
- The notification timing logic should be configurable

### Design Considerations

- The notification message should be short and clear
- Use consistent colours and UI style with Focus Bear design system
- Action buttons should be clearly visible
- Consider using icons to improve readability

### Definition of Done

This backlog item is considered done when:

- The new notification message is implemented
- The notification appears at the correct time
- The notification message is clear and actionable
- The action button opens the correct screen
- The feature works on desktop and mobile
- The feature is tested and no major bugs are found
- The Product Manager reviews and approves the feature

---

## Reflection

### 1. What details were missing from the original backlog item?

The original backlog item was missing a clear problem statement, user story, acceptance criteria, and technical considerations. It only mentioned improving a notification message but did not explain the problem or expected outcome.

### 2. How does refining backlog items help developers work more efficiently?

Refining backlog items helps developers clearly understand what needs to be built and what the expected result is. This reduces confusion, prevents rework, and helps developers estimate and complete tasks more efficiently.

### 3. What challenges did you face while writing the acceptance criteria?

The main challenge was writing acceptance criteria that are clear and testable. The acceptance criteria must be specific enough so that developers and testers know when the feature is complete.

---

## Conclusion

Refining backlog items is an important responsibility of a Product Manager. A clear and detailed backlog item improves communication between team members, reduces development delays, and ensures the team builds the correct feature efficiently.
