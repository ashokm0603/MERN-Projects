# Software Requirements Specification (SRS)
## Project 52: Expense Splitting with Settle-Up (Data & Finance)

### 1. Project Description
This application simplifies shared finances for roommates, travel groups, or couples. It allows users to log group expenses, automatically calculates who owes whom (minimizing the number of transactions needed), and keeps a running ledger of debts until they are marked as "Settled Up".

### 2. Core Scope
The platform relies on complex "debt simplification" algorithms, user grouping mechanisms, and a clear, transparent audit trail for all added expenses.

### 3. Functionalities (Minimum 25)

#### Group & User Management
1. **User Registration:** Sign up using Email, Google, or Apple login.
2. **Create a Group:** Create specific groups (e.g., "Miami Trip", "Apartment 4B") and invite members via a shareable link.
3. **Multiple Groups:** Users can belong to multiple groups simultaneously.
4. **Group Dashboard:** A summary showing the total group spending and the user's personal balance within that group.
5. **Non-Registered Members:** Add a "dummy" member to a group if someone doesn't want to make an account, managed by the creator.

#### Expense Logging
6. **Add Expense:** Form to input amount, description, date, and who paid.
7. **Split Equally:** Default option that splits the total cost equally among all group members.
8. **Split by Exact Amounts:** Input exact dollar amounts for each person (e.g., a restaurant bill where people ordered different items).
9. **Split by Percentages:** Allocate costs based on percentage (e.g., 60% / 40%).
10. **Split by Shares:** Allocate costs by shares (e.g., a family of 3 gets 3 shares, a single person gets 1 share).
11. **Receipt Upload:** Attach a photo of the receipt to the expense for transparency.
12. **Multi-Payer Expense:** Support scenarios where multiple people chipped in to pay a single large bill.

#### Calculation & Simplification
13. **Debt Simplification Algorithm:** Automatically calculate the most efficient way to settle debts (e.g., if A owes B $10, and B owes C $10, it simplifies to A owes C $10).
14. **Running Balances:** A clear "Who Owes Who" screen showing current simplified debts.
15. **Individual Balances:** View exactly how much you owe and are owed across all your groups.

#### Settlement & Notifications
16. **Record a Payment:** A user clicks "Settle Up" to record a cash, Venmo, or bank transfer payment made outside the app.
17. **Payment Approval:** The recipient receives a notification and must approve the "Settled Up" request to clear the debt.
18. **Push Notifications:** Alerts when a new expense is added, edited, or deleted within a group.
19. **Nudge Reminder:** A polite button to send a reminder notification to someone who owes money for a long time.
20. **Export Ledger:** Download a PDF or spreadsheet of the entire group's expense history.

#### Advanced Features
21. **Currency Conversion:** Add expenses in multiple currencies (useful for international trips) with auto-conversion based on the date of the expense.
22. **Expense Categories:** Tag expenses (Food, Transport, Accommodation) to see a pie chart of group spending.
23. **Activity Feed:** A scrolling audit log showing every action (e.g., "John added Lunch ($40) at 1:00 PM").
24. **Undo/Edit Functionality:** Allow the creator to edit a mistake, which sends a notification to the group detailing the change.
25. **Admin Panel:** Monitor system load, manage server issues, and handle account recovery requests.
