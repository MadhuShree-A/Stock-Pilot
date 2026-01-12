# StockPilot: State-Driven Stock Trading Strategy

StockPilotis a Python-based stock trading strategy that uses market state classification and transition probabilities to make optimal buy decisions. The project simulates real-world trading behavior using historical stock price data and evaluates portfolio performance over time.

---

##  Project Overview

The goal of this project is to build a simple rule-based trading model that decides when to place buy orders based on daily stock returns.

Market conditions are classified into three states:

- **Bull (+1)** – Strong positive returns  
- **Flat (0)** – Mild or stable returns  
- **Bear (-1)** – Strong negative returns  

Using historical transitions between these states, the model estimates probabilities and makes buy decisions to maximize portfolio value.

---

##  Technologies Used

- Python  
- Pandas  
- NumPy  
- Jupyter Notebook  
- QuantRocket  

---

##  How It Works

1. Fetch daily closing prices for AAPL (2023).  
2. Calculate daily returns.  
3. Classify each day into Bull, Flat, or Bear states.  
4. Compute transition probabilities in a streaming manner.  
5. Decide optimal days to place buy orders.  
6. Track portfolio value based on predefined reward rules.  

---

##  Files in This Repository

- `StockPilot.ipynb` – Main implementation notebook  
- `README.md` – Project documentation  

---

##  Results

The strategy identifies optimal buy points based on market state transitions and tracks the final portfolio value **V(N)**.

This demonstrates how probabilistic models can assist in financial decision-making.

---

##  Key Learnings

- Financial data processing  
- Market state modeling  
- Probability-based decision making  
- Algorithmic trading concepts  
- Portfolio performance evaluation  

---

 
