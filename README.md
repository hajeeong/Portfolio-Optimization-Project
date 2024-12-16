# Portfolio Optimization Project
![Screenshot 2024-12-16 at 2 23 51 AM](https://github.com/user-attachments/assets/c03d8caa-9e1f-43ad-a2af-9a689b21512a)

## Project Overview
This project focuses on optimizing investment portfolios to achieve maximum returns for a given level of risk. It employs modern portfolio theory and quantitative methods, leveraging Python and advanced financial libraries to provide actionable investment strategies.

## Introduction
Portfolio optimization is a key concept in finance that helps investors allocate their assets efficiently. This project implements optimization algorithms to identify the best asset allocation, showcasing expertise in financial engineering and computational finance.

---

## Project Features
### Optimization Techniques
- **Mean-Variance Optimization**:
  - Calculates the optimal portfolio weights to maximize the Sharpe ratio.
- **Efficient Frontier Analysis**:
  - Visualizes the trade-off between risk and return.
- **Monte Carlo Simulation**:
  - Simulates thousands of portfolios to identify the global minimum variance and maximum Sharpe ratio portfolios.

### Key Functionalities
- **Risk Metrics**:
  - Calculates portfolio variance, standard deviation, and beta.
- **Performance Metrics**:
  - Computes expected returns, Sharpe ratio, and diversification benefits.
- **Customizable Inputs**:
  - Allows users to specify assets, risk-free rates, and constraints.
- **Visualization Tools**:
  - Generates plots for the Efficient Frontier, portfolio allocation, and risk-return trade-offs.

---

## Software Tools and Technologies

### Programming and Libraries
- **Python**: Core programming language.
- **NumPy**: Numerical computations for asset returns and covariances.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib** and **Seaborn**: Visualization tools for financial data.
- **SciPy**: Optimization algorithms.
- **yFinance**: Fetches historical stock data.

---

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/hajeeong/Portfolio-Optimization-Project.git
   cd Portfolio-Optimization-Project
   ```

2. **Set Up a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   ```bash
   python portfolio_optimizer.py
   ```

---

## Results and Insights
- **Optimal Portfolios**:
  - Identified portfolios with the maximum Sharpe ratio and minimum variance.
- **Efficient Frontier**:
  - Visualized the risk-return trade-offs for various portfolio allocations.
- **Diversification Insights**:
  - Highlighted the benefits of asset diversification to minimize risk.

---

## Conclusion
This project demonstrates a solid understanding of portfolio optimization techniques and their practical applications. By integrating advanced financial models with Python, it showcases the ability to design effective investment strategies, making it a valuable addition to a finance-focused portfolio.
