# Software Requirements Specification (SRS)
## Project 40: Price Drop Alert Tool (Commerce)

### 1. Project Description
The Price Drop Alert Tool is a consumer-centric application that helps users save money by tracking the prices of specific products across various e-commerce websites (e.g., Amazon, BestBuy, Zara). Users input a product URL and their target price, and the system continuously monitors the page, sending an email or push notification the moment the price drops below their threshold.

### 2. Core Scope
The application relies on backend web scraping/API polling, a robust background job scheduler, price history data visualization, and a reliable notification delivery system.

### 3. Functionalities (Minimum 25)

#### Item Tracking & Management
1. **URL Submission:** A simple input field where users can paste a product URL from supported retailers.
2. **Automated Metadata Extraction:** The system automatically scrapes and displays the product name, image, and current price upon URL submission.
3. **Target Price Setting:** Users set the exact dollar amount they are willing to pay for the item.
4. **"Any Drop" Alert:** A toggle to alert the user if the price drops by *any* amount, regardless of a specific target.
5. **Dashboard:** A central hub showing all tracked items, their current prices, target prices, and status (Active/Triggered).
6. **Organize via Tags:** Group tracked items into custom folders (e.g., "Christmas Gifts", "PC Build").

#### Scraping & Data Engine
7. **Multi-Retailer Support:** Custom scraping logic or API integration for at least 3 major e-commerce platforms.
8. **Periodic Polling:** A background worker (e.g., Cron job) that checks the price of all active items every 3-6 hours.
9. **Out-of-Stock Detection:** The scraper identifies if an item is currently out of stock and pauses price alerts, instead offering a "Back in Stock" alert.
10. **Proxy Management:** Utilize rotating proxies for the scraper to avoid being IP-banned by e-commerce sites.
11. **Variant Support:** Specifically track the price of a selected variant (e.g., the Blue version of a shirt, or the 256GB version of a phone).

#### Notifications & Alerts
12. **Email Alerts:** Send an immediate, richly formatted email when the target price is hit, including a direct 'Buy Now' link.
13. **Push Notifications:** Web or mobile push notifications for instant alerts (crucial for fast-selling flash deals).
14. **SMS Alerts (Premium):** Option to receive a text message for high-priority items.
15. **Price Trend Digest:** A weekly email summarizing the price movements of all items the user is tracking.

#### Analytics & History
16. **Price History Chart:** An interactive line graph showing the price fluctuations of the product since the user started tracking it.
17. **Historical Low Indicator:** Visually highlight if the current price is the lowest recorded price in the platform's database.
18. **Crowdsourced Price Data:** Combine data from all users tracking the same item to build a comprehensive, global price history graph.

#### Social & Community
19. **Deal Sharing:** A public feed where users can share items that have just hit a massive discount.
20. **Trending Items:** A section displaying the top 10 most-tracked products across the entire platform.
21. **Wishlist Import:** Feature to import a public Amazon Wishlist URL and automatically track all items on it.

#### User Account & Admin Features
22. **User Authentication:** Registration via Email/Password, Google, or Apple.
23. **Notification Preferences:** Fine-grained control over which types of alerts (Email, Push, SMS) are received.
24. **Affiliate Link Wrapping:** Automatically convert outgoing 'Buy Now' links into affiliate links to monetize the platform.
25. **Admin Dashboard:** Monitor scraping success rates, proxy health, total active tracks, and affiliate revenue generated.
