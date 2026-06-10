# Software Requirements Specification (SRS)
## Project 35: Pre-loved Clothing Marketplace (Commerce)

### 1. Project Description
The Pre-loved Clothing Marketplace is a sustainable fashion e-commerce platform dedicated to the buying and selling of second-hand clothing and accessories. It provides sellers with easy listing tools and buyers with detailed condition grading, size filters, and style-based discovery to find quality pre-owned garments. The platform promotes conscious consumption, reduces textile waste, and makes fashion accessible at affordable price points.

### 2. Core Scope
The application focuses on product listing, condition-based grading, discovery and filtering, peer-to-peer transactions, and secure payment handling. It must build trust through transparent condition descriptions, verified seller profiles, and a robust buyer protection policy.

### 3. Functionalities (Minimum 25)

#### Seller Tools & Listing
1. **Item Listing Creator:** Create a listing with product photos (up to 8), title, brand, category, color, material, size, and a detailed description.
2. **Standardized Condition Grading:** Sellers classify items using a platform-defined grading scale (e.g., New with Tags, Like New, Good, Fair, Worn) with grading criteria guides.
3. **Measurement Input:** Enter specific measurements (bust, waist, length, etc.) in addition to standard size labels to eliminate size uncertainty.
4. **Pricing Assistance Tool:** AI-based pricing suggestion based on brand, category, condition grade, and comparable sold listings.
5. **Bundle Listing:** Group multiple related items (e.g., a matching set) into a single discounted bundle listing.
6. **Boost Listing:** Option for sellers to pay a small fee to feature their listing prominently in search results.

#### Discovery & Browsing
7. **Advanced Search & Filters:** Filter by category (Tops, Dresses, Denim, Footwear, etc.), size, brand, condition grade, price range, and color.
8. **Style-Based Discovery:** A personalized "For You" feed based on browsed categories, saved brands, and past purchase history.
9. **Brand Directory:** Browse listings by specific brand names with brand-specific pages.
10. **New Arrivals Feed:** A real-time feed of the latest listings added to the platform.
11. **Wishlist / Save Items:** Save listings to a personal wishlist for later purchase consideration.
12. **"Similar Items" Recommendations:** Display algorithmically recommended similar items on each product page.

#### Buying Experience
13. **Detailed Product Page:** Display all photos, measurements, condition details, seller rating, listing age, and view count.
14. **Offer / Negotiate Price:** Send a private price offer to the seller; seller can accept, decline, or counter-offer.
15. **Secure Checkout:** A multi-step checkout with shipping address entry, payment method selection, and order summary.
16. **Multiple Payment Options:** Support UPI, credit/debit cards, net banking, wallets, and Buy Now Pay Later options.
17. **Shipping Label Generation:** Sellers can print a platform-generated shipping label directly after a sale is confirmed.

#### Trust & Safety
18. **Seller Rating & Reviews:** Buyers rate sellers post-transaction on accuracy of description, packaging quality, and communication.
19. **Seller Verification:** Optional identity and address verification for a "Verified Seller" badge that builds buyer trust.
20. **Buyer Protection Policy:** Platform holds payment in escrow until the buyer confirms receipt and item matches description.
21. **Item Not as Described Dispute:** Buyers can file a dispute if the item's condition significantly mismatches the listing; platform mediates.

#### Communication
22. **In-App Buyer-Seller Chat:** Private messaging between buyer and seller to ask questions or negotiate before purchase.
23. **Order Status Notifications:** Automated notifications at each order milestone: Order Confirmed, Shipped, Out for Delivery, Delivered.

#### Sustainability Features
24. **Carbon Footprint Tracker:** Display estimated CO₂ emissions saved by choosing a pre-loved item over a new one.
25. **Sustainability Score Dashboard:** Show users their cumulative environmental impact from all pre-loved purchases made on the platform.
26. **Donation Mode:** Allow sellers to list items for free, with proceeds going to a partnered charity instead of the seller.
