# Software Requirements Specification (SRS)
## Project 45: Course Progress Visualizer (Education)

### 1. Project Description
The Course Progress Visualizer is an organizational tool designed for self-taught students and online learners. It allows users to input the syllabus of various online courses (like Udemy, Coursera, or YouTube playlists) and visually track their chapter-by-chapter completion, time spent, and overall learning momentum using engaging charts.

### 2. Core Scope
The platform focuses on hierarchical data structures (Courses -> Modules -> Lessons), manual and automated progress logging, and dynamic data visualization.

### 3. Functionalities (Minimum 25)

#### Course Setup & Management
1. **Add Custom Course:** Manually create a course by defining its title, platform (e.g., "Udemy"), and total expected hours.
2. **Module/Chapter Builder:** A drag-and-drop interface to build the syllabus outline (e.g., Section 1: HTML, Section 2: CSS).
3. **Lesson Checkboxes:** Add specific lessons under each module with estimated durations (e.g., "Intro to Flexbox - 15 mins").
4. **YouTube Playlist Import:** Paste a YouTube playlist URL to automatically parse video titles and durations into a course structure.
5. **Course Status Tags:** Mark courses as "Not Started," "In Progress," "Paused," or "Completed."

#### Tracking & Logging
6. **One-Click Completion:** Check off a lesson to automatically update the course's overall completion percentage.
7. **Time Tracker (Stopwatch):** A built-in timer users can start when they begin studying to log actual time spent versus estimated time.
8. **Manual Time Entry:** Quickly log "I studied 45 minutes today" directly to a specific course.
9. **Daily Notes:** A rich-text area attached to each study session to jot down key takeaways or questions.
10. **Study Streaks:** Track consecutive days of logging at least 10 minutes of study time.

#### Data Visualization
11. **Master Progress Bar:** A prominent visual bar showing the percentage completion for each active course.
12. **Burnup Chart:** A graph plotting the number of completed lessons over time against the total lessons.
13. **Time Distribution Pie Chart:** Visual breakdown of which subjects/courses the user spent the most time on this week.
14. **Expected vs. Actual Graph:** Compare the estimated course duration with the actual time the user is logging.
15. **Milestone Confetti:** A visual celebration animation when completing a major module or an entire course.

#### Motivation & Reminders
16. **Study Goal Setting:** Set a weekly goal (e.g., "Study 10 hours this week") with a dynamic progress ring.
17. **Push Notifications:** Reminders like "You haven't touched your React course in 4 days. 15 minutes today?"
18. **Certificate Storage:** Upload and store completion certificates/PDFs linked to the finished course.
19. **Share Progress:** Generate a stylish "Learning Report Card" image to share on LinkedIn or Twitter.

#### Account & Settings
20. **User Authentication:** Secure login using email or Google OAuth.
21. **Dashboard Customization:** Pin the most important or urgent courses to the top of the dashboard.
22. **Data Export:** Export all study logs and notes as a Markdown or CSV file.
23. **Dark Mode:** System-wide dark theme to reduce eye strain during late-night study sessions.
24. **Multi-Device Sync:** Ensure progress checked off on mobile instantly updates on the desktop web app.
25. **Admin Dashboard:** Monitor overall user engagement, daily active users, and system uptime.
