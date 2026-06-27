# 📈 Stock Portfolio Tracker

A feature-rich, command-line portfolio tracking application built using Python. Investors can organize their holdings, analyze asset distributions, and track net financial returns across five major global economic sectors.

## 🚀Key Features

* **Sector-Based Asset Bank:** Manages predefined market metrics across 5 key sectors (Technology, Financials, Healthcare, Consumer Discretionary, and Communication).
* **Dynamic Analytics Engine:** Instantly calculates position parameters including Cost Basis, Current Market Value, and position weights (`Total Return %`).
* **Robust Input Validation:** Implemented multi-layered `try-except` blocks and input sanitization (`.strip().upper()`) to ensure zero system crashes from user typos.
* **Persistent Automated Reporting:** Uses the native system `datetime` module to output clean analytical performance logs straight to an appended local text file (`Stock_Report.txt`).

## 🛠️ Built With

* **Python 3** (Optimized for Python IDLE and standard terminal environments)
* **datetime module** for automated, real-time system clock timestamps
