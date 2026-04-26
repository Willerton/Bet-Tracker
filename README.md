## Features

### Bankroll Management

* Track balances per bookmaker (site-specific bankrolls)
* Set and update starting and current balances
* Automatically deduct stakes from available balance when placing bets
* Prevents over-staking across multiple active bets

---

### Points-Based Staking System

* Points are calculated as a percentage of the selected bookmaker balance
* Supports:

  * Preset points (0.25 to 10)
  * Custom point entry
  * Direct cash stake input (auto-converted to points)
* Stakes are calculated dynamically based on available balance
* Points rounded to 1 decimal place

---

### Bet Tracking

* Add and manage bets with:

  * Selection name
  * Bookmaker
  * Bet type
  * Event date and time
  * Odds (fractional or decimal)
  * Points or cash stake
* Bet statuses:

  * Pending
  * Win
  * Loss
  * Money Back (MB)
* Edit bet details (selection name and event time)
* Delete bets
* Manual override for real-world returns (e.g. Rule 4 deductions, cashouts)

---

### Live Metrics & Performance Tracking

* Total Starting Balance
* Current Balance
* Actual Profit / Loss (settled bets only)
* Active Stake Value (total of all pending bets)
* Active Potential Profit
* ROI (Return on Investment)
* Exposure % (risk relative to bankroll)
* Active Bets count

---

### Analytics Dashboard

* Balance over time chart
* Bookmaker breakdown including:

  * Total bets
  * Active bets
  * Win / Loss / Money Back counts
  * Win rate
  * Total staked
  * Active stake
  * Profit / Loss
  * ROI
* Compact layout with no horizontal scrolling

---

### Bet Management (All Bets Page)

* Search across all bets
* Column filtering
* Column sorting
* Filter breadcrumbs for visibility
* Inline editing for:

  * Bet name
  * Event date/time
* Status updates via popup modal

---

### User Interface & Experience

* Dark / Light mode toggle

  * Defaults to Dark mode
  * Saved locally in browser
* Responsive layout for desktop and mobile
* Collapsible dashboard sections:

  * Site Balance
  * Point Calculator
* Improved spacing and table layout
* Visual status tags (Win, Loss, Pending, MB, etc.)

---

### Data Management

* Data stored locally using browser localStorage
* Export data to file
* Import data from file
* Clear all data with confirmation requirement ("CONFIRM")

---

### Accessibility

* Keyboard navigation support
* Focus indicators for interactive elements
* Improved colour contrast in both themes
* Reduced motion support for accessibility preferences

---

### Additional Features

* Odds format toggle (fractional / decimal)
* Automatic stake preview before placing bets
* Overdue bet highlighting
* Per-site filtering for point calculator and bet entry
* Persistent UI state (theme, collapsed sections)

---

## Summary

bet-tracker is a full-featured betting and bankroll management tool designed to provide accurate tracking, real-time exposure visibility, and detailed performance analytics across multiple bookmakers.
