# Software Requirements Specification (SRS)
## Project 36: Subscription Box Manager (Commerce)

### 1. Project Description
The Subscription Box Manager is a personal financial tracking application that serves as a centralized dashboard for managing all of a user's recurring subscriptions and subscription box services. Users manually input or connect their subscription services to track renewal dates, monthly and annual costs, usage satisfaction ratings, and overall return on investment. The platform provides alerts, spending analysis, and smart recommendations to help users identify unused subscriptions and reduce unnecessary recurring expenditure.

### 2. Core Scope
The application focuses on subscription cataloging, cost aggregation, renewal date alerting, ROI/value tracking, and spending analytics. It is designed to solve the "subscription creep" problem where users accumulate many recurring charges without a clear picture of total spending or actual usage of each service.

### 3. Functionalities (Minimum 25)

#### Subscription Tracking & Management
1. **Subscription Entry:** Manually add a subscription with service name, category, billing amount, billing cycle (monthly/quarterly/annual), start date, and next renewal date.
2. **Subscription Categories:** Classify subscriptions into predefined categories (Entertainment, Software/SaaS, Health & Fitness, Food Delivery, News & Learning, Gaming, Shopping, Other).
3. **Service Logo Auto-Detection:** Automatically fetch and display the logo of a recognized service (Netflix, Spotify, Adobe, etc.) when its name is entered.
4. **Subscription Status Toggle:** Mark subscriptions as Active, Paused, or Cancelled to manage their inclusion in cost calculations.
5. **Multi-Currency Support:** Enter and display subscription costs in different currencies with an automatic conversion to a base currency for totals.
6. **Shared Subscription Splitting:** Mark a subscription as shared (e.g., Netflix Family Plan) and specify the number of co-payers to show the user's actual cost share.

#### Dashboard & Cost Overview
7. **Monthly Cost Summary:** A prominent display showing the total amount spent on subscriptions per month.
8. **Annual Projection:** Calculate and display the total annual spend across all active subscriptions.
9. **Cost Breakdown by Category:** A pie chart or donut chart showing the proportion of spending across each subscription category.
10. **Cost Per Day Calculator:** Display each subscription's cost broken down to a per-day rate for easier value assessment.
11. **Top Spending Subscriptions:** Rank subscriptions by monthly cost to instantly identify the most expensive services.

#### ROI & Value Tracking
12. **Usage Satisfaction Rating:** Rate each subscription on a 1–5 scale for how much value and usage the user gets from it.
13. **ROI Score Calculation:** Calculate an ROI score combining the cost and satisfaction rating to highlight "Worth It" vs. "Consider Cancelling" subscriptions.
14. **Usage Frequency Log:** Log how frequently the user uses each subscription (Daily, Weekly, Monthly, Rarely) to inform the ROI calculation.
15. **Underutilized Subscription Alerts:** Proactively flag subscriptions rated low usage for more than 30 days with a "Consider Cancelling" recommendation.

#### Renewal Alerts & Reminders
16. **Upcoming Renewal Calendar:** A calendar view showing all subscription renewal dates for the current and upcoming month.
17. **Renewal Notifications:** Push and email notifications a configurable number of days before each subscription renews (e.g., 7-day and 3-day warnings).
18. **Annual Plan Reminders:** Special alerts for annual subscriptions, with a 30-day advance reminder to evaluate before a large charge hits.
19. **Free Trial End Alerts:** Track free trial end dates and send alerts before the trial converts to a paid subscription.

#### History & Reporting
20. **Payment History Log:** A chronological log of all past subscription charges for record-keeping and expense verification.
21. **Monthly Trend Chart:** A line chart showing total subscription spending month-over-month over the past 12 months.
22. **Cancellation History:** Track cancelled subscriptions, the cancellation date, and reasons for future reference.
23. **Yearly Spending Report:** An annual summary report of all subscription expenses for tax or personal finance review.

#### User Account & Features
24. **User Authentication:** Secure registration and login with email/password and Google OAuth.
25. **Data Export:** Export the full subscription list and payment history as a CSV or PDF file.
26. **Subscription Import via CSV:** Bulk-import existing subscriptions from a pre-formatted CSV template for quick onboarding.
