# Stock Opportunity Scanner for Indian Market

## Business Case
1. Automatically scans thousand of Indian stocks.
2.Filters stocks based on predefined inventment criteria.
3. Saves analysts hours of manual research.
4. Combines technical and fundamental analysis.
5. Generates explainable stocl rankings
6. Helps investors discover ooprtunities earlier.
7. Reduces emotional decision making.
8. Allows creation of reusable screening strategies.
9. Continiously updates rankings as market data changes.
10. Serves as a decision support engine rather than replacing invetors.
---

## Technology Stack

| Category | Technologies |
|---|---|
| Frontend | React, TypeScript, Vite |
| Tables | TanStack Table |
| Charts | TradingView Lightweight Charts, Recharts |
| Backend | Python, FastAPI |
| Historical Market Data | yfinance |
| Indian Market Data | Upstox API |
| Data Processing | Pandas, Polars, NumPy |
| Technical Analysis | pandas-ta / TA-Lib |
| Fundamental Analysis | Custom Python Scoring Engine |
| Machine Learning | Scikit-learn, XGBoost |
| Explainability | SHAP |
| Database | PostgreSQL |
| Time-Series Database | TimescaleDB |
| Cache | Redis |
| Notifications | Email, Telegram Bot |
| Data Validation | Pandera |
| Experiment Tracking | MLflow |
| Testing | Pytest, HTTPX, Playwright |
| CI/CD | GitHub Actions |
---

# Application Walkthrough

| Page | Primary Business Use | Why It Is Important | Business Value | Key Users |
|---|---|---|---|---|
| **Dashboard** | Provides a consolidated view of market conditions, AI picks, index movement and sector performance | Users need an immediate summary before starting detailed analysis | Reduces the time required to understand the market and increases daily engagement | Retail investors, analysts, research users |
| **Market Overview** | Shows broader market direction through indices, market breadth, gainers, losers, volume spikes and sector trends | Stock opportunities should be evaluated within the context of the overall market | Helps users avoid isolated decisions and improves market-timing awareness | Investors, traders, market researchers |
| **Stock Screener** | Filters stocks using fundamental, technical, valuation and AI criteria | It is the main business function of the application: identifying relevant stocks from a large market universe | Saves research time, improves consistency and supports repeatable stock-selection processes | Retail investors, research analysts, swing traders |
| **AI Opportunities** | Ranks potential opportunities using AI scores, upside potential, confidence and explanatory reasoning | Traditional screeners show matches, but users still need help understanding which opportunities deserve attention | Differentiates the product, improves decision support and makes complex analysis easier to consume | New investors, active investors, advisory teams |
| **Watchlist** | Stores shortlisted stocks for continuous observation and comparison | Users rarely make a decision immediately after discovering a stock; they need to monitor it over time | Improves retention, supports ongoing research and creates a personalized experience | All registered users |
| **Alerts & Reports** | Monitors price, breakout, AI-score and technical conditions while storing saved scans and analysis reports | Market conditions change quickly, so users need automated monitoring and historical records | Encourages timely action, reduces missed opportunities and provides traceability of past analysis | Traders, investors, research teams |
| **Stock Details** *(contextual page)* | Provides complete analysis of a selected company, including price, fundamentals, technicals, peers, news and AI insights | Users must validate an opportunity before adding it to a watchlist or acting on it | Builds trust in the recommendation and supports informed decision-making | Investors, analysts, due-diligence users |
| **Settings/Profile** *(profile menu)* | Manages user preferences, notifications, theme, saved criteria and account settings | Personalization is necessary, but it is not part of the main stock-discovery workflow | Supports user control and reduces unnecessary clutter in the primary navigation | Registered users, administrators |
