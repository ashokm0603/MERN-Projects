# Software Requirements Specification (SRS)
## Project 56: Side Hustle Revenue Dashboard (Data & Finance)

### 1. Project Description
The Side Hustle Revenue Dashboard is a financial analytics tool designed specifically for freelancers, gig-workers, and creators with multiple income streams. It allows users to track income from various platforms (e.g., Uber, Fiverr, Etsy, YouTube), categorize expenses related to those gigs, and visualize overall profit margins and trends in one unified dashboard.

### 2. Core Scope
The application emphasizes highly customizable data entry, comprehensive charting using libraries like Chart.js or Recharts, tax-prep features, and a responsive design for on-the-go logging.

### 3. Functionalities (Minimum 25)

#### Income & Expense Tracking
1. **Custom Income Streams:** Users can define multiple sources of income with custom names and colors (e.g., "Etsy Store", "Freelance Writing").
2. **Log Income:** Quickly input a payment received, date, associated platform, and notes.
3. **Log Expense:** Input business-related expenses (e.g., Software subscriptions, gas, materials) linked to a specific income stream.
4. **Mileage Tracker:** A specific input form for gig drivers to log miles driven for tax deduction purposes.
5. **Recurring Entries:** Set up recurring income or expenses (e.g., $15/month for Adobe Creative Cloud).
6. **Receipt Storage:** Upload photos or PDFs of receipts attached to specific expense entries.

#### Dashboard & Data Visualization
7. **Main Dashboard:** A high-level overview showing Total Revenue, Total Expenses, and Net Profit for the current month.
8. **Income Breakdown Pie Chart:** Visual representation showing which side hustle brings in the highest percentage of revenue.
9. **Profit Margin Tracker:** Automatically calculate and display the profit margin (Profit / Revenue) for each individual gig.
10. **Monthly Trend Line Chart:** Track revenue growth month-over-month to identify seasonal trends.
11. **Goal Setting & Progress:** Set monthly or annual revenue goals with a dynamic progress bar filling up as income is logged.

#### Tax Preparation & Reports
12. **Tax Estimation:** A basic calculator that sets aside a user-defined percentage (e.g., 25%) of net profit into a virtual "Tax Bucket."
13. **Schedule C Exporter:** Generate a year-end report categorized similarly to the IRS Schedule C form for independent contractors.
14. **Custom CSV Export:** Export all data filtered by date range, platform, or category to send to an accountant.
15. **Expense Categorization:** Pre-built tax-deductible categories (e.g., Home Office, Advertising, Travel).

#### User Account & Security
16. **User Authentication:** Secure email/password registration and login.
17. **Data Privacy & Encryption:** Ensure financial inputs are encrypted and not sold to third parties.
18. **Multi-Currency Support:** Allow users operating internationally to log income in various currencies with manual conversion settings.
19. **Dark Mode / Light Mode:** UI themes for better accessibility.

#### Productivity & Tools
20. **Hourly Rate Calculator:** Input hours worked versus income received to calculate the *actual* effective hourly rate for a specific gig.
21. **Invoice Generator:** A built-in tool to generate simple, professional PDF invoices to send to clients.
22. **Invoice Status Tracker:** Mark generated invoices as "Sent", "Overdue", or "Paid".
23. **Client CRM:** A simple address book to save client names, emails, and notes.
24. **In-App Reminders:** Push notifications reminding the user to log their weekly earnings every Sunday evening.
25. **Admin Analytics:** Monitor platform growth, active users, and system performance without exposing user financial data.
