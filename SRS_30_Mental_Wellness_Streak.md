# Software Requirements Specification (SRS)
## Project 30: Mental Wellness Streak Tracker (Health & Wellness)

### 1. Project Description
The Mental Wellness Streak Tracker is a gamified daily habit-building application. It encourages users to perform simple, daily micro-habits—such as meditating for 5 minutes, journaling, or taking a walk—to improve their mental health. By rewarding consistency with streaks, badges, and positive reinforcement, it helps users build lasting, healthy routines.

### 2. Core Scope
The platform focuses on daily logging, streak calculation logic, gamification (badges, levels), and visual progress tracking.

### 3. Functionalities (Minimum 25)

#### Habit Configuration & Daily Logging
1. **Micro-Habit Selection:** Users can choose from a library of preset habits (e.g., "Drink Water", "Read 10 pages", "Meditate").
2. **Custom Habit Creation:** Ability to define a personalized daily habit with a custom icon and color.
3. **Daily Checklist Dashboard:** A clear, distraction-free view of the day's required habits.
4. **One-Tap Completion:** Simple tap/click to mark a habit as done for the day, triggering a confetti animation.
5. **Partial Completion (Optional):** Log partial progress (e.g., drank 2 out of 4 required glasses of water).

#### Streak & Gamification Engine
6. **Streak Counter:** Prominently display the number of consecutive days a habit has been completed.
7. **Global Streak:** A master streak that tracks if *any* wellness activity was completed that day.
8. **Streak Forgiveness (Freezes):** Users earn "Freezes" by maintaining a 7-day streak, allowing them to miss one day without losing their streak.
9. **Badge Unlocks:** Award visual badges for milestones (e.g., "7 Days Strong", "30 Day Champion").
10. **Leveling System:** Earn XP for every completed habit to level up the user's profile.

#### Reminders & Notifications
11. **Custom Nudges:** Set specific times to receive push notifications for each habit.
12. **"Don't Break the Chain" Alerts:** A specific evening warning if a streak is about to be lost at midnight.
13. **Motivational Quotes:** Daily push notifications featuring positive affirmations.
14. **Silent Mode:** Automatically mute notifications during configured sleep hours.

#### Analytics & Reflection
15. **Calendar View:** A monthly grid showing colored dots on days where habits were completed.
16. **Success Rate Analytics:** Display the percentage of days a habit was completed over the last 30 or 90 days.
17. **Mood Correlation:** Allow users to rate their daily mood (1-5) alongside their habits to see how consistency affects mental health.
18. **Weekly Review Prompt:** A brief Sunday reflection form asking what went well and what was challenging.

#### Social & Community (Optional/Opt-in)
19. **Accountability Buddies:** Invite a friend to share streak statuses.
20. **Buddy Nudges:** Send a predefined encouraging emoji to a buddy who hasn't completed their habit yet today.
21. **Leaderboards:** Opt-in leaderboards showing friends with the highest active streaks.

#### Account & Data Management
22. **User Authentication:** Email/password or OAuth registration.
23. **Timezone Handling:** Ensure "midnight" is calculated accurately based on the user's local timezone.
24. **Data Backup & Sync:** Cloud syncing to ensure streaks aren't lost if a device is changed.
25. **Dark Mode Theme:** A soothing dark theme to prevent eye strain during late-night journaling or logging.
