# CDS Pricing Streamlit

Interactive Streamlit application for simplified valuation of a Credit Default Swap (CDS) and credit risk analysis.

## Description

This project calculates the simplified Mark-to-Market of a CDS using market parameters chosen by the user:

- Notional
- Credit spread
- Recovery rate
- Risk-free rate
- Maturity

The application also displays:

- The implied hazard rate
- The present value of the premium leg
- The present value of the protection leg
- The Mark-to-Market for the CDS buyer
- The survival and default curves of the product
- A detailed cashflow schedule

# Launch the Application

1. Open a Python environment (VS Code, Anaconda Prompt, or Terminal).

2. Install the dependencies:

pip install -r requirements.txt

3. Launch the application:

streamlit run app.py
