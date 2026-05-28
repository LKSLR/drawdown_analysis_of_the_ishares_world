### Drawdown Analysis of the MSCI World ETF

This project analyzes historical drawdowns of the iShares MSCI World ETF and investigates how investment horizon affects the probability of loss.

The goal is to better understand investment risk, recovery periods, and the relationship between holding time and the likelihood of remaining in drawdown.

## Research Question

At what investment horizon does the probability of loss fall below 5%?

---

## Methods

The analysis is based on weekly price data of the iShares MSCI World ETF retrieved with the `yfinance` library.

The following metrics were calculated:

- Maximum Drawdown
- Average Drawdown
- Time Under Water
- Recovery Duration
- Probability of Loss over different investment horizons

Rolling maximums were used to measure drawdowns relative to historical highs.

---

## Findings

The analysis shows that short investment horizons are associated with a relatively high probability of loss and prolonged drawdowns.

With increasing holding periods, the probability of remaining below the initial investment decreases significantly. Historical data suggests that longer investment horizons substantially improve resilience against market drawdowns.

The analysis indicates that a holding period of approximately 83 weeks was historically required to reduce the probability of loss below 5%.

---

## Conclusion

Even though an ETF like the MSCI World is generally considered a relatively safe investment, the required holding period to achieve a high probability of positive returns is substantially longer than many investors might initially expect.
