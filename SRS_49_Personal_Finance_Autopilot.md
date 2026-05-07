# Software Requirements Specification (SRS)
## Project 49: Personal Finance Autopilot (Data & Finance)

### 1. Project Description
The Personal Finance Autopilot is a budgeting and expense tracking application. It allows users to manually log their transactions (or import CSVs), auto-categorizes spending using rule-based algorithms, and provides monthly "nudges" or suggestions on how to optimize their savings and reduce unnecessary subscriptions.

### 2. Core Scope
The application focuses heavily on secure data handling, fast data entry UI, automated categorization logic, and comprehensive data visualization for spending habits.

### 3. Functionalities (Minimum 25)

#### Transaction Management
1. **Manual Data Entry:** A lightning-fast form to log an expense (Amount, Merchant, Date) on mobile or web.
2. **CSV Import:** Bulk upload transactions by importing bank statements (CSV format).
3. **Auto-Categorization:** AI/Rule-based engine that automatically assigns categories (e.g., "Starbucks" -> "Dining Out").
4. **Custom Rules Engine:** Users can create rules (e.g., "If merchant contains 'Uber', categorize as 'Transport'").
5. **Split Transactions:** Ability to split a single large receipt (e.g., Target) into multiple categories (Groceries, Electronics).
6. **Receipt Attachment:** Upload photos of physical receipts and attach them to a specific transaction.

#### Budgeting & Goals
7. **Monthly Budget Setup:** Set spending limits for specific categories (e.g., $300 for Groceries).
8. **Budget Progress Bars:** Real-time visual bars showing how much of the budget is consumed.
9. **Rollover Budgets:** Option to roll over leftover budget from one month to the next (Envelope system).
10. **Savings Goals:** Create custom goals (e.g., "Vacation Fund") with target amounts and dates, tracking progress.
11. **"Safe to Spend" Indicator:** A calculated metric showing exactly how much discretionary money is left until payday.

#### Insights & Analytics
12. **Spending Breakdown:** Interactive Pie/Donut charts showing spending by category.
13. **Income vs. Expense Trend:** Line chart comparing total money in versus total money out over the last 6-12 months.
14. **Subscription Detector:** Automatically identify recurring monthly payments and list them in a "Subscriptions" dashboard.
15. **Smart Nudges:** Automated alerts suggesting savings (e.g., "You spent 20% more on dining this month than average").
16. **Net Worth Calculator:** Manual input for assets and liabilities to calculate and track overall net worth over time.

#### Security & Access
17. **User Registration:** Secure authentication utilizing bcrypt and strict password policies.
18. **Data Encryption:** Bank-level encryption (AES-256) for all financial amounts and merchant names stored in the database.
19. **Two-Factor Authentication (2FA):** Support for SMS or Authenticator app (Google Auth/Authy) for login.
20. **Biometric App Lock:** (For PWA/Mobile) Require FaceID or PIN every time the app is opened.
21. **Export Data:** Download all financial data as a CSV or Excel file for external tax software.

#### Customization & Settings
22. **Multi-Currency Support:** Ability to log transactions in different currencies and view a converted total based on live exchange rates.
23. **Custom Categories:** Users can create, rename, or delete default spending categories.
24. **Theme Toggle:** System-wide dark mode and light mode.
25. **Admin Monitoring:** An admin panel to monitor server health, database size, and daily active users (without any access to user financial data).
