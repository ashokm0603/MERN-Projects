# Software Requirements Specification (SRS)
## Project 14: Freelancer Project Board (Social Impact)

### 1. Project Description
The Freelancer Project Board is a localized micro-gig platform designed to connect small business owners and individuals with local freelancers. Users can post short-term projects with specific budgets, while freelancers can bid, showcase their portfolios, and communicate in real-time. It emphasizes fair wages and skill-building for junior freelancers.

### 2. Core Scope
The platform requires dual user roles (Client and Freelancer), a bidding/proposal system, real-time chat, and a robust rating and review mechanism.

### 3. Functionalities (Minimum 25)

#### User Authentication & Roles
1. **Dual Role Registration:** Users can sign up as a 'Client' (posting jobs) or a 'Freelancer' (bidding on jobs).
2. **Profile Creation (Freelancer):** Upload portfolio links, list skills, set hourly rates, and add a bio.
3. **Profile Creation (Client):** Company/Individual details, location, and past project history.
4. **OAuth Login:** Support for Google/LinkedIn authentication.
5. **Identity Verification:** (Optional) Basic KYC or phone number verification to build trust.

#### Project Management (Client)
6. **Post a Project:** Form detailing project title, description, required skills, deadline, and budget range.
7. **Drafts:** Save incomplete project postings to publish later.
8. **Manage Bids:** View a dashboard of all proposals received for a specific project.
9. **Accept/Reject Proposals:** Interface to accept a bid, automatically notifying the freelancer.
10. **Close/Cancel Project:** Ability to remove a project if filled externally or no longer needed.

#### Bidding & Searching (Freelancer)
11. **Job Feed Dashboard:** Browse available projects sorted by date, budget, or relevance.
12. **Advanced Filters:** Filter projects by required skills, fixed-price vs. hourly, and budget brackets.
13. **Submit Proposal:** Write a cover letter, propose a specific price, and estimate delivery time.
14. **Withdraw Bid:** Cancel a submitted proposal before the client accepts it.
15. **Saved Jobs:** Bookmark interesting projects to apply for later.

#### Communication & Collaboration
16. **Real-Time Chat:** WebSocket-based messaging system for clients and freelancers to discuss project details.
17. **File Sharing:** Upload and share documents, images, or code snippets within the chat.
18. **Milestone Tracking:** Break down accepted projects into deliverable milestones.
19. **Status Updates:** Freelancers can update the project status (e.g., Not Started, In Progress, Under Review).

#### Feedback & Payments
20. **Rating & Reviews:** Both parties leave a 1-5 star rating and written review after project completion.
21. **Dispute Resolution Flow:** A form to flag issues or request admin intervention if a project goes wrong.
22. **Escrow Integration (Stripe):** (Optional/Mock) Hold client funds securely until milestones are approved.
23. **Earnings Dashboard:** Freelancers can view their total earnings, pending payouts, and completed jobs.

#### Admin & System Features
24. **Admin Panel:** Manage users, resolve disputes, and monitor active projects.
25. **Skill Tag Management:** Admins maintain the standard list of selectable skills (e.g., React, Graphic Design).
26. **Email Notifications:** Alerts for new bids, messages, and project awards.
