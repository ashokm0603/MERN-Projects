# Software Requirements Specification (SRS)
## Project 46: Exam Timetable Planner (Education)

### 1. Project Description
The Exam Timetable Planner is a smart scheduling application for students. Users input their upcoming exam dates, the perceived difficulty of each subject, and their available study hours. The system then automatically generates a smart, spaced-repetition revision schedule, breaking down subjects into manageable daily study blocks leading up to the exams.

### 2. Core Scope
The application requires a complex scheduling algorithm, calendar integration, a responsive user interface, and notification systems to keep the student on track during intense exam periods.

### 3. Functionalities (Minimum 25)

#### Input & Configuration
1. **Exam Entry:** Form to input the subject name, exact date, and time of the exam.
2. **Difficulty Rating:** Users rate each subject's difficulty on a scale (1-5) to allocate more time to harder subjects.
3. **Current Knowledge Level:** Rate how prepared the user currently feels (1-5) to adjust the starting intensity.
4. **Syllabus Breakdown:** Option to split a subject into specific topics or chapters (e.g., Biology -> Cell Structure, Genetics).
5. **Study Constraints:** Input available study hours per day (e.g., "Monday: 4 hours, Tuesday: 2 hours").
6. **Break Configuration:** Define the preferred ratio of study to break times (e.g., 50 mins study, 10 mins break).

#### Smart Scheduling Algorithm
7. **Auto-Generate Timetable:** Algorithm creates a daily schedule distributing the required study hours across the available days.
8. **Spaced Repetition:** The algorithm automatically schedules "Review" sessions for topics studied days prior to combat the forgetting curve.
9. **Conflict Resolution:** Alerts the user if the available study hours are mathematically insufficient for the number of exams/difficulty.
10. **Dynamic Rescheduling:** If a user misses a study block, the app recalculates and redistributes the missed hours over the remaining days.

#### Daily Study Dashboard
11. **Today's Agenda:** A clear chronological list of what exactly needs to be studied today.
12. **Study Timer:** Integrated Pomodoro timer specific to the current study block.
13. **Task Check-off:** Mark a topic as "Completed" or "Need more time."
14. **Focus Mode:** A full-screen mode that hides other subjects to reduce overwhelm.

#### Calendar Integration & Export
15. **In-App Calendar View:** A monthly and weekly grid showing the generated study blocks.
16. **Google/Apple Calendar Sync:** Export the generated schedule to the user's primary calendar app.
17. **PDF Export:** Generate a printable, color-coded weekly timetable to stick on a wall.

#### Analytics & Motivation
18. **Progress Rings:** Visual indicators showing the completion percentage of the revision plan for each subject.
19. **Confidence Tracker:** Before the exam, users update their confidence level, generating a "Readiness Score."
20. **Daily Affirmations:** Motivational quotes displayed on the dashboard during heavy study weeks.
21. **Study Log History:** Track exactly how many hours were actually spent on each subject versus the planned hours.

#### User Account & System Settings
22. **User Authentication:** Registration using Google or University Email.
23. **Push Notifications:** Reminders like "It's 4 PM, time to start your Physics revision."
24. **Color Customization:** Allow users to assign specific colors to different subjects for visual clarity.
25. **Admin Dashboard:** Monitor server performance, active users, and system errors without accessing user data.
