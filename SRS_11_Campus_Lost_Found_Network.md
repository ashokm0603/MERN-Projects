# Software Requirements Specification (SRS)
## Project 11: Campus Lost & Found Network (Social Impact)

### 1. Project Description
The Campus Lost & Found Network is a hyperlocal platform designed for university students and staff. It streamlines the process of returning lost items by allowing users to post found items with photos and descriptions. Claimants must verify their identity and ownership via an OTP or specific security questions before the exact location or finder's contact is revealed.

### 2. Core Scope
The application focuses on image uploads, geographic/campus tagging, search functionality, and a secure communication/verification channel between the finder and the loser.

### 3. Functionalities (Minimum 25)

#### User Authentication
1. **University Email Verification:** Restrict registration to users with a valid `.edu` or specific campus email address.
2. **User Profile:** Manage contact information, department/major, and notification preferences.
3. **Login/Logout:** Secure session management.
4. **Password Reset:** Standard email-based password recovery.

#### Item Posting
5. **Report Found Item:** Form to upload images, select category (Electronics, IDs, Clothing), and describe where it was found.
6. **Report Lost Item:** Form to describe a lost item, approximate time/location, and offer an optional reward.
7. **Location Tagging:** Select specific campus buildings, cafeterias, or grounds from a predefined dropdown or interactive campus map.
8. **Image Blurring (Privacy):** Option to automatically blur sensitive items (like ID cards or wallets) until ownership is verified.
9. **Time & Date Picker:** Accurately log when the item was lost or found.

#### Searching & Browsing
10. **Main Dashboard:** Separate feeds for "Lost" and "Found" items.
11. **Advanced Search & Filters:** Filter by category, date range, or specific campus building.
12. **Keyword Search:** Search descriptions and titles for specific items (e.g., "Airpods", "Blue Bottle").
13. **Status Badges:** Clearly display if an item is "Active," "Claim Pending," or "Resolved."

#### Claiming & Verification
14. **Initiate Claim:** Users can click "This is mine" on a found item.
15. **Security Questionnaire:** Finders can set 1-2 hidden questions (e.g., "What is the background image on the phone?") that the claimant must answer.
16. **OTP Verification:** System sends a One-Time Password to the claimant's verified student email to prevent spam claims.
17. **In-App Messaging:** Secure chat interface between the finder and verified claimant to arrange a meetup, without exposing personal phone numbers.

#### Notifications & Tracking
18. **Match Alerts:** Notify a user if a newly "Found" item matches the category and location of their "Lost" report.
19. **Email Notifications:** Alerts for new messages, claim approvals, or status changes.
20. **My Items Dashboard:** A centralized view of all items a user has reported lost or found.
21. **Mark as Resolved:** Once returned, both parties confirm the exchange, moving the item to the archive.

#### Admin & System Features
22. **Admin Dashboard:** Monitor overall activity, unresolved items, and user reports.
23. **Moderation Tools:** Ability to delete inappropriate posts or ban malicious users.
24. **Category Management:** Admins can add or modify the list of campus buildings and item categories.
25. **Success Stories/Stats:** Public display of statistics (e.g., "500 items returned this semester") to encourage platform use.
