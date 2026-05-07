# Software Requirements Specification (SRS)
## Project 6: Smart Meeting Summarizer (AI-Powered)

### 1. Project Description
The Smart Meeting Summarizer is an AI-driven platform designed to boost productivity by converting raw meeting transcripts or audio recordings into structured, actionable insights. The system automatically extracts key decisions, action items, and generates professional follow-up emails, saving teams hours of manual note-taking.

### 2. Core Scope
The platform handles audio processing, transcript parsing, AI summarization, and email integration. It targets business professionals, project managers, and remote teams who rely heavily on video conferencing.

### 3. Functionalities (Minimum 25)

#### User Account & Integration
1. **User Authentication:** Secure login using Email, Google Workspace, or Microsoft 365.
2. **Profile Management:** Manage user details and preferred email signature.
3. **Calendar Integration:** Sync with Google Calendar/Outlook to automatically fetch upcoming meetings.
4. **Zoom/Meet Integration:** Webhooks or bot integration to automatically pull transcripts after a meeting.

#### Meeting Input Methods
5. **Audio/Video Upload:** Upload recorded meeting files (.mp4, .mp3, .wav) for processing.
6. **Transcript Paste:** Direct text input for pasting raw VTT or text transcripts.
7. **Live Microphone Capture:** Option to record audio directly from the browser during an in-person meeting.
8. **Multi-Speaker Diarization:** AI capability to distinguish between different speakers (Speaker A, Speaker B).

#### AI Summarization Engine
9. **Executive Summary Generation:** Create a brief 1-2 paragraph overview of the entire meeting.
10. **Action Items Extraction:** Automatically list tasks and assign them to the mentioned individuals.
11. **Key Decisions Log:** Highlight finalized decisions and agreements made during the call.
12. **Sentiment Analysis:** Analyze the overall tone of the meeting (positive, neutral, conflicting).
13. **Custom Topic Extraction:** Identify and tag main topics/keywords discussed.

#### Document & Email Management
14. **Follow-Up Email Drafter:** Auto-generate a formatted email containing the summary and action items.
15. **Email Sending:** Send the follow-up email directly from the app via integrated email APIs.
16. **Export to Docs:** Export summaries to Notion, Google Docs, or download as PDF/Word.
17. **Template Customization:** Allow users to customize the format of the output summaries and emails.

#### Organization & Search
18. **Meeting Dashboard:** A centralized hub displaying all past meetings and their status.
19. **Global Search:** Full-text search across all transcripts, summaries, and action items.
20. **Tagging & Folders:** Organize meetings by project, client, or department.
21. **Meeting Sharing:** Generate shareable links to send summaries to stakeholders who weren't in the meeting.

#### Collaboration & Editing
22. **Manual Editing:** A rich-text editor to manually tweak the AI-generated summary before sharing.
23. **Comments Section:** Allow team members to comment on the summary or clarify action items.
24. **Task Status Tracking:** Mark action items as 'Pending', 'In Progress', or 'Completed' within the app.

#### Security & System Features
25. **Data Privacy Controls:** Auto-delete audio files after transcription to maintain confidentiality.
26. **Subscription Management:** Stripe integration for handling free trials and premium tiers (based on audio minutes).
27. **Admin Panel:** Monitor user activity, storage limits, and manage billing.
