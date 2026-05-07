# Software Requirements Specification (SRS)
## Project 41: Peer Tutoring Marketplace (Education)

### 1. Project Description
The Peer Tutoring Marketplace connects students who excel in specific subjects with peers who need academic help. It provides a platform to offer tutoring services, book one-on-one sessions, and process payments securely, fostering a collaborative, peer-to-peer learning environment.

### 2. Core Scope
The platform features dual user roles (Tutor and Student), an integrated scheduling system, video call integration, and an internal rating system to ensure quality.

### 3. Functionalities (Minimum 25)

#### Profile & Search
1. **User Registration:** Signup using university `.edu` emails to verify student status.
2. **Dual Profiles:** Users can easily toggle between being a 'Tutor' and a 'Student' on the same account.
3. **Tutor Profile Creation:** Input major, GPA, subjects offered, hourly rate, and a short intro bio.
4. **Subject Search:** Search bar with auto-complete for specific course codes (e.g., "MATH 101" or "Organic Chemistry").
5. **Advanced Filtering:** Filter search results by price, rating, and availability (online vs. in-person).

#### Scheduling & Booking
6. **Availability Calendar:** Tutors can sync their Google Calendar to block out times they are in class.
7. **Session Booking Flow:** Students select an open time slot, define the topic they need help with, and submit a request.
8. **Request Approval:** Tutors receive a notification to accept or decline the booking request within 24 hours.
9. **Rescheduling:** A flow allowing either party to propose a new time if a conflict arises.
10. **Automated Reminders:** Email and push notifications sent 24 hours and 1 hour before the session starts.

#### Communication & Video Integration
11. **In-App Chat:** Secure messaging system for students to clarify their needs before the session begins.
12. **File Sharing:** Upload syllabi, past exams, or assignments within the chat for the tutor to review beforehand.
13. **Zoom/Meet Integration:** Automatically generate and attach a unique video conference link to the booking once approved.
14. **Whiteboard Integration:** (Optional) An embedded collaborative whiteboard for real-time math/diagram solving.

#### Payments & Earnings
15. **Secure Checkout:** Stripe integration for students to pay for the session upfront (held in escrow).
16. **Session Completion Toggle:** Both parties must click "Session Completed" to release the funds to the tutor.
17. **Dispute System:** A button to pause payment if a tutor doesn't show up, triggering admin review.
18. **Earnings Dashboard:** Tutors can view their total earnings, pending payouts, and set up direct deposit.
19. **Promo Codes:** Platform-issued discount codes for first-time students.

#### Reviews & Trust
20. **Post-Session Rating:** Mandatory 1-5 star rating prompt after a session concludes.
21. **Written Reviews:** Students can leave a public text review displayed on the tutor's profile.
22. **Verified "A" Grade Badge:** Tutors can upload an unofficial transcript to get a verified badge for specific subjects.
23. **Favorites List:** Students can bookmark great tutors for easy rebooking before midterms/finals.

#### Admin & System Features
24. **Admin Dashboard:** Monitor all bookings, mediate payment disputes, and ban no-show users.
25. **Analytics Dashboard:** Admins can view the most popular subjects searched to focus marketing efforts.
