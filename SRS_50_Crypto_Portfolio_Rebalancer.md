# Software Requirements Specification (SRS)
## Project 50: Crypto Portfolio Rebalancer (Data & Finance)

### 1. Project Description
The Crypto Portfolio Rebalancer is a data-driven cryptocurrency portfolio management tool that helps investors maintain their target asset allocations over time. Users define their ideal portfolio allocation (e.g., 40% Bitcoin, 30% Ethereum, 20% Solana, 10% Stablecoins), and the platform continuously monitors live market prices to calculate portfolio drift from the target. When drift exceeds configurable thresholds, the system generates specific rebalancing trade suggestions (buy X of Asset A, sell Y of Asset B) to bring the portfolio back in line.

### 2. Core Scope
The application focuses on portfolio tracking with live price data, target allocation management, automated drift calculation, rebalancing trade generation, and performance analytics. It is a read-and-analyze tool (non-custodial), meaning it does not execute trades directly but provides precise, actionable trade instructions.

### 3. Functionalities (Minimum 25)

#### Portfolio Setup & Management
1. **Add Holdings:** Input cryptocurrency holdings by specifying the asset name/ticker, quantity held, and acquisition price.
2. **Multiple Portfolio Support:** Create and manage multiple separate portfolios (e.g., "Long-Term Hold," "Trading Fund," "Retirement Stash").
3. **Target Allocation Definition:** Set a target percentage allocation for each asset in the portfolio; the system enforces allocations sum to 100%.
4. **Asset Search & Autocomplete:** Search for any cryptocurrency by name or ticker with autocomplete powered by a crypto market API (CoinGecko, CoinMarketCap).
5. **Manual Price Override:** Allow users to manually override the live price for assets traded on decentralized exchanges not covered by the main API.

#### Live Market Data & Valuation
6. **Live Price Feed:** Display real-time prices for all held assets, refreshing automatically at configurable intervals.
7. **Current Portfolio Value:** Calculate and display the total portfolio value in the user's chosen fiat currency (USD, EUR, INR, etc.).
8. **Asset-Level Valuation:** Show the current value, quantity, and percentage of portfolio for each individual holding.
9. **Profit/Loss Display:** Show unrealized profit or loss for each asset based on acquisition price versus current market price.
10. **24h Price Change Indicators:** Display the 24-hour price change (percentage and absolute) for each held asset.

#### Drift Calculation & Alerts
11. **Current vs. Target Allocation Comparison:** Side-by-side display of each asset's current allocation percentage versus its target percentage.
12. **Drift Percentage Calculation:** Calculate and display the "drift" for each asset (how far current allocation has deviated from target).
13. **Rebalancing Threshold Setting:** Users configure a drift threshold (e.g., ±5%) at which the system triggers a rebalancing recommendation.
14. **Rebalancing Alert Notifications:** Push and email notifications when any asset's drift exceeds the user-defined threshold.
15. **Portfolio Drift Health Score:** A single aggregate score representing the overall deviation of the portfolio from its target state.

#### Rebalancing Suggestions
16. **Trade Instruction Generator:** When rebalancing is triggered, calculate and display the exact trades needed: which assets to buy, which to sell, and in what quantities.
17. **Dollar-Cost Averaging (DCA) Option:** Generate rebalancing instructions assuming new cash is being added, rather than selling existing assets.
18. **Rebalancing Strategy Selection:** Choose from rebalancing strategies: Threshold-Based, Calendar-Based (monthly/quarterly), or Hybrid.
19. **Trade Instruction Export:** Export rebalancing instructions as a plain text or PDF checklist for manual execution on an exchange.
20. **Slippage & Fee Estimation:** Estimate transaction fees and potential slippage for each suggested trade to show the true cost of rebalancing.

#### Analytics & Performance
21. **Portfolio Performance Chart:** A line chart showing total portfolio value over time (7-day, 1-month, 3-month, 1-year).
22. **Allocation History Visualization:** A stacked area chart showing how the actual allocation of each asset has evolved over time.
23. **Rebalancing History Log:** A log of all past rebalancing events, dates, trades executed, and portfolio state before and after.
24. **Benchmark Comparison:** Compare portfolio performance against a benchmark (e.g., Bitcoin-only, Ethereum-only, or 50/50 BTC/ETH).

#### User Account & Security
25. **User Authentication:** Secure login with email/password and Google OAuth.
26. **Data Privacy Commitment:** All portfolio data is stored encrypted; the platform never requests or stores private wallet keys or exchange API keys with trade permissions.
27. **Exchange Read-Only API Integration:** Optional connection to exchange APIs (Binance, Coinbase) in read-only mode to automatically sync holdings without any risk to funds.
