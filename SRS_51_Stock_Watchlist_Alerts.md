# Software Requirements Specification (SRS)
## Project 51: Stock Watchlist with Alerts (Data & Finance)

### 1. Project Description
The Stock Watchlist with Alerts is a personal stock market monitoring tool that allows investors to build a curated list of stocks they are watching, set customizable price and percentage-change alert thresholds, and receive real-time notifications when those thresholds are triggered. Paired with a mini-dashboard showing key metrics and price charts, the platform helps retail investors stay informed and act decisively without constantly monitoring the market.

### 2. Core Scope
The application focuses on stock search and watchlist management, customizable alert configuration, real-time price data integration, notification delivery, and portfolio performance visualization. It is designed to be a lightweight, fast monitoring tool rather than a full brokerage platform, with no actual trading functionality.

### 3. Functionalities (Minimum 25)

#### Watchlist Management
1. **Stock Search & Add:** Search for stocks by company name or ticker symbol (NSE, BSE, NYSE, NASDAQ) with live autocomplete.
2. **Multiple Watchlists:** Create and name multiple watchlists (e.g., "Tech Giants," "Long-Term Holds," "Earnings Season") for organized tracking.
3. **Drag-and-Drop Reordering:** Reorder stocks within a watchlist using drag-and-drop for personalized prioritization.
4. **Stock Notes:** Attach a private note to any stock in the watchlist (e.g., investment thesis, target price rationale).
5. **Add Date Tracking:** Record the date when a stock was added to the watchlist to track monitoring duration.

#### Live Market Data
6. **Real-Time Price Display:** Show the current live price for each stock in the watchlist, refreshing at regular intervals during market hours.
7. **Key Metrics Per Stock:** Display daily change (value and %), 52-week high/low, market cap, P/E ratio, and trading volume alongside each stock.
8. **Market Status Indicator:** Clearly indicate whether the market is currently Open, Closed, or in Pre/Post-Market trading hours.
9. **Pre/Post-Market Prices:** Display pre-market and after-hours prices for eligible exchanges.
10. **Sector & Industry Tag:** Automatically tag each stock with its sector (Technology, Healthcare, Finance, etc.) and industry for context.

#### Alerts Configuration
11. **Price Target Alert:** Set an exact price level at which to receive a notification (e.g., "Alert me when AAPL reaches ₹18,000").
12. **Percentage Change Alert:** Set a threshold for daily percentage change (e.g., "Alert if TSLA moves more than ±5% in a day").
13. **52-Week High/Low Alert:** Automatically trigger an alert when a stock hits a new 52-week high or low.
14. **Volume Spike Alert:** Alert when a stock's trading volume exceeds a user-defined multiple of its average volume (a key technical signal).
15. **Alert Direction Control:** Specify if the alert should fire only when the price goes Above or Below the threshold, or in either direction.
16. **Alert Expiration:** Set an optional expiration date for a price alert so it auto-deactivates after the specified date.

#### Notifications
17. **Email Alerts:** Send a detailed email notification when an alert is triggered, including current price, alert condition, and a chart thumbnail.
18. **Push Notifications:** Real-time browser push notifications for triggered alerts, even when the app is in the background.
19. **Alert History Log:** A chronological log of all past triggered alerts with timestamps, triggered prices, and conditions.

#### Analytics & Visualization
20. **Price History Chart:** An interactive candlestick or line chart for each stock showing price history over 1D, 1W, 1M, 3M, 1Y, and 5Y time frames.
21. **Watchlist Performance Summary:** Aggregate view showing the total percentage gain/loss of all stocks in a watchlist from their add date to today.
22. **Top Movers Panel:** A real-time panel highlighting the best and worst performing stocks in the user's watchlists for the current day.
23. **News Integration:** Display the 3 most recent news headlines for each stock, fetched from a financial news API, directly on the stock detail page.

#### User Account & Settings
24. **User Authentication:** Secure login with email/password and Google OAuth.
25. **Timezone & Exchange Settings:** Set the user's timezone and preferred stock exchange for accurate market hours and data display.
26. **Export Watchlist:** Export a watchlist as a CSV file containing stock tickers, add dates, notes, and key metrics for external analysis.
