# Catastrophe-Risk-Modelling-A-Monte-Carlo-Analysis-of-Flood-Losses-Inspired-by-the-2024-Valencia-DANA
Overview
This project develops a simplified catastrophe risk model to estimate the financial impact of extreme flood events on a residential insurance portfolio. Using the 2024 Valencia DANA as a real-world case study, the model applies actuarial and statistical techniques to simulate catastrophic losses and evaluate the effectiveness of reinsurance strategies.
The objective is not to replicate proprietary catastrophe models used by the insurance industry, but to demonstrate the fundamental principles of catastrophe risk modelling through a transparent, reproducible, and data-driven approach.

Objectives
• Build a representative residential insurance portfolio.
• Model catastrophe frequency using a Poisson distribution.
• Model loss severity using statistical distributions.
• Simulate thousands of annual loss scenarios using Monte Carlo simulation.
• Estimate key risk metrics such as Expected Loss, Value at Risk (VaR) and Tail Value at Risk (TVaR).
• Evaluate the impact of an Excess of Loss (XoL) reinsurance treaty on the insurer's loss distribution.
• Perform sensitivity analyses under different catastrophe scenarios.

Methodology
The project follows a standard actuarial catastrophe modelling framework:
1. Portfolio construction.
2. Event frequency modelling.
3. Loss severity modelling.
4. Monte Carlo simulation.
5. Risk metric calculation.
6. Reinsurance analysis.
7. Scenario and sensitivity analysis.

Technologies
• Python
• NumPy
• Pandas
• SciPy
• Matplotlib
• Jupyter Notebook

Repository Structure


├── data/ # Input datasets

├── notebooks/ # Exploratory analysis and simulations

├── src/ # Python source code

├── figures/ # Charts and visualisations

├── report/ # Technical report

├── README.md

└── requirements.txt

Disclaimer
This project is an educational and portfolio exercise. It uses simplified assumptions and publicly available information to illustrate actuarial modelling techniques and should not be interpreted as a commercial catastrophe model or a pricing tool.
Author
Daniel — MSc Actuarial & Financial Sciences
Portfolio project focused on actuarial science, catastrophe risk modelling, and reinsurance analytics.
