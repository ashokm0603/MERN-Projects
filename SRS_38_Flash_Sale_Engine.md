# Software Requirements Specification (SRS)
## Project 38: Flash Sale Engine (Commerce)

### 1. Project Description
The Flash Sale Engine is a specialized e-commerce module designed to drive urgency and high-volume sales over short periods. It allows merchants to create time-limited, highly discounted offers complete with synchronized countdown timers, live stock meters, and anti-bot checkout queues to handle traffic spikes.

### 2. Core Scope
The platform must handle high concurrency (traffic spikes), real-time inventory synchronization to prevent overselling, and dynamic UI elements that foster a sense of urgency.

### 3. Functionalities (Minimum 25)

#### Campaign Configuration (Admin)
1. **Campaign Builder:** Interface to select products, set the start/end exact time (down to the minute), and define the discount percentage.
2. **Dedicated Landing Page:** Auto-generate a specific URL for the flash sale that goes live exactly when the timer hits zero.
3. **Pre-Sale Teaser Page:** A "Coming Soon" page showing the blurred products and a countdown timer.
4. **Inventory Allocation:** Define exactly how many units of a product are allocated to the flash sale versus regular stock.
5. **Purchase Limits:** Restrict buyers to purchasing only 1 or 2 units of a flash sale item to prevent scalping.

#### Urgency & UI Elements
6. **Synchronized Countdown Timer:** A highly accurate global timer (synced via server time, not local client time) displayed across the site.
7. **Live Stock Bar:** A progress bar showing how much stock is left (e.g., "85% Claimed"), updating in real-time.
8. **"Someone just bought..." Popups:** Tiny, non-intrusive notifications showing real-time purchases to build social proof.
9. **Cart Reservation Timer:** Once an item is added to the cart, the buyer has exactly X minutes (e.g., 5 mins) to checkout before it is released back to inventory.
10. **Auto-Expiry:** The sale page automatically locks and redirects users to an "Ended" page the second the timer hits zero.

#### Checkout & Scalability
11. **Virtual Waiting Room (Queue):** During massive traffic spikes, place excess users in a queue system (first-in, first-out) to prevent server crashes.
12. **One-Page Checkout:** A heavily optimized, single-step checkout process to ensure buyers can complete purchases within their reservation time.
13. **Guest Checkout Priority:** Option to force guest checkout during the sale to speed up the process.
14. **High-Concurrency Database Locking:** Optimistic or pessimistic locking mechanisms to ensure the exact same item isn't sold twice at the exact same millisecond.
15. **Bot Detection:** Implement reCAPTCHA v3 or Cloudflare Turnstile specifically on the checkout button to block automated buying scripts.

#### Notifications & Marketing
16. **Pre-Sale Email Reminders:** Users can click "Remind Me" to get an email 15 minutes before the sale starts.
17. **SMS Alerts:** Integration with Twilio for instant text message alerts when the sale drops.
18. **Abandoned Cart Recovery (Post-Sale):** If items were left in the cart and stock remains after the sale ends, send an email offering a smaller discount.
19. **Social Share Incentives:** Offer an extra 5% off if the user shares the sale link on Twitter/Facebook before buying.

#### Analytics & Post-Sale
20. **Real-Time Analytics Dashboard:** Admins can watch live traffic, active carts, and revenue per minute during the sale.
21. **Post-Sale Report:** Detailed summary showing conversion rate, fastest-selling item, and total revenue.
22. **Stock Reintegration:** Automatically move unsold flash sale inventory back to the regular store at normal prices.

#### System Maintenance
23. **Caching Layer:** Heavy use of Redis or Memcached for the product catalog to serve reads without hitting the main database.
24. **Webhook Integration:** Send live sale data to external inventory management software (like Shopify or ERPs).
25. **Admin Kill Switch:** A single button to instantly pause or abort the sale in case of a critical pricing error.
