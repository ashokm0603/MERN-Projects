# Software Requirements Specification (SRS)
## Project 22: Personal OKR Tracker (Productivity)

### 1. Project Description
The Personal OKR (Objectives and Key Results) Tracker is a goal-setting and performance management platform that empowers individuals and small teams to define ambitious quarterly objectives, break them down into measurable key results, and track weekly progress through intuitive visual dashboards and progress charts. Inspired by the OKR framework used by leading companies like Google and Intel, this tool brings that same rigor to personal and professional development.

### 2. Core Scope
The application centers on the OKR framework — creating objectives, defining quantifiable key results, tracking progress updates, and visualizing achievement. It requires a clean, motivating UI with strong data visualization and reminder capabilities to keep users engaged throughout the quarter.

### 3. Functionalities (Minimum 25)

#### OKR Creation & Management
1. **Create Quarterly Objectives:** Define a high-level, qualitative objective with a title, description, and associated quarter (e.g., Q3 2026).
2. **Key Result Definition:** Add 2–5 measurable key results (KRs) to each objective, specifying a metric, starting value, and target value (e.g., "Increase daily users from 100 to 500").
3. **KR Type Support:** Support different KR types: Numeric (increase/decrease a number), Percentage (reach X% completion), and Binary (Done/Not Done).
4. **Objective Categorization:** Tag objectives by life area (e.g., Career, Health, Finance, Learning, Relationships, Personal Projects).
5. **Archive Completed OKRs:** Move completed or past-quarter OKRs to an archive while keeping them accessible for reference.
6. **Sub-Objectives:** Nest child objectives under a parent objective to model complex, multi-part goals.

#### Progress Tracking
7. **Weekly Check-In Workflow:** A guided weekly check-in prompting users to update progress on each active key result.
8. **Progress Update with Notes:** When updating a KR's current value, optionally add a brief note explaining progress, blockers, or learnings.
9. **Confidence Level Rating:** During each check-in, rate the confidence of achieving the key result (Low / Medium / High) to surface at-risk OKRs.
10. **Automatic Progress Calculation:** The system automatically calculates overall objective progress as the average of its key results' completion percentages.
11. **Progress Timeline:** A chronological log of all updates made to each key result, showing the progression over time.

#### Visualization & Dashboard
12. **OKR Overview Dashboard:** A top-level dashboard showing all active objectives with their overall completion percentages and confidence ratings at a glance.
13. **Progress Bar Indicators:** Visual progress bars for each objective and key result showing percentage to target.
14. **Weekly Progress Chart:** A line chart showing how overall OKR progress has changed week-over-week throughout the quarter.
15. **Category Performance Summary:** A breakdown of performance across life area categories (e.g., Career at 75%, Health at 40%).
16. **Heat Calendar:** A heatmap calendar indicating weeks where check-ins were completed versus missed.

#### Reflection & Retrospective
17. **End-of-Quarter Review:** A structured retrospective form for each OKR: "What did we achieve?", "What blocked us?", "What will we do differently?"
18. **Quarter Comparison View:** Compare OKR outcomes across multiple past quarters to identify long-term progress trends.
19. **Lessons Learned Log:** A personal notes section for each objective to capture insights and lessons throughout the quarter.

#### Team Features (Optional)
20. **Shared Team OKRs:** Create and share OKRs with a team; each member can update their own contributing key results.
21. **Team Progress Dashboard:** A combined view showing all team members' OKR progress in one place.
22. **Mention & Comment System:** Tag team members in update notes and comment on each other's key results.

#### Reminders & Notifications
23. **Weekly Check-In Reminders:** Automated email or push notification on a configured day (e.g., every Monday) prompting the weekly check-in.
24. **At-Risk OKR Alerts:** Notify users when a key result's confidence is rated Low or when progress is significantly behind schedule.

#### User Account & Data
25. **User Authentication:** Secure login with email/password and Google OAuth.
26. **Data Export:** Export all OKR data, progress history, and retrospectives as a PDF or CSV for personal records or performance reviews.
