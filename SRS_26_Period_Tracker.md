# Software Requirements Specification (SRS)
## Project 26: Period & Hormone Cycle Tracker (Health & Wellness)

### 1. Project Description
The Period & Hormone Cycle Tracker is a holistic women's health application that goes beyond basic calendar tracking. It allows users to log physical symptoms, mood changes, and energy levels, using this data to predict future cycles and offer personalized wellness, diet, and exercise tips tailored to the current hormonal phase.

### 2. Core Scope
The application relies heavily on data logging, predictive algorithms for calendar generation, data visualization, and a content management system for wellness tips. Privacy and data security are paramount.

### 3. Functionalities (Minimum 25)

#### Cycle Tracking & Prediction
1. **Cycle Setup:** Initial onboarding to gather average cycle length and the date of the last period.
2. **Interactive Calendar:** A main calendar view highlighting predicted period dates, ovulation windows, and fertile days.
3. **Log Period:** Easily mark the start and end dates of a menstrual cycle.
4. **Prediction Algorithm:** Machine learning model that adjusts future predictions based on historical cycle variations.
5. **Phase Indicator:** Clearly display the current hormonal phase (Menstrual, Follicular, Ovulatory, Luteal) on the dashboard.

#### Symptom & Mood Logging
6. **Flow Tracking:** Log the intensity of the flow (Light, Medium, Heavy, Spotting) daily.
7. **Physical Symptoms Logger:** Select from a predefined list of symptoms (cramps, bloating, acne, headaches).
8. **Mood & Energy Logger:** Track emotional states (happy, sensitive, anxious) and energy levels (high, low, exhausted).
9. **Basal Body Temperature (BBT):** Manual input for BBT tracking to aid in precise ovulation prediction.
10. **Custom Notes:** A private diary section for any specific daily observations.

#### Personalized Insights & Content
11. **Phase-Specific Tips:** Display daily tips on nutrition, exercise, and productivity based on the user's current hormonal phase.
12. **Pattern Recognition:** AI highlights recurring patterns (e.g., "You frequently report headaches 2 days before your period").
13. **Article Library:** A searchable database of medically reviewed articles regarding women's health and hormones.
14. **Cycle History Analysis:** Visual graphs comparing cycle lengths over the past 6-12 months.

#### Health Integrations & Reports
15. **Water Intake Tracker:** A simple counter to ensure adequate hydration during specific cycle phases.
16. **Sleep Integration:** Log hours slept and correlate sleep quality with cycle phases.
17. **Export for Doctor:** Generate a consolidated PDF report of cycles and symptoms to share with a gynecologist.
18. **Pregnancy Mode Toggle:** Pause cycle predictions and switch to a trimester-based tracker if the user becomes pregnant.

#### Reminders & Notifications
19. **Period Approaching Alert:** Push notification 2-3 days before the predicted start date.
20. **Fertile Window Alert:** Notification when entering the ovulation phase.
21. **Pill Reminder (Birth Control):** Optional daily reminder for taking oral contraceptives.
22. **Log Reminder:** Gentle evening nudge to log symptoms if the user hasn't done so that day.

#### Security & Account Management
23. **Anonymous Mode:** Option to use the app without creating a server-synced account (local storage only) for maximum privacy.
24. **Data Deletion:** A clear, one-click option to permanently delete all health data and account details from the servers.
25. **Passcode Protection:** App lock feature requiring a PIN or biometric authentication to open the app.
