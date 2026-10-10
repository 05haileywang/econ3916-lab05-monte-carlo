# econ3916-lab05-monte-carlo
# Monte Carlo Engine -- Probability & Simulation

## Objective
I used Monte Carlo simulation to test probability results and to estimate the daily risk of a $1M portfolio.

## Methodology
- Simulated 10,000 coin flips and plotted the running share of heads.
- Simulated 10,000 Monty Hall games and counted wins for switching.
- Simulated a disease screening test on 100,000 people (prevalence 1%, sensitivity 95%, specificity 90%) and counted how many positive tests were true.
- Simulated daily portfolio returns and computed 95% Value at Risk (VaR) and Expected Shortfall (ES) for a $1M portfolio.
- Estimated pi with random points and checked that the error shrinks like 1/sqrt(n).

## Key Findings
- Coin flips: the running share of heads settled near 0.5 as the number of flips grew.
- Monty Hall: switching won 6,694 of 10,000 games.
- Disease screening: 8.8%% of positive tests were from sick people. Most positives were false alarms because the disease is rare.
- Risk: the 95% VaR was $19,494 and the 95% ES was $24,230. ES is larger because it averages the losses on the worst days instead of marking where they begin.
- Pi estimate: the error shrank in line with 1/sqrt(n).
