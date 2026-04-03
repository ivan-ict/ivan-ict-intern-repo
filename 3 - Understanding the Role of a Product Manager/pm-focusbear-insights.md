# Product Management at Focus Bear – Insights

## Overview

This note summarises my current understanding of product management at Focus Bear based on three recent OKR / supervisor check-in meetings, my observations of the product, and team discussions. Overall, Focus Bear is currently concentrating on improving onboarding, activation, engagement after sign-up, product reliability, and cross-team delivery coordination.

---

## 1. What are Focus Bear’s current product priorities?

### Main product priorities

#### 1. Improve onboarding and activation

A major current priority is improving onboarding across Mac, mobile, Windows, and desktop experiences. The team is trying to reduce friction during setup, make permissions easier to understand, and guide users more clearly toward value early in the journey. Mac onboarding is being finalised, while mobile onboarding and the mobile home screen are also being redesigned to improve activation and engagement.

#### 2. Improve post-onboarding engagement

The team is not only focused on getting users through onboarding, but also on making the product feel more engaging afterwards. Proposed changes include a redesigned home screen, micro-interactions, collapsible charts, clearer next steps, motivational empty states, and improved routine suggestions. This shows that Focus Bear is trying to strengthen the experience after sign-up, not just the first-run flow.

#### 3. Fix reliability and product quality issues

There is ongoing attention on push notifications, routine suggestions, AI blocking, settings synchronisation, UI bugs, and cross-platform consistency. The team is also investing in CI improvements, automated UI screenshots, and AI-assisted QA to increase development speed without lowering quality.

#### 4. Strengthen security and operational maturity

Security and compliance are also important priorities. The SendGrid API key breach led to stricter policy attention, including quarterly key rotations and continued ISO 27001 / GDPR work. This indicates that product work at Focus Bear is connected not only to features, but also to trust, compliance, and operational resilience.

#### 5. Improve delivery speed and team coordination

Jeremy also emphasised faster shipping, more merged PRs, and better coordination across backend, frontend, Mac, mobile, UX, and QA. The change to stand-ups and scrum-of-scrums reflects a process-level effort to support multi-platform delivery more effectively.

---

## 2. What key user problems is Focus Bear solving?

Based on the product direction and team discussions, Focus Bear seems to be solving several core user problems.

### 1. Difficulty getting started with focus systems

Many users likely want help building better work or study habits, but setup can feel confusing or overwhelming. That is why the team is investing so much in onboarding, permission guidance, distraction blocking setup, and clearer explanations.

### 2. Difficulty staying focused and avoiding distractions

Focus Bear helps users block distractions, structure routines, and create an environment that supports deep work or study. Features like distraction blocking, routine suggestions, and habit support all point to this core problem.

### 3. Difficulty maintaining motivation and continuing to use productivity tools

The team’s interest in home screen redesigns, motivational states, micro-interactions, and stickiness metrics suggests that many users may sign up but not continue engaging. Focus Bear is therefore trying to help users maintain momentum, not just complete setup.

### 4. Difficulty navigating productivity features easily

Menu redesign work, habit management improvements, and simplified workflows suggest that usability and navigation are also important. Focus Bear is solving not only behavioural problems, but also interface clarity problems.

---

## 3. How does Focus Bear collect user feedback and incorporate it into decision-making?

Focus Bear appears to use several feedback sources:

### Feedback sources

- **User testing sessions** are being conducted and reviewed to gather direct usability feedback.
- **User audits** are being used to identify onboarding drop-off points.
- **Intern feedback** is also reviewed and incorporated into the roadmap.
- **Product metrics** such as activation rate, stickiness, retention, conversions, paying users, and traffic sources are regularly discussed in OKR meetings.
- **Bug reports and QA findings** from different teams feed into development priorities.

### How feedback is used

Feedback seems to be translated into design iterations, bug-fixing priorities, onboarding improvements, roadmap updates, and QA actions. This suggests that decision-making at Focus Bear combines both qualitative feedback and quantitative product metrics. Rather than relying on one source only, the team appears to balance user observation, analytics, and internal team input.

---

## 4. How do PMs at Focus Bear currently work with developers, UX designers, and QA?

From the meetings, product management at Focus Bear looks very cross-functional and hands-on.

### Working with developers

PM-related discussions are closely connected to implementation priorities such as onboarding updates, mobile releases, notification fixes, SES migration, settings sync, and merged PR targets. Product decisions are discussed in the same space as engineering progress and blockers, which suggests close PM–engineering collaboration.

### Working with UX/design

Design seems to play a major role in product decisions. The team reviews Figma designs, discusses user trust, simplified flows, interface clarity, navigation, and high-DPI usability. Designers and engineers appear to collaborate closely before implementation, especially for onboarding and home screen work.

### Working with QA

QA is integrated through testing, design QA, manual QA needs, automation efforts, OpenClaw experiments, and review of user testing feedback. There is also an ongoing push to improve testing confidence so the team can merge faster and release with less risk.

### My conclusion

PM work at Focus Bear appears to involve:

- reviewing metrics and user feedback
- aligning design and engineering priorities
- identifying blockers and quality issues
- helping coordinate multiple teams around the same product outcomes

---

## 5. Notes from OKR meetings attended

### OKR Meeting 1 – 16 March 2026

- Mobile onboarding release was close to completion.
- Activation and stickiness showed modest improvement.
- Android notification issues remained a concern.
- The team discussed QA automation, onboarding demos, and cross-platform consistency.
- Product discussions were tightly linked to implementation and release planning.

### OKR Meeting 2 – 23 March 2026

- Mac onboarding became a strong focus, especially trust, clarity, and guided setup.
- Mobile onboarding and home screen improvements were planned next.
- Activation rates had dropped slightly, so the team was watching this closely.
- User testing sessions and intern feedback were being fed into the roadmap.
- Menu redesign and workflow simplification were also discussed.

### OKR Meeting 3 – 30 March 2026

- Focus remained on Mac onboarding and mobile home screen improvements.
- Recent onboarding changes had not yet improved activation enough.
- A user audit was underway to identify drop-off points.
- Security became more urgent after the SendGrid incident.
- Team coordination, delivery speed, and CI improvements were also emphasised.

---

## 6. User testing review

> **Note:** I have not directly reviewed the full user testing recordings yet. The observations below are a provisional summary based on OKR notes, product behaviour, and related team feedback. I should refine this section after watching the recordings myself.

### Three things that were frustrating or confusing

1. The onboarding flow may still contain too much friction, especially around permissions, accessibility, and distraction blocking steps.
2. Users may be unclear about what to do immediately after completing permissions or onboarding.
3. Some parts of the product still seem inconsistent across platforms, especially around notifications, settings behaviour, and routine suggestions.

### Three things that worked well

1. The team is improving onboarding with clearer instructions and a more trust-building design.
2. The use of illustrations, guided setup, and simplified UI likely makes technical steps feel less intimidating.
3. Menu redesign and workflow simplification appear to improve navigation clarity and reduce clutter.

---

## 7. One area where Focus Bear seems to be struggling

The biggest struggle appears to be **converting onboarding completion into real activation and continued engagement**.

Even after onboarding improvements, activation rates on iOS and Android have not improved enough, and in some cases have slightly declined. This suggests the challenge is not only getting users through setup, but also helping them quickly experience value and continue using the product afterwards. The redesign of the home screen and user audits shows the team is aware of this gap.

### One question to ask in the next meeting

**What is the single biggest drop-off point in the onboarding-to-activation journey right now, and how are we measuring whether the new home screen changes actually fix it?**

---

## 8. Reflection

### What are three major product challenges Focus Bear is currently facing?

#### 1. Activation is still not improving enough

The company is investing heavily in onboarding, but activation results are still weaker than expected. This suggests that the current product journey still has friction or unclear value delivery.

#### 2. Reliability and consistency across platforms

Push notifications, routine suggestions, settings synchronisation, UI bugs, and platform-specific issues show that maintaining a smooth cross-platform experience is still difficult.

#### 3. Balancing fast delivery with quality, coordination, and team capacity

The team wants faster PR throughput and better delivery speed, but also needs better QA, better CI, and more support in Mac, frontend, and manual QA. This creates pressure between speed and quality.

### What questions do you still have about Focus Bear’s product strategy?

1. Which user segment is the highest priority right now: students, professionals, neurodivergent users, or teams?
2. How does Focus Bear define successful activation beyond just finishing onboarding?
3. Which retention metric matters most in roadmap decisions: daily use, weekly stickiness, routine completion, or paid conversion?
4. How are PMs prioritising between feature growth, reliability fixes, and security/compliance work?
5. How much roadmap weight comes from user testing versus analytics versus internal team feedback?

---

## 9. Final takeaway

My current understanding is that product management at Focus Bear is highly practical, cross-functional, and strongly tied to product metrics. The company is currently focused on improving activation, strengthening onboarding, increasing engagement after setup, fixing reliability issues, and improving collaboration across teams. A key challenge is that product improvements are being made, but the expected activation gains have not yet fully appeared, so the next stage seems to be about better identifying friction and validating whether design changes truly improve user outcomes.
