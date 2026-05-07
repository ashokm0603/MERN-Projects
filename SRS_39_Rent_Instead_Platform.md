# Software Requirements Specification (SRS)
## Project 39: Rent-Instead-of-Buy Platform (Commerce)

### 1. Project Description
This peer-to-peer marketplace encourages a circular economy by allowing individuals to rent out items they own but rarely use (e.g., power tools, camping gear, high-end cameras) to their neighbors by the day. It includes robust verification, security deposits, and availability calendars.

### 2. Core Scope
The system requires dual user roles (Owner and Renter), date-based inventory management, location-based search, and a complex payment flow involving security deposits/holds.

### 3. Functionalities (Minimum 25)

#### User Authentication & Trust
1. **User Registration:** Signup via email, Google, or phone number.
2. **Identity Verification:** Mandatory KYC (Know Your Customer) upload of a government ID to prevent theft.
3. **User Profiles:** Display profile picture, bio, location, and aggregate review scores.
4. **Trust Badges:** Badges for "Verified ID", "Fast Responder", or "Top Lender".

#### Item Listing & Browsing
5. **Create Listing:** Upload multiple photos, describe the item, its condition, and specify replacement value.
6. **Dynamic Pricing:** Set a daily, weekly, or monthly rental rate.
7. **Category Management:** Browse items by specific categories (Tools, Electronics, Outdoors, Party Supplies).
8. **Map-Based Search:** Search for items visually on an interactive map showing approximate locations (within a 1-mile radius for privacy).
9. **Availability Calendar:** Owners block out dates when they need the item themselves, or when it's already booked.

#### Booking & Rental Flow
10. **Date Picker:** Renters select a start and end date; the system automatically calculates the total cost.
11. **Booking Request:** Renters submit a request; Owners have 24 hours to accept or decline.
12. **Instant Book Option:** Owners can toggle 'Instant Book' for trusted renters, bypassing the manual approval step.
13. **Security Deposit Hold:** The payment gateway places a hold (authorization) on the renter's credit card for the item's replacement value during the rental period.
14. **In-App Messaging:** Secure chat to arrange exact pickup and drop-off times/locations.
15. **Rental Contract Generation:** Auto-generate a simple digital agreement summarizing the dates, condition, and late fees.

#### Item Handoff & Return
16. **Condition Photos (Pre-Rental):** Both parties upload time-stamped photos of the item at the moment of handoff to document its current condition.
17. **QR Code Handshake:** Renter scans a QR code on the Owner's phone to officially mark the rental as "Started."
18. **Late Return Penalties:** System automatically charges predefined late fees per day if the item is not returned on time.
19. **Condition Photos (Post-Rental):** Photos taken upon return to verify no damage occurred.
20. **Deposit Release:** Automatically release the security deposit hold 24 hours after a successful return if no damage is reported.

#### Reviews & Dispute Resolution
21. **Two-Way Rating:** Owners rate Renters (on punctuality and care), and Renters rate Owners (on item accuracy and communication).
22. **Damage Claim Form:** An interface for the Owner to submit a claim, holding the deposit while admins review the pre/post rental photos.
23. **Insurance Integration (Optional):** Offer a premium daily insurance fee that waives the security deposit for the renter.

#### System & Admin Features
24. **Admin Dashboard:** Monitor all active rentals, mediate disputes, and ban fraudulent accounts.
25. **Tax & Earnings Reports:** Owners can download a summary of their rental income for tax purposes.
