# Software Requirements Specification (SRS)
## Project 34: Group Buy Organizer (Commerce)

### 1. Project Description
The Group Buy Organizer is a collaborative commerce platform that enables friends, communities, or online groups to coordinate bulk purchases of products in order to collectively meet the minimum order quantity required to unlock wholesale or group-discount pricing. An organizer creates a group buy for a specific product, shares it with their network, collects commitments and payments, and then places a single bulk order — passing the savings on to every participant.

### 2. Core Scope
The application focuses on group buy creation, participant recruitment, commitment tracking, payment collection, order status management, and transparent financial handling. It requires robust payment flow management to handle collections from multiple individuals and clear communication throughout the buying process.

### 3. Functionalities (Minimum 25)

#### Group Buy Creation (Organizer)
1. **Group Buy Listing Creator:** Create a group buy with product name, description, photos, vendor source link, individual unit price, group price per unit, minimum quantity required, and deadline.
2. **Tier-Based Pricing:** Define multiple price tiers based on total quantity ordered (e.g., 10–20 units: ₹500/unit; 21–50 units: ₹420/unit).
3. **Maximum Quantity Cap:** Set a maximum number of units the group buy will accept to prevent overloading the vendor.
4. **Duration Setting:** Set a start and end date for the group buy recruitment period.
5. **Category Tagging:** Categorize the group buy (e.g., Electronics, Food & Grocery, Clothing, Books, Supplements).

#### Discovery & Participation
6. **Public Group Buy Feed:** Browse active group buys by category, location, popularity, and time remaining.
7. **Search & Filter:** Search for specific products or filter by category, minimum order size, and proximity.
8. **Join & Commit:** Any user can join an active group buy by specifying the number of units they want and committing to the purchase.
9. **Commitment Confirmation:** Upon joining, participants receive a confirmation email summarizing their commitment (product, units, expected price, and deadline).
10. **Waitlist Feature:** Once a group buy hits its maximum capacity, additional interested users can join a waitlist.

#### Progress Tracking & Communication
11. **Live Progress Bar:** A visual bar showing the current number of committed units against the minimum target, updating in real time.
12. **Countdown Timer:** Display a live countdown to the group buy deadline.
13. **Participant Feed:** A list of anonymous participant names and unit quantities (to build social proof and urgency).
14. **Organizer Announcements:** The organizer can post updates (e.g., "Order placed!" or "Delivery expected next week") visible to all participants.
15. **In-App Notifications:** Notify participants of key events: when target is reached, when deadline is extended, when order is placed, and when delivery is dispatched.

#### Payment Management
16. **Escrow-Style Payment Collection:** Participants pay upfront into a secure escrow; funds are only released to the organizer once the minimum quantity target is met.
17. **Auto-Refund on Failed Group Buy:** If the minimum quantity is not reached by the deadline, all committed payments are automatically refunded.
18. **Integrated Payment Gateway:** Support payments via Razorpay, Stripe, or UPI, with a clear payment receipt for each participant.
19. **Organizer Financial Summary:** A dashboard for the organizer showing total funds collected, number of units committed, and net payout after platform fees.

#### Order Fulfillment & Delivery
20. **Order Placement Confirmation:** Once the target is reached and deadline passes, the organizer marks the order as placed; all participants are notified.
21. **Shipping Address Collection:** Collect individual delivery addresses from participants at the time of commitment for direct shipping.
22. **Bulk vs. Individual Delivery Toggle:** Configure whether the vendor ships to each participant individually or to a single organizer address for local distribution.
23. **Delivery Status Updates:** Organizer posts shipment tracking updates and estimated delivery dates visible to all participants.

#### Reviews & Trust
24. **Post-Delivery Rating:** Participants rate the group buy experience (product quality, organizer reliability, delivery time) after receiving their order.
25. **Organizer Reputation Score:** Aggregate review scores build an organizer's reputation profile, encouraging trust for future group buys.
26. **Dispute Resolution System:** A formal process for participants to report issues (wrong product, non-delivery) managed by platform admins.
