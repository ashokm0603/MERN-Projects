# Software Requirements Specification (SRS)
## Project 27: Sleep Quality Dashboard (Health & Wellness)

### 1. Project Description
The Sleep Quality Dashboard is a personal health tracking web application that helps users understand and improve their sleep patterns. Users manually log their sleep sessions, rate subjective sleep quality, and track correlated factors like mood, caffeine intake, exercise, and screen time. The platform generates insightful analytics, pattern recognition reports, and personalized sleep hygiene recommendations to help users achieve consistent, restorative sleep.

### 2. Core Scope
The application focuses on sleep data logging, subjective quality rating, correlation analysis between lifestyle factors and sleep quality, trend visualization, and evidence-based sleep improvement recommendations. It uses manual entry as the primary data input method, making it universally accessible without requiring wearable hardware.

### 3. Functionalities (Minimum 25)

#### Sleep Logging
1. **Sleep Session Logging:** Log bedtime, wake time, and calculated total sleep duration for each night.
2. **Sleep Quality Rating:** Rate the subjective quality of each night's sleep on a 1–5 star or 1–10 scale.
3. **Sleep Notes:** Add free-text notes to each log entry to record specific factors (e.g., "Had coffee at 7pm," "Had a nightmare").
4. **Nap Tracking:** Log daytime nap duration separately from nightly sleep to track total daily rest.
5. **Morning Feel Indicator:** Log how refreshed or groggy the user feels upon waking with a simple emoji or scale selector.

#### Lifestyle Factor Tracking
6. **Caffeine Intake Log:** Record the number of caffeinated beverages consumed and the time of the last intake.
7. **Exercise Log:** Note whether the user exercised that day, the type of exercise, and the time of day.
8. **Screen Time Before Bed:** Log estimated screen time in the hour before sleeping.
9. **Stress Level Rating:** Rate the daily stress level (1–10) to correlate with sleep quality.
10. **Alcohol Consumption Log:** Record alcohol consumption for the day as a correlation factor.

#### Analytics & Insights Dashboard
11. **Weekly Sleep Summary:** Key metrics for the past 7 days: average sleep duration, average quality score, total hours slept.
12. **Sleep Duration Trend Chart:** An interactive line chart showing nightly sleep duration over 7, 30, and 90-day periods.
13. **Quality Score Trend Chart:** A corresponding chart for the subjective quality rating over time.
14. **Sleep Debt Calculator:** Calculate and display cumulative "sleep debt" based on the user's personal optimal sleep duration goal.
15. **Best & Worst Sleep Nights Highlights:** Automatically identify and surface the best and worst sleep nights of the month.

#### Pattern Recognition & Correlations
16. **Correlation Analysis:** Visualize correlations between sleep quality and tracked lifestyle factors (caffeine, exercise, stress, screen time).
17. **Weekday vs. Weekend Comparison:** Compare average sleep duration and quality scores between weekdays and weekends.
18. **Sleep Schedule Consistency Score:** Measure how consistent the user's bedtime and wake time are, as consistency is a key indicator of sleep health.
19. **Optimal Bedtime Suggestion:** Based on historical data, suggest the bedtime that is most strongly correlated with high-quality sleep for the user.

#### Recommendations & Education
20. **Personalized Sleep Hygiene Tips:** Provide specific, actionable recommendations based on the user's identified patterns (e.g., "Your quality drops on nights with caffeine after 4pm").
21. **Sleep Education Library:** A curated library of evidence-based articles about sleep hygiene, sleep disorders, and relaxation techniques.
22. **Guided Relaxation Links:** Quick access to guided meditation, breathing exercises, or white noise resources to help wind down.

#### Goals & Reminders
23. **Sleep Duration Goal Setting:** Set a personal target for nightly sleep hours (e.g., 7.5 hours) to track against.
24. **Bedtime & Wake-Up Reminders:** Configurable push/browser notifications reminding users of their target bedtime and wake-up time.

#### User Account & Data
25. **User Authentication:** Secure registration and login with email/password and Google OAuth.
26. **Data Export:** Download complete sleep history as a CSV file for sharing with healthcare providers.
27. **Data Visualization Report (PDF):** Generate a monthly sleep health report in PDF format for personal review.
