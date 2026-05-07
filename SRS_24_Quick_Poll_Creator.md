# Software Requirements Specification (SRS)
## Project 24: Quick Poll Creator for Teams (Productivity)

### 1. Project Description
The Quick Poll Creator is a lightweight, blazing-fast web application designed for teams to make decisions quickly. It allows users to create polls with deadlines, share them via a simple link, and view live results with dynamic charts, without requiring participants to create an account.

### 2. Core Scope
The platform focuses on frictionless UX, real-time data updates using WebSockets, and generating clean, responsive data visualizations for the results.

### 3. Functionalities (Minimum 25)

#### Poll Creation
1. **Frictionless Creation:** Ability to create a basic poll directly from the homepage without logging in.
2. **Question Types:** Support for Multiple Choice, Single Choice, and Ranking (drag-and-drop order).
3. **Image Options:** Allow creators to attach an image to each polling option (great for design feedback).
4. **Add/Remove Options:** Dynamic form fields to add as many choices as needed.
5. **Deadline Configuration:** Set a specific date and time for the poll to automatically close.

#### Poll Settings & Security
6. **Anonymous Voting:** Toggle to allow users to vote without providing a name.
7. **Name Requirement:** Toggle to require voters to input a name (or link to a Slack/Discord identity).
8. **IP/Cookie Tracking:** Prevent duplicate voting by checking IPs and setting local cookies.
9. **Result Visibility Settings:** Choose to show results "Always", "Only after voting", or "Only to the creator".
10. **Password Protection:** Lock a poll behind a custom password for sensitive team decisions.

#### Voting Experience
11. **Shareable Link Generation:** Instantly generate a short URL and a QR code for the poll.
12. **Mobile-Optimized Interface:** Ensure the voting screen is highly responsive and easy to tap on mobile devices.
13. **Real-Time Updates:** As soon as someone votes, the results chart updates instantly for everyone viewing the page.
14. **Change Vote:** Allow users to change their vote before the deadline (if cookies/accounts are enabled).
15. **Comments Section:** A mini-chat or comment thread below the poll for voters to explain their choice.

#### Results & Analytics
16. **Dynamic Data Visualizations:** Display results using Pie charts, Bar charts, or Donut charts (using libraries like Chart.js).
17. **Export Data:** Allow the creator to export the raw voting data as a CSV file.
18. **Winning Option Highlight:** Clearly highlight the winning option once the poll is closed.
19. **Voter Demographics (If collected):** Show a breakdown of votes by department or role, if that data was requested.

#### User Accounts (Optional for creators)
20. **Creator Dashboard:** A dashboard for registered users to see all their past and active polls.
21. **Poll Duplication:** Easily clone a past poll to run it again (e.g., weekly lunch vote).
22. **Integration Webhooks:** Post the poll directly into a Slack channel or Discord server via Webhooks.

#### Admin & Maintenance
23. **Auto-Cleanup:** Automatically delete anonymous/guest polls 30 days after they close to save database space.
24. **Spam Detection:** Built-in rate limiting to prevent bot scripts from flooding a poll with votes.
25. **Admin Panel:** Monitor active polls, server load, and manage reported/inappropriate content.
