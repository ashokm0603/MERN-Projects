# Software Requirements Specification (SRS)
## Project 58: Community Library Book Exchange (Community & Civic)

### 1. Project Description
The Community Library Book Exchange is a neighborhood-level peer-to-peer book lending platform that empowers residents to list books they own and are willing to lend, browse books available from neighbors, request to borrow them, and track the history of all borrows and returns. The platform fosters a reading culture within communities, reduces individual book expenses, and gives books a longer, shared life — acting as a hyper-local digital library without any institutional infrastructure.

### 2. Core Scope
The application focuses on book cataloging, availability management, borrow request workflows, return tracking, and community trust-building through ratings and reviews. A geographic proximity feature ensures users are matched with nearby lenders for practical, in-person exchanges.

### 3. Functionalities (Minimum 25)

#### Book Listing & Catalog
1. **List a Book:** Add a book to the lending library by entering the ISBN (for automatic metadata fetch) or manually inputting the title, author, genre, language, and cover image.
2. **ISBN Auto-Fetch:** Scan or enter an ISBN to automatically populate all book details (title, author, cover, description, publisher) from a public book database API (Google Books, Open Library).
3. **Book Condition Rating:** Specify the physical condition of the book being listed (Excellent, Good, Acceptable, Worn but Readable).
4. **Availability Status:** Set a book's status as Available, Currently Lent Out, or Unavailable (not open for borrowing at this time).
5. **Personal Book Shelf View:** A dashboard showing all books the user has listed, their current availability status, and active borrow requests.
6. **Bulk Listing via CSV:** Upload a CSV of books for users who want to quickly list a large personal collection.

#### Discovery & Browsing
7. **Community Book Catalog:** Browse all available books listed by members in the user's geographic area.
8. **Search & Filter:** Search by title, author, or genre; filter by availability, language, condition, and proximity radius.
9. **Genre-Based Browsing:** Navigate the catalog through genre categories (Fiction, Non-Fiction, Science, History, Self-Help, Children's, etc.).
10. **Book Detail Page:** View full book details including the owner's listing description, condition, and borrowing terms (loan duration, pickup/drop-off preference).
11. **Wishlist / Save Book:** Bookmark a book to receive a notification when it becomes available for lending.

#### Borrow Request Workflow
12. **Send Borrow Request:** Submit a formal borrowing request to the book owner, specifying the desired loan start date and duration.
13. **Request Message:** Include a short personal introduction message with the borrow request to help the owner decide.
14. **Owner Approve / Decline:** Book owners receive requests and can approve or decline with an optional message.
15. **Loan Agreement Confirmation:** Upon approval, both parties confirm the exchange details (handover method, date, location) through the platform.
16. **Pickup / Delivery Options:** Select between in-person pickup (with a location agreed via chat) or a postal/courier arrangement.

#### Borrow Tracking & Returns
17. **Active Borrow Tracking:** Track all currently borrowed books with their due dates clearly displayed.
18. **Return Due Date Reminders:** Automated email and push notification reminders 3 days before and on the return due date.
19. **Extension Request:** Borrowers can request a loan extension; owners can approve or decline.
20. **Mark as Returned:** Either party can mark a book as returned, triggering a review prompt.

#### Trust & Community
21. **Post-Return Rating:** Both the borrower and owner rate each other after a borrow cycle on dimensions like reliability, communication, and book condition adherence.
22. **Trust Score:** Aggregate ratings build a public trust score displayed on each user's profile.
23. **User Profile:** View a member's listed books, borrow history, and trust score before engaging in a transaction.
24. **Community Forum:** A discussion board for sharing book recommendations, reading lists, and community reading events.

#### Communication & Notifications
25. **In-App Messaging:** Private messaging between book owners and borrowers to coordinate exchange logistics.
26. **Notification Center:** Centralized notification hub for all request updates, messages, reminders, and return alerts.
