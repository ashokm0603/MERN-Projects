# Software Requirements Specification (SRS)
## Project 13: Study Group Matchmaker (Social Impact)

### 1. Project Description
The Study Group Matchmaker is an academic social platform designed to connect students who want to study together. The system matches students based on shared subjects, mutual availability, compatible learning styles, and academic goals, helping them form productive and harmonious study groups. It addresses the common challenge of students struggling to find reliable, compatible study partners, particularly in large online or hybrid learning environments.

### 2. Core Scope
The application focuses on preference-based matching, study group formation, scheduling coordination, communication tools, and productivity tracking. It serves students at all academic levels, from high school to postgraduate, and supports both online and in-person group sessions.

### 3. Functionalities (Minimum 25)

#### User Profile & Preferences
1. **Student Profile Creation:** Register with name, institution, current courses/subjects, academic level, and a short bio.
2. **Learning Style Assessment:** Complete a short questionnaire to identify learning style (e.g., Visual, Auditory, Reading/Writing, Kinesthetic) used for compatibility matching.
3. **Subject & Topic Listing:** Specify subjects currently being studied and specific topics or chapters needing focus.
4. **Availability Schedule:** Input weekly availability using an interactive timetable grid.
5. **Session Preference Settings:** Choose preferred session format (Online, In-Person, Hybrid), session length, and ideal group size (2–6 members).

#### Matching Algorithm
6. **Subject-Based Matching:** Automatically identify students studying the same subject or course code.
7. **Availability Overlap Detection:** Find compatible students whose free time overlaps with the user's availability for at least one common session slot.
8. **Learning Style Compatibility Score:** Calculate a compatibility percentage between matched students based on their learning style profiles.
9. **Goal Alignment Matching:** Match students with similar academic goals (e.g., exam prep, assignment help, concept understanding).
10. **Match Recommendations Feed:** Display a ranked list of recommended study partners or groups with compatibility scores.

#### Group Formation & Management
11. **Create Study Group:** Any user can create a named study group, set the subject, maximum members, session schedule, and open it for applications or invitations.
12. **Join Group Requests:** Users can send join requests to open groups; group admins approve or decline.
13. **Invite-Only Groups:** Group creators can directly invite specific matched students.
14. **Member Role Assignments:** Assign roles within a group such as Facilitator, Note-Taker, and Time Keeper.
15. **Group Dashboard:** A shared group space showing upcoming sessions, shared resources, and member activity.

#### Scheduling & Sessions
16. **Shared Session Calendar:** A group calendar for scheduling, viewing, and RSVPing to upcoming study sessions.
17. **Session Reminders:** Automated email and push notification reminders before each scheduled session.
18. **Video Call Integration:** Integrated link generation for video call platforms (Zoom, Google Meet) directly from the session card.
19. **Session Notes & Minutes:** A shared collaborative document for each session to record key discussion points and action items.

#### Communication & Resources
20. **Group Chat:** Real-time group messaging for coordination, quick questions, and file sharing.
21. **Resource Library:** A shared folder within each group for uploading and organizing notes, PDFs, and study guides.
22. **Discussion Threads:** Organized Q&A threads where members can post questions and collaboratively answer them.

#### Progress & Feedback
23. **Session Attendance Tracking:** Log attendance for each study session to keep members accountable.
24. **Post-Session Rating:** Rate each study session and provide feedback on session productivity and group dynamics.
25. **Study Progress Dashboard:** Individual dashboard showing sessions attended, subjects covered, and study streak.
