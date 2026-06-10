# Software Requirements Specification (SRS)
## Project 9: Community Skill Swap Platform (Social Impact)

### 1. Project Description
The Community Skill Swap Platform is a peer-to-peer barter network that connects individuals who want to exchange skills and services without any monetary transaction. A user who is proficient in web design can offer their services in exchange for guitar lessons from another user, for example. The platform eliminates financial barriers to learning and service-seeking, fostering a community of mutual growth and support.

### 2. Core Scope
The application focuses on skill listing, swap request management, mutual matching, real-time communication, and community reputation building. It relies on a fair barter mechanism where users negotiate and agree on skill-for-skill exchanges, tracked through an agreement and completion workflow.

### 3. Functionalities (Minimum 25)

#### User Profiles & Skill Listings
1. **User Registration & Profile Creation:** Secure account creation with name, bio, location, profile photo, and availability schedule.
2. **Skill Offering Listings:** Users create listings for skills they can teach or provide (e.g., "Python Tutoring," "Logo Design," "Yoga Instruction"), including description, proficiency level, and estimated time per session.
3. **Skill Seeking Listings:** Users also list skills they are looking to learn or receive in exchange.
4. **Portfolio Showcase:** Users can attach links, images, or documents as proof of their skill proficiency (e.g., GitHub link for developers, photos for artists).
5. **Availability Calendar:** Set and display weekly availability so potential swap partners can schedule sessions accordingly.

#### Discovery & Matching
6. **Skill Search & Browse:** Full-text search and category-based browsing (e.g., Technology, Arts, Languages, Fitness, Cooking) to discover available skill offerings.
7. **AI-Powered Match Recommendations:** Automatically suggest compatible users whose offered skills match the seeker's needs and vice versa.
8. **Location-Based Filtering:** Filter potential swap partners by city or radius for in-person skill sessions.
9. **Tag-Based Filtering:** Filter listings by skill tags, proficiency level (Beginner, Intermediate, Expert), and session format (Online/In-Person).
10. **Saved Listings:** Bookmark interesting skill offerings to revisit later.

#### Swap Request & Agreement
11. **Swap Request Initiation:** Send a formal swap proposal to another user specifying the skills offered, skills requested, and proposed session structure.
12. **Counter-Offer System:** Recipients can accept, decline, or counter-propose a swap with modified terms.
13. **Swap Agreement Confirmation:** Both parties must explicitly confirm the final agreement before the swap is officially scheduled.
14. **Swap Details Summary:** A clear summary page showing both parties' commitments, session dates, format, and duration.

#### Communication
15. **In-App Messaging:** Real-time private messaging system between matched users to discuss swap details.
16. **Session Video Link Sharing:** Securely share video call links (Zoom, Google Meet) directly within the chat for online sessions.
17. **Notification System:** Real-time in-app and email notifications for swap requests, messages, confirmations, and reminders.

#### Reputation & Community
18. **Post-Swap Review System:** After a swap is completed, both parties rate and review each other on criteria like skill quality, punctuality, and communication.
19. **Reputation Score & Badges:** Aggregate reviews into a reputation score; award badges for milestones (e.g., "10 Swaps Completed," "Top Rated Teacher").
20. **Community Feed:** A public activity feed showing recent swaps, new member introductions, and skill spotlights.
21. **Dispute Resolution System:** A formal process for reporting and resolving disputes about swap quality or no-shows.

#### Admin & Platform Management
22. **Admin Dashboard:** Monitor platform activity, flagged content, new registrations, and reported disputes.
23. **Content Moderation:** Review and remove inappropriate skill listings or user profiles.
24. **Swap Analytics:** Track total swaps completed, most popular skill categories, and user engagement metrics.
25. **User Verification Badge:** Provide an optional identity verification process to increase trust between swap partners.
