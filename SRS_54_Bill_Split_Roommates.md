# Software Requirements Specification (SRS)
## Project 54: Bill Split for Roommates (Data & Finance)

### 1. Project Description
The Bill Split for Roommates is a shared household expense management application designed specifically for people living together in a shared accommodation. The platform allows housemates to track recurring shared bills (rent, electricity, internet, groceries), assign proportional payment responsibilities, log individual payments, and maintain a clear, always up-to-date view of who owes what — eliminating the financial friction and awkward conversations that often arise in shared living situations.

### 2. Core Scope
The application focuses on household bill management, proportional cost splitting, recurring payment tracking, payment logging, running balance calculation, and settlement management. It is designed for small groups (2–8 people) with a focus on transparency, fairness, and ease of use for non-financial users.

### 3. Functionalities (Minimum 25)

#### Household & Member Management
1. **Household Creation:** Create a named household (e.g., "Flat 4B") and receive an invite code or link to share with roommates.
2. **Member Invitation:** Invite roommates to join the household via email or shareable invite link.
3. **Member Profiles:** Each member has a profile with name, profile picture, and contact number.
4. **Admin Role:** The household creator acts as admin with the ability to manage members, remove inactive roommates, and settle the household.
5. **Member Departure Handling:** When a roommate leaves, the system calculates their final settlement balance before removing them from the household.

#### Bill Entry & Management
6. **Add Recurring Bill:** Create a recurring bill entry with a name (e.g., "Electricity"), total amount, billing cycle (monthly/quarterly/annual), due date, and who pays first.
7. **One-Time Bill Entry:** Log one-off shared expenses (e.g., "Replacement Microwave," "Apartment Cleaning Service").
8. **Bill Category Tags:** Categorize bills (Rent, Utilities, Internet, Groceries, Household Supplies, Entertainment, Other).
9. **Auto-Generation of Recurring Entries:** Automatically create the next billing cycle entry when a recurring bill is marked as paid.
10. **Bill Attachment:** Attach a photo of the bill or receipt for transparency and dispute resolution.

#### Cost Splitting
11. **Equal Split:** Automatically divide a bill equally among all household members.
12. **Custom Split by Percentage:** Assign a custom percentage of a bill to each member (e.g., if bedrooms are different sizes, rent is split 60/40).
13. **Custom Split by Amount:** Manually assign a specific fixed amount to each member for a given bill.
14. **Exclude Members from Split:** Mark specific bills as not applicable to certain members (e.g., a roommate who pays their own internet separately).
15. **Running Balance Tracker:** Maintain a continuously updated balance for each member showing the net amount they owe or are owed across all bills.

#### Payment Logging
16. **Log a Payment:** Record when a member pays their share of a bill, specifying payment method (Cash, UPI, Bank Transfer) and date.
17. **Mark Bill as Fully Paid:** Easily mark an entire bill as settled once all members have logged their contributions.
18. **Partial Payment Recording:** Allow logging of partial payments when a member can't pay the full amount at once.
19. **Payment History Timeline:** A chronological log of all payments made by all members for full financial transparency.

#### Settlement & Balances
20. **Simplified Debt Calculation:** Algorithmically minimize the number of transactions needed to settle all debts (e.g., instead of A paying B and B paying C, suggest A pay C directly).
21. **Settle Up Feature:** Record a lump-sum settlement between two members that clears their accumulated balances.
22. **Balance Summary Dashboard:** A clear visual showing the net balance of every member — color-coded positive (owed money) and negative (owes money).

#### Notifications & Reminders
23. **Bill Due Date Reminders:** Automated push and email reminders a configurable number of days before each bill's due date.
24. **Payment Confirmation Notifications:** Notify all relevant members when someone logs a payment toward a shared bill.
25. **Monthly Household Summary:** A monthly email digest summarizing all bills, payments, and current balances for the household.

#### Reporting & Data
26. **Expense Reports:** Generate monthly and annual expense reports showing total household spending by category.
27. **Individual Spending History:** Each member can view their personal bill contribution history and payment record.
