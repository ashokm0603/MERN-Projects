# Software Requirements Specification (SRS)
## Project 33: Hyper-Local Services Marketplace (Commerce)

### 1. Project Description
This platform connects residents with trusted, hyper-local service providers (e.g., plumbers, electricians, tutors, house cleaners) operating within a specific neighborhood or city radius. It streamlines the process of finding help, booking appointments, and securely processing payments, acting as an 'Uber for local services'.

### 2. Core Scope
The platform requires dual user interfaces (Customer and Provider), scheduling calendars, geographic search/filtering, and a secure payment gateway with escrow capabilities.

### 3. Functionalities (Minimum 25)

#### Customer Features
1. **Geolocation Search:** Automatically detect the user's location and show service providers within a 5, 10, or 20-mile radius.
2. **Category Browsing:** Browse clearly defined categories (Home Repair, Cleaning, Tutoring, Beauty).
3. **Provider Profiles:** View provider details, past work photos, hourly rates, and verified reviews.
4. **Real-Time Availability:** View a calendar showing exactly when a provider is available to be booked.
5. **Instant Booking:** Select a time slot and immediately request a service appointment.

#### Service Provider Features
6. **Provider Registration:** A comprehensive onboarding flow including ID verification and background check uploads.
7. **Service Listing Creation:** Define services offered, set pricing (fixed or hourly), and upload portfolio images.
8. **Calendar Management:** Sync with Google Calendar or manually block out unavailable dates and times.
9. **Booking Management Dashboard:** Accept, decline, or reschedule incoming service requests.
10. **Earnings Dashboard:** Track completed jobs, pending payouts, and total revenue.

#### Communication & Tracking
11. **In-App Messaging:** Secure chat interface for customers and providers to discuss specific job details before arrival.
12. **Photo/Video Sharing:** Customers can send pictures of the problem (e.g., a broken pipe) through the chat.
13. **Status Updates:** Provider can update the job status (e.g., "On the way", "Arrived", "Work in progress", "Completed").
14. **Push/SMS Notifications:** Real-time alerts for booking confirmations, messages, and arrivals.

#### Payments & Security
15. **Integrated Checkout:** Customers pay via credit card (Stripe integration) within the app.
16. **Pre-Authorization:** Hold funds on the customer's card when the booking is accepted, capturing them only when the job is marked complete.
17. **Tipping Option:** Allow customers to add a tip to the final bill after exceptional service.
18. **Refund & Dispute Flow:** A dedicated form for customers to request a refund or mediate a dispute involving an admin.
19. **Automated Payouts:** Automatically route the provider's cut to their bank account (e.g., Stripe Connect) weekly.

#### Reviews & Trust
20. **Verified Reviews:** Only customers who have actually booked and paid through the platform can leave a rating (1-5 stars) and text review.
21. **Provider Badges:** System-assigned badges for "Top Rated," "Fast Responder," or "Background Checked."
22. **Favorites List:** Customers can save their favorite providers for easy rebooking in the future.

#### Admin & System Architecture
23. **Admin Dashboard:** Monitor all transactions, active bookings, and moderate user disputes.
24. **Commission Engine:** Configure the platform fee percentage (e.g., 10%) taken from each transaction.
25. **Analytics & Heatmaps:** Admins can view geographic heatmaps of where the most service requests are originating to target marketing efforts.
