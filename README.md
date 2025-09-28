# Equities systematic trading stat arb model

This project implements an **equities momentum trading model** in Python.  
The strategy generates momentum trade entry signals that are supported by autocorrelation and if the market regime validates the long or short position.

---

Purpose:
- To further my career opportunities through upskilling.
- To demonstrate personal progress in python coding proficiency in a quant finance (buy-side) context.
- No python knowledge before 9 June 2025. Today 28 September 2025. 16 weeks of learning.

Methodology:
- download data for an equity index and its constituents
- clean data
- calculate momentum signal
- calculate autocorrelation to validate signal
- calculate market regime as "risk on/off" using a compsite of risk regime indicators
- execute trade entry if the momentum signal is validated by both autocorrelation (persistence) and the market regime
- define performance calculation and presentation functions
- scale positions by rolling volatility
- optimse for portfolio VaR limit
- execute stratey for optimised portfolio VaR limit
- display performance chart (returns) and summary data (returns, sharpe, mad DD, etc)

---

## About Me
I have 20 years of experience in finance:
- 10 years in derivatives sales and structuring at Barclays Capital, Lloyds Banking Group, and Crédit Agricole CIB, where I became a derivatives
  structuring desk head and Deputy Chief Dealer, generating $26.5m in desk PnL and $15m in individual PnL in top year.
- 10 years in non-front office roles, including at J.P. Morgan and Morgan Stanley, including in Risk and exotic rates derivatves valuations control.

I am now upgrading my **programming and quantitative skills** with the goal of securing a quantitative or quant-related role in a hedge fund or investment bank.
