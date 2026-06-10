# Software Requirements Specification (SRS)
## Project 59: NGO Volunteer Management System (Community & Civic)

### 1. Project Description
The NGO Volunteer Management System is a comprehensive organizational platform designed to help non-governmental organizations efficiently recruit, onboard, schedule, and track the contributions of their volunteer workforce. It streamlines the entire volunteer lifecycle — from initial registration and skill profiling to drive assignment, hour logging, and impact reporting — enabling NGO staff to focus less on administrative coordination and more on their core mission.

### 2. Core Scope
The application focuses on volunteer registration and skill management, drive/event creation and assignment, attendance and hour tracking, impact metrics reporting, and communication between NGO coordinators and volunteers. It serves NGOs of varying sizes, from local community organizations to large national bodies managing hundreds of volunteers.

### 3. Functionalities (Minimum 25)

#### Volunteer Registration & Profiles
1. **Volunteer Registration Portal:** A public-facing registration form for new volunteers to sign up with name, contact details, location, educational background, and languages spoken.
2. **Skills & Expertise Profiling:** Volunteers select their relevant skills from a predefined list (Medical, Teaching, Construction, Counseling, Translation, IT, Logistics, Fundraising, Photography, etc.).
3. **Availability Calendar:** Volunteers input their weekly recurring availability and blackout dates for accurate scheduling.
4. **Document Upload:** Volunteers upload supporting documents (ID proof, certificates, background check) for verification purposes.
5. **Volunteer Status Management:** Track volunteer status: Pending Verification, Active, On Leave, Inactive, or Graduated.

#### Drive & Event Management (Coordinator)
6. **Drive/Event Creation:** Coordinators create volunteer drives with a title, description, cause area (Education, Healthcare, Environment, Relief, Livelihood, etc.), location, date, and time.
7. **Volunteer Requirement Specification:** Define how many volunteers are needed and what specific skills are required for each drive.
8. **Drive Visibility Settings:** Publish drives as Open (any volunteer can apply) or Restricted (coordinator assigns specific volunteers).
9. **Drive Listing & Calendar View:** A calendar and list view of all upcoming, ongoing, and past drives accessible to both coordinators and volunteers.

#### Assignment & Scheduling
10. **Skill-Based Volunteer Matching:** AI-assisted recommendation of suitable volunteers for a drive based on required skills and availability overlap.
11. **Coordinator Assignment:** Manually assign specific volunteers to a drive from the recommendation list or the full volunteer directory.
12. **Volunteer Self-Application:** For open drives, volunteers can browse and apply to join a drive; coordinators approve or decline applications.
13. **Assignment Confirmation Notifications:** Notify volunteers via email and push notification when they are assigned to or accepted for a drive.
14. **Drive Roster Management:** View the complete list of assigned volunteers for each drive with their contact info and skill profiles.

#### Attendance & Hour Tracking
15. **QR Code Check-In:** Coordinators display a unique QR code at the drive; volunteers scan it on arrival to log attendance automatically.
16. **Manual Attendance Override:** Coordinators can manually mark attendance for volunteers who could not scan the QR code.
17. **Hour Logging:** Calculate and record volunteer hours automatically based on drive duration upon check-in and check-out.
18. **Manual Hour Adjustment:** Coordinators can adjust logged hours if a volunteer stayed for a partial duration.
19. **Cumulative Hour Dashboard:** Each volunteer's profile shows their total verified volunteer hours across all drives.

#### Impact Metrics & Reporting
20. **Individual Volunteer Impact Report:** Generate a personalized report for each volunteer showing hours contributed, drives participated in, and causes served.
21. **Volunteer Certificate Generation:** Automatically generate a downloadable participation/appreciation certificate for a volunteer upon completing a drive.
22. **NGO-Wide Impact Dashboard:** Aggregate statistics for the organization: total volunteer hours, drives conducted, volunteers active, and beneficiaries reached.
23. **Drive Post-Mortem Report:** Generate a summary for each completed drive including attendance rate, hours served, and coordinator notes.

#### Communication & Engagement
24. **Announcement Broadcasts:** Send announcements to all active volunteers or specific skill groups via email and in-app notifications.
25. **Drive-Specific Chat:** A communication channel within each drive for coordinators and assigned volunteers to coordinate logistics.
26. **Volunteer Recognition & Badges:** Award badges and public recognition for milestone achievements (e.g., 50 Hours Served, 10 Drives Completed, Most Consistent Volunteer of the Quarter).
