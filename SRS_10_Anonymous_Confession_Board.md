# Software Requirements Specification (SRS)
## Project 10: Anonymous Confession Board (Social Impact)

### 1. Project Description
The Anonymous Confession Board is a safe, community-driven platform where users can share their secrets, thoughts, and confessions completely anonymously. The system incorporates mood-based categorizations, upvoting for relatability, and strict moderation tools to ensure the environment remains supportive and free of cyberbullying.

### 2. Core Scope
The application focuses on anonymity, community interaction (voting and commenting), and robust content moderation. It requires careful database design to ensure IP addresses and user identities are not linked to their posts.

### 3. Functionalities (Minimum 25)

#### Core Posting & Browsing
1. **Anonymous Posting:** Submit text confessions without requiring an account.
2. **Mood/Category Tagging:** Categorize posts by mood (e.g., Happy, Sad, Guilty, Funny) or topics (e.g., School, Work, Relationships).
3. **Feed Sorting:** Sort the main feed by "Newest," "Most Relatable (Top)," or "Trending."
4. **Mood-Based Filtering:** Allow users to filter the feed to only see confessions of a specific mood.
5. **Character Limit Enforcement:** Restrict post length (e.g., max 500 characters) to keep content concise.

#### Community Interaction
6. **Relatability Voting:** "Relate" or "Hug" buttons instead of traditional upvotes/likes to foster a supportive environment.
7. **Anonymous Commenting:** Allow users to leave supportive comments anonymously.
8. **Comment Threads:** Support threaded replies for deeper conversations.
9. **Share Confession:** Generate a stylized image of the confession for sharing on other social networks.
10. **Save Confession:** (If using local storage/cookies) Allow users to bookmark posts they resonate with.

#### User Safety & Moderation
11. **Automated Profanity Filter:** Block or censor posts containing hate speech or severe profanity before they go live.
12. **Trigger Warning Tags:** Allow posters to add predefined trigger warnings (e.g., TW: Mental Health) which blur the content until clicked.
13. **User Reporting System:** Allow readers to flag posts or comments that violate community guidelines.
14. **Auto-Hide Threshold:** Automatically hide posts that receive a high number of reports pending admin review.
15. **Crisis Resources Integration:** Automatically display links to mental health hotlines if specific keywords (e.g., "suicide", "depressed") are detected.

#### Optional User Accounts
16. **Pseudonymous Registration:** Users can create an account using just a username and password (no email required) to track their own posts.
17. **My Posts Dashboard:** View the engagement (votes/comments) on one's own confessions.
18. **Notification System:** Get in-app alerts when someone replies to your confession or comment.
19. **Account Deletion:** Instantly delete all associated posts and comments if the user chooses to delete their account.

#### System & Admin Features
20. **Admin Authentication:** Secure login for platform moderators.
21. **Moderation Queue:** Dashboard for admins to review flagged posts and comments.
22. **Ban Management:** Ability for admins to shadow-ban or IP-ban abusive users.
23. **Analytics Dashboard:** View daily active users, post volume, and the most common moods.
24. **Custom Avatars:** Assign randomized, abstract avatars to commenters to differentiate users in a thread without revealing identity.
25. **Dark Mode Interface:** A soothing dark mode design to fit the late-night confession aesthetic.
