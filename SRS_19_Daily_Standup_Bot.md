# Software Requirements Specification (SRS)
## Project 19: Daily Standup Bot (Productivity)

### 1. Project Description
The Daily Standup Bot automates the routine of agile daily standups for remote and asynchronous teams. Team members submit their standup answers (What did you do yesterday? What will you do today? Any blockers?) via a web portal, and the bot compiles, summarizes, and broadcasts the updates to the team's communication channels (like Slack or Email).

### 2. Core Scope
The system involves scheduled triggers, a form-based user interface, an AI summarization module to condense verbose answers, and external API integrations for broadcasting.

### 3. Functionalities (Minimum 25)

#### User & Team Management
1. **User Authentication:** Login via Google Workspace or Microsoft 365.
2. **Team Creation:** Group users into specific agile teams or squads.
3. **Role Assignment:** Designate Scrum Masters (Admins) and Team Members.
4. **Timezone Support:** Handle teams across multiple timezones, prompting users at their local morning time.

#### Standup Configuration
5. **Custom Questions:** Admins can modify the default 3 standup questions to fit their team's specific needs.
6. **Schedule Setting:** Define the days of the week and the exact time the bot prompts the team.
7. **Deadline Setting:** Set a cutoff time (e.g., 10:00 AM) by which all members must submit.
8. **Reminder Configuration:** Automatically ping users who haven't submitted 30 minutes before the deadline.

#### Submission Interface
9. **Web Form Submission:** A clean, mobile-friendly interface to quickly type answers.
10. **Draft Saving:** Auto-save answers as the user types before final submission.
11. **Blocker Highlighting:** A specific toggle to explicitly flag if the user is blocked, visually differentiating the report.
12. **Rich Text Support:** Allow bullet points and basic formatting in the answers.
13. **Vacation/Ooo Toggle:** A button to easily mark oneself as "Out of Office," skipping the standup for the day.

#### Summarization & Broadcasting
14. **AI Condensation:** Use AI to turn long, rambling answers into concise bullet points.
15. **Blocker Extraction:** Automatically pull all "blockers" from everyone's updates and list them at the top of the summary report.
16. **Email Broadcast:** Send the compiled summary to a designated mailing list.
17. **Slack/Teams Integration:** Post the final report into a specific Slack channel or MS Teams group.
18. **Individual History Viewer:** Allow users to view their own past submissions to remember what they worked on last week.

#### Tracking & Analytics
19. **Participation Dashboard:** Scrum Masters can see a calendar view of who submitted and who missed standups.
20. **Blocker Frequency Stats:** Track how often specific team members or projects are blocked.
21. **Mood Tracking (Optional):** Ask users to rate their current stress level (1-5) and aggregate team morale over time.
22. **Export Reports:** Export weekly or monthly standup logs for sprint retrospectives.

#### System Features
23. **Webhook Endpoints:** Allow external tools (like Jira) to auto-populate the "What I did yesterday" field based on closed tickets.
24. **Admin Panel:** Manage billing, view total API usage, and handle support tickets.
25. **Dark Mode:** A dark theme option for the web submission interface.
