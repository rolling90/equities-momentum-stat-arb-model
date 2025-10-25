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
- calculate market regime as "risk on/off" using a compsite of risk regime indicators (VIX, Gold, US10yTreasury)
- execute trade entry if the momentum signal is validated by both autocorrelation (persistence in the ticker's price history) and the market regime
- scale positions by contribution to portfolio VaR budget
- optimse for portfolio VaR limit
- execute stratey for optimised portfolio VaR limit
- display performance chart (returns) and summary data (returns, sharpe, mad DD, etc)

---

## About Me
- 20 years' finance experience, of which 14 years in execution trading - macro markets.
- Prior employers include Morgan Stanley, Deutsche Bank, Barclays Capital, Crédit Agricole CIB.
- Ex Heaad of FX & rates Derivaives Sales-Trading at Credit Agricole CIB. Top year: generated $26.5m desk PnL & $15m individual PnL.
