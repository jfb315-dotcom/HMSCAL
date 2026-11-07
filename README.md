# HMS Mortgage Calculator

Payment calculator for Home Mortgage Solutions, LLC (NMLS #168687), used by our loan officers, realtors and customers. Live at https://jfb315-dotcom.github.io/HMSCAL/.

- `index.html` is the whole app. `email-logo.png` is the logo.
- **Modes:** Buy, Refi, and What can I afford. Compare two options side by side.
- **Starting rate:** the latest Freddie Mac weekly national average 30-year fixed, rounded down to the eighth, read from the market dashboard's `data/market.json`. FHA, VA and USDA start 0.25% lower. If that file can't load, the rate starts at 6.5%.
- **Mortgage insurance:** conventional MI comes from the mortgage-info.com 2026 PMI chart by credit score and down payment. A real quote typed into the MI box overrides it.
- **Share quote:** makes a picture of the quote card (with the loan officer's NMLS and contact info) to text or email, or copies it as text.
- **Loan officers** (John Bischof, Darrell Whitaker, Kristie Bruce) are listed in the `LOS` object near the top of the script.
