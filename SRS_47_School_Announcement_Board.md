# Software Requirements Specification (SRS)
## Project 47: School Announcement Board (Education)

### 1. Project Description
The School Announcement Board is a centralized, role-based digital portal designed to streamline communication within an educational institution. It replaces traditional bulletin boards and fragmented email chains by providing a single platform where administrators, teachers, and students can broadcast, view, and interact with important school-wide or class-specific announcements.

### 2. Core Scope
The application relies heavily on Role-Based Access Control (RBAC), categorized feeds, push notifications, and document attachment capabilities to ensure information reaches the right audience efficiently.

### 3. Functionalities (Minimum 25)

#### Role-Based Access & Authentication
1. **Multi-Role Login:** Secure authentication supporting three distinct roles: Admin, Teacher, and Student/Parent.
2. **SSO Integration:** Support for Single Sign-On using Google Workspace for Education or Microsoft 365.
3. **Role-Specific Dashboards:** Different UI layouts and capabilities depending on the logged-in role (e.g., Admins see school-wide metrics, Students see their class feed).
4. **User Import:** Admins can bulk-import student and teacher accounts via CSV at the start of a semester.

#### Announcement Creation (Admins & Teachers)
5. **Rich Text Editor:** Draft announcements using a rich text editor (bold, italics, bullet points, hyperlinks).
6. **Audience Targeting:** Broadcasters can select the target audience: "Whole School," "Specific Grade Level," or "Specific Class."
7. **File Attachments:** Ability to attach PDFs, permission slips, or images directly to an announcement.
8. **Scheduled Posting:** Draft an announcement now and schedule it to automatically publish at a specific date and time.
9. **Priority Tagging:** Mark an announcement as "High Priority" or "Urgent," which visually highlights it in the feed.
10. **Expiration Dates:** Set an automatic expiration date for an announcement so it disappears from the feed when no longer relevant (e.g., an event flyer).

#### Viewing & Interaction (Students & Parents)
11. **Personalized Feed:** Students only see announcements relevant to their specific grade and enrolled classes.
12. **Read Receipts:** Track which students/parents have opened and viewed a specific mandatory announcement.
13. **Digital Signatures (Consent):** A feature allowing parents to digitally sign permission slips attached to an announcement.
14. **Commenting System:** Optional threaded comments below an announcement (can be toggled on/off by the author) for Q&A.
15. **Bookmark Announcements:** Students can save important announcements (like exam schedules) to a "Saved" tab for quick reference.

#### Organization & Search
16. **Category Tags:** Tag announcements with categories like "Sports," "Academics," "Clubs," or "Emergencies."
17. **Global Search:** Fast text-based search to find past announcements using keywords.
18. **Archive System:** Old or expired announcements are moved to an accessible Archive rather than permanently deleted.
19. **Event Calendar Integration:** Announcements with dates automatically populate a shared school-wide digital calendar.

#### Notifications & Alerts
20. **Push Notifications:** Instant mobile/browser push notifications for Urgent or High Priority broadcasts.
21. **Daily Digest Emails:** An automated end-of-day email summarizing all new announcements for parents who don't log in daily.
22. **SMS Alerts:** Integration with an SMS gateway (like Twilio) to text parents directly during emergencies (e.g., snow days, lockdowns).

#### System Administration & Analytics
23. **Engagement Analytics:** Admins can view charts showing the open rates and click-through rates of their announcements.
24. **Content Moderation:** Admins have the power to edit or delete any announcement posted by a teacher if it violates school policy.
25. **Audit Logs:** A security log tracking who posted, edited, or deleted announcements, ensuring accountability.
