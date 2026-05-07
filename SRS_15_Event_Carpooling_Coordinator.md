# Software Requirements Specification (SRS)
## Project 15: Event Carpooling Coordinator (Social Impact)

### 1. Project Description
The Event Carpooling Coordinator is an eco-friendly platform designed to reduce traffic and carbon emissions around major events (concerts, conferences, festivals). It matches attendees heading to the same venue, allowing them to coordinate rides, share costs, and network.

### 2. Core Scope
The application focuses on event listing, geographic matching (origins to a common destination), ride offering/requesting, and secure user communication.

### 3. Functionalities (Minimum 25)

#### User Authentication
1. **User Registration:** Sign up via Email, Google, or Facebook.
2. **User Profile:** Add vehicle details (for drivers), music preferences, and bio to facilitate better matching.
3. **Verification System:** ID or Social Media linking to ensure safety and trust among riders.
4. **Driver/Rider Toggle:** Users can switch roles depending on the event.

#### Event Management
5. **Event Browsing:** A dashboard listing upcoming events, concerts, or conferences.
6. **Search & Filter Events:** Search events by date, city, or category.
7. **Add Custom Event:** Users can create a private or public event if it's not listed.
8. **Event Details Page:** Displays venue map, date/time, and a list of available rides going to this event.

#### Ride Creation & Booking
9. **Offer a Ride:** Drivers input their starting location, departure time, available seats, and cost per seat (if any).
10. **Request a Ride:** Riders post their starting location and desired arrival time to request a pickup.
11. **Route Mapping:** Integration with Google Maps/Mapbox APIs to visualize the route and potential pickup points.
12. **Seat Booking System:** Riders can click "Request Seat"; driver receives a notification to approve or decline.
13. **Auto-Matching Algorithm:** System suggests the closest drivers to a rider's starting point heading to the same event.

#### Ride Coordination
14. **In-App Group Chat:** A dedicated chat room for the driver and approved riders for a specific trip.
15. **Live Location Sharing:** (Optional) Temporarily share GPS location within the app 1 hour before pickup.
16. **Itinerary Management:** Display exact pickup locations, times, and vehicle license plate details.
17. **Cancel Booking/Ride:** Handled workflows for when a driver or rider cancels, including automated notifications to affected parties.

#### Safety & Feedback
18. **SOS Button:** In-app emergency button that sends ride details to a designated emergency contact.
19. **Post-Ride Ratings:** Rate drivers on safety/punctuality and riders on behavior.
20. **Written Reviews:** Leave public reviews on user profiles.
21. **Report User:** Flag inappropriate behavior or no-shows to admins.

#### Financials & Admin
22. **Cost Splitting Calculator:** Automatically suggest a fair split based on distance and fuel estimates.
23. **Payment Integration (Stripe/PayPal):** Securely transfer gas money through the app.
24. **Admin Dashboard:** Monitor platform usage, manage events, and handle user reports.
25. **Analytics:** Track total carbon emissions saved through carpooling.
26. **Email/SMS Alerts:** Reminders sent 24 hours and 1 hour before the scheduled departure.
