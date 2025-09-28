# Equities momentum strategy - systematic trading stat arb model

This project implements an **equities momentum trading model** in Python.  
The strategy generates momentum long/short trade entry signals for single name equities, validated by autocorrelation and market regime "risk on/off" indicators.

---

Purpose:
- To further my career opportunities through upskilling.
- To demonstrate personal progress in python coding proficiency in a quant finance (buy-side) context.
- No python knowledge before 9 June 2025. Today 28 September 2025. 16 weeks of learning.

Methodology:
- download and clean data for an equity index and its constituents
- calculate momentum signal for each ticker
- calculate autocorrelation for each ticker
- calculate market regime as "risk on/off" using a compsite of risk regime indicators
- execute trade entry if the momentum signal is validated by both autocorrelation (persistence in the ticker's price history) and the market regime
- scale positions by contribution to portfolio VaR budget
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
