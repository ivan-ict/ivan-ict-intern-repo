# Analysing User Behaviour with PostHog

**Milestone:** Gathering Customer Insights
**Task:** Analysing User Behaviour with PostHog (#15)

---

## Goal

The goal of this task is to use PostHog analytics to analyse user behaviour, identify drop-off points in the user journey, and suggest improvements to improve activation and retention.

---

## Why is this important?

User feedback tells us what users say, but analytics show what users actually do. By analysing behaviour data, Product Managers can identify where users drop off, what features are used, and where onboarding or product experience needs improvement. Analytics help teams make data-driven decisions.

---

## Research & Learn

### What key user metrics should PMs track in PostHog?

Key metrics include:

- MAU (Monthly Active Users)
- DAU (Daily Active Users)
- Stickiness Ratio (DAU / MAU)
- Activation Rate
- Retention Rate (Week 1, Week 4, etc.)
- Funnel Conversion Rate
- Feature Usage
- Drop-off Rate between steps

These metrics help measure user engagement, retention, and product success.

### How do companies identify drop-off points in user journeys?

Companies use funnel analysis to track user steps such as:

1. App install
2. App open
3. Sign up
4. Complete onboarding
5. First key action (activation)
6. Become paid user

By analysing where users leave the funnel, companies can identify friction points and improve the onboarding experience.

### What role does analytics play in validating customer feedback?

Analytics validates whether customer feedback represents the majority of users. For example, some users may request new features, but analytics may show that most users are dropping off during onboarding. This helps teams prioritize the most important problems first.

---

## Key Insights from PostHog

### 1. Retention & Growth Trends

- Monthly Active Users (MAU) show a steady growth trend, reaching around 750 users in recent months.
- Stickiness ratio for paid users ranges between 10% and 26%, showing that only a portion of users use the app frequently.
- Retention drops significantly after Week 0, decreasing to around 25% in Week 1 and stabilizing around 5% by Week 10.

**Insight:** The product is growing in users, but long-term retention is still low.

---

### 2. Primary Drop-off Point – Mobile Activation

The biggest drop-off occurs in the mobile activation funnel.

- 41 users opened the app for the first time.
- Only 7 users completed the activation step.
- Activation rate = 17.07%.
- Drop-off rate = 82.93%.
- Conversion to paid users from this group = 0%.

**Insight:** Most new mobile users open the app but never complete the activation step, meaning they never experience the core value of the product.

---

## Suggested Improvement

### Guided Onboarding Flow – "First Session Success Checklist"

**Problem:**
Users open the app but do not complete the activation step (such as starting a focus session or setting up a habit).

**Proposed Solution:**
Implement a mandatory 3-step onboarding walkthrough:

1. Select one habit to track.
2. Grant necessary permissions (Notifications / Screen Time).
3. Start a 5-minute demo focus session.

**Goal:**
Increase activation rate from 17% to around 40% by reducing time to value (TTV) and helping users experience the core feature quickly.

---

## Reflection

### What user behaviour trend surprised you?

The most surprising trend is the large difference between MAU and DAU. While MAU is close to 800 users, DAU is only around 40–60 users. This suggests that many users use the app occasionally, but not daily. For a productivity app, daily usage should be higher.

### How does PostHog data compare to customer feedback from Zoho Desk & Discord?

Customer feedback from Discord and Zoho usually comes from active users who request features or report bugs. However, PostHog shows that many new users drop off before they even become active users. This means analytics reveals problems that are not visible in customer feedback because those users never reach the feedback stage.

### What’s one improvement you’d suggest to Focus Bear based on analytics?

I would suggest implementing mobile onboarding guidance such as tooltips, walkthrough tutorials, or a demo session. For example, if a user opens the app but does not activate within 2 minutes, the app could show a guide explaining how to start the first focus session.

---

## Summary

PostHog analytics shows that the main problem is not user acquisition, but user activation and retention, especially on mobile. Improving the onboarding experience and helping users complete their first focus session could significantly improve activation and retention rates.
