# Floating Shares Calculator

A self-contained, interactive mortgage and equity tracker designed to calculate dynamic ownership percentages between two parties based on initial deposits and ongoing contributions.

## 🚀 Overview
This application provides a real-time visualization of mortgage amortization and the shifting "Floating Shares" equity split. It is particularly useful for partners who contribute different initial deposits and want to track their ownership stake as the mortgage is repaid.

## ✨ Key Features
- **Dynamic Equity Split:** Calculates ownership based on the formula:  
  `(Individual's Deposit + 50% of Standard Principal Paid + 100% of Own Overpayments) / (Total Equity)`
- **Adaptive Visualization:** Interactive Chart.js graph showing:
  - Remaining Mortgage Balance.
  - Cumulative Interest Paid.
  - Individual Ownership Percentages (on a secondary adaptive axis).
- **Time Saved Tracker:** Instantly see how much time you've shaved off your mortgage term when applying overpayments.
- **Smart Overpayment Spread:** "Lump Sum" inputs are intelligently spread over the remaining life of the mortgage to simulate realistic investment growth rather than an instant jump.
- **Privacy-Focused:** A single, self-contained HTML file. No data leaves your machine.

## 🛠️ Usage
1. Open `mortgage_tracker.html` in any modern web browser.
2. Enter your mortgage details (Amount, Rate, Term).
3. Input initial deposits for both parties.
4. Experiment with **Monthly Overpay** or **Lump Sum** amounts to see how they impact the ownership trajectory and the total interest saved.

## 📊 Technical Stack
- **Frontend:** Vanilla JavaScript (ES6+), CSS3.
- **Libraries:** [Chart.js](https://www.chartjs.org/) (via CDN).
- **No Build Required:** No Node.js or external dependencies needed—everything is bundled in one file.

## 📝 License
This project is private and intended for personal use.
