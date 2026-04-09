# PM Involvement in QA & User Testing (#5)

## Overview

This task focuses on understanding how Product Managers collaborate with QA to ensure features meet requirements and deliver a consistent user experience before release.

---

## Goal

To evaluate a feature implementation, compare it with expected behaviour, and identify any issues or inconsistencies.

---

## Why This Is Important

Testing ensures:

- Features work as intended
- User experience is consistent and intuitive
- Bugs are identified before reaching production

PM involvement helps validate that the feature aligns with **user needs and product expectations**, not just technical correctness.

---

## Research & Learn

### 1. Role of PM in Testing

Product Managers:

- Validate features against original requirements
- Test from a **user perspective**
- Identify gaps between expected vs actual behaviour
- Prioritise bugs based on impact

---

### 2. How QA Teams Work

QA teams:

- Write **test cases** based on requirements
- Cover:
    - Functional testing (does it work?)
    - Edge cases (boundary conditions)
    - Regression testing (no breakage)
- Execute tests and report bugs

---

### 3. Why PM Testing Is Important

- Developers focus on implementation correctness
- QA focuses on coverage
- PM ensures:
    - The feature actually solves the user problem
    - The experience is intuitive and consistent

---

## Feature Tested

### Feature: Stats Screen Access

---

## Expected Behaviour (Based on Product Logic)

- If a user is logged in:
    - All authenticated screens (e.g., Stats, Settings) should recognise the session
- The app should maintain a **consistent authentication state across screens**

---

## Actual Behaviour Observed

- Navigating to **Stats screen**:
    - App asks user to sign in
    - Shows authentication error
- Navigating to **Settings screen**:
    - User is still shown as logged in

---

## Identified Issue

### Problem

Inconsistent authentication state across different screens.

### Steps to Reproduce

1. Log in to the app
2. Navigate to **Stats screen**
3. Observe sign-in requirement and error
4. Navigate to **Settings screen**
5. Observe user is still logged in

---

### Impact

- Confusing user experience
- Reduces trust in the app
- May block access to key features

---

### Suggested Fix

- Ensure authentication state is **synchronised across all screens**
- Validate session handling logic when navigating between views
- Add fallback handling for session validation errors

---

## Comparison: Spec vs Implementation

| Aspect               | Expected              | Actual              |
| -------------------- | --------------------- | ------------------- |
| Authentication state | Consistent across app | Inconsistent        |
| User experience      | Seamless navigation   | Confusing behaviour |
| Error handling       | Clear and accurate    | Misleading          |

---

## Reflection

### 1. How did implementation differ from spec?

The implementation failed to maintain a consistent authentication state, leading to conflicting behaviour between screens.

---

### 2. What would you improve in the testing process?

- Add **cross-screen testing scenarios**
- Include **authentication state validation tests**
- Test real user navigation flows, not just isolated features

---

### 3. How can PMs reduce issues in production?

- Define clearer acceptance criteria
- Collaborate closely with QA on test coverage
- Perform **end-to-end testing from a user perspective**
- Prioritise high-impact bugs before release

---

## Key Takeaways

- PM testing ensures features work from a **user perspective**
- Inconsistencies often appear across screens, not just within one feature
- Early detection of bugs improves product quality and user trust

---
