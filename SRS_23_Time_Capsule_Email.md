# Software Requirements Specification (SRS)
## Project 23: Time-Capsule Email Scheduler (Productivity)

### 1. Project Description
The Time-Capsule Email Scheduler is a unique web application that allows users to write emails to themselves or others and schedule them to be sent far into the future—whether that's 1 month, 1 year, or 10 years later. It serves as a digital time capsule for goal setting, memories, or future reminders.

### 2. Core Scope
The application relies on robust background job scheduling (e.g., cron jobs, BullMQ), secure data storage to ensure long-term preservation of the emails, and an intuitive, nostalgic user interface.

### 3. Functionalities (Minimum 25)

#### Email Creation
1. **Rich Text Editor:** A robust editor allowing formatting, lists, and embedded links.
2. **Media Attachments:** Allow users to attach photos, audio clips, or small video files to their time capsules.
3. **Recipient Management:** Users can address the email to themselves or enter multiple email addresses for friends/family.
4. **Subject Line Generator:** Optional AI suggestions for creative subject lines based on the content.
5. **Draft Auto-Saving:** Automatically save progress to prevent data loss while writing long letters.

#### Scheduling & Timing
6. **Date Picker:** Select a precise future date using a calendar interface.
7. **Preset Timers:** Quick-select buttons for "1 Year", "5 Years", "On my 30th Birthday", etc.
8. **Timezone Accuracy:** Ensure the email is sent exactly at the local timezone time specified by the user.
9. **Recurring Capsules:** Option to send the exact same email every year on a specific date.
10. **Delivery Confirmation Check:** A system to handle bounced emails if a recipient's address no longer exists 10 years later.

#### User Dashboard & Organization
11. **User Registration/Login:** Secure accounts to manage pending and sent capsules.
12. **Capsule Vault:** A dashboard showing all upcoming scheduled emails (content is locked/hidden to preserve the surprise, showing only the send date).
13. **Sent History:** An archive of time capsules that have already been delivered.
14. **Edit Before Sending:** Allow users to edit or delete a scheduled email up until 24 hours before delivery.
15. **Tags & Categories:** Organize capsules by theme (e.g., "Career Goals", "To my kids", "Predictions").

#### Advanced & Premium Features
16. **Public Gallery (Optional):** Users can opt to make their time capsule public anonymously once it opens, for others to read.
17. **Dead Man's Switch:** Send specific emails automatically if the user does not log into the app for a set period (e.g., 1 year).
18. **Physical Letter Option:** (Premium) Partner with a printing API to send a physical, printed letter instead of an email.
19. **Video Capsule:** (Premium) Direct webcam recording within the app to send a video message.

#### Security & Infrastructure
20. **End-to-End Encryption:** Encrypt the content of the emails in the database so not even the database admins can read them.
21. **Robust Queue Management:** A highly reliable background worker system to process the daily queue of emails to send.
22. **Spam Compliance:** Ensure the outgoing email servers comply with anti-spam regulations (Unsubscribe links for third-party recipients).
23. **Email Verification:** Require users to verify their email address before sending capsules to themselves.

#### Admin & System Health
24. **Delivery Analytics:** Admin dashboard tracking delivery success rates, bounce rates, and open rates.
25. **Storage Management:** Monitor server storage for media attachments and implement auto-scaling solutions.
