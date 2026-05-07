# Software Requirements Specification (SRS)
## Project 32: Posture & Break Reminder App (Health & Wellness)

### 1. Project Description
Designed for office workers and students, this web-based application aims to combat the negative health effects of prolonged sitting. It runs in the background and pops up at scheduled intervals to remind users to fix their posture, take a screen break, or perform quick guided stretches.

### 2. Core Scope
The application relies heavily on browser notifications, timer logic, and a rich media library of GIFs/videos demonstrating correct posture and stretches.

### 3. Functionalities (Minimum 25)

#### Timer & Reminder Logic
1. **Customizable Intervals:** Set reminders for every 30, 45, or 60 minutes.
2. **Smart Scheduling:** Define "Working Hours" (e.g., 9 AM to 5 PM) so notifications don't fire during personal time.
3. **Micro-Breaks (20-20-20 Rule):** Specific 20-second timers reminding the user to look 20 feet away to reduce eye strain.
4. **Macro-Breaks:** Longer 5-10 minute reminders to stand up and walk around.
5. **Snooze Function:** Temporarily delay a stretch reminder if the user is in a deep focus state or a meeting.

#### Guided Stretches & Exercises
6. **Stretch Library:** A categorized library of stretches (Neck, Shoulders, Lower Back, Wrists).
7. **Visual Demonstrations:** Auto-playing GIFs or short looping videos demonstrating exactly how to perform the stretch.
8. **Audio Cues:** Optional voice overs guiding the user through the breathing and holding of the stretch.
9. **Desk-Friendly Filter:** Ensure all suggested stretches can be performed in a standard office chair without extra equipment.
10. **Randomized Routines:** The app selects a different combination of 3 stretches each break to prevent monotony.

#### Posture Education
11. **Ergonomic Setup Guide:** An interactive checklist helping users correctly set the height of their chair, monitor, and keyboard.
12. **Posture Checker:** A visual graphic reminding users to check their ear-shoulder-hip alignment.
13. **Daily Posture Tip:** A small informational snippet shown alongside the break timer.

#### Tracking & Analytics
14. **Compliance Tracking:** Log whether the user completed the stretch routine or skipped it.
15. **Daily Score:** A gamified score out of 100 based on adherence to the break schedule.
16. **Pain & Stiffness Logger:** A weekly prompt asking the user to rate their back/neck pain to see if the app is helping over time.
17. **Weekly Reports:** Visual charts showing how many minutes were spent stretching that week.

#### User Interface & Experience
18. **Unintrusive Notifications:** Use standard OS push notifications that don't aggressively steal window focus.
19. **Full-Screen Break Mode:** An optional strict mode that covers the screen with the stretch animation, forcing the user to stop working.
20. **Theme Options:** Light, Dark, and "Zen" color palettes.
21. **Sound Toggles:** Ability to mute all chimes and bells for open-office environments.

#### Technical & Account Features
22. **User Accounts:** Save settings and routine preferences across different computers (e.g., Work PC and Home Laptop).
23. **Desktop App (PWA Wrapper):** Ability to install the web app as a standalone desktop application via Chrome/Edge.
24. **Webcam Posture AI (Advanced/Optional):** Request webcam permission to periodically check if the user is slouching using a basic machine learning model (e.g., TensorFlow.js PoseNet).
25. **Admin Panel:** Add new stretches to the global database and monitor aggregate user adherence.
