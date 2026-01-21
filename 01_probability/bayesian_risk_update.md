# Updating Project Risk Using Bayesian Inference

## Problem Context
Project risk assessments are often based on historical data or expert judgment.
As new evidence becomes available, these estimates should be updated systematically.
Bayesian inference provides a structured approach for updating beliefs using evidence.

## Scenario Description
A project has an initial estimated probability of delay based on past experience.

- Prior probability of delay: 30%
- Evidence: early milestone slippage observed

The goal is to update the probability of delay after observing new evidence.

## Bayesian Components

### Prior
P(Delay) = 0.30  
P(No Delay) = 0.70

### Likelihood
P(Evidence | Delay) = 0.70  
P(Evidence | No Delay) = 0.20

### Evidence
P(Evidence) =  
(0.70 × 0.30) + (0.20 × 0.70)

## Posterior Calculation
Using Bayes’ Theorem:

P(Delay | Evidence) =  
[P(Evidence | Delay) × P(Delay)] / P(Evidence)

The posterior probability of delay increases after observing early warning signs.

## Interpretation
After incorporating early performance signals, the probability of project delay increases significantly.
This updated estimate supports proactive risk mitigation actions such as resource reallocation or schedule adjustment.

## Key Insights
- Bayesian inference allows continuous learning
- Risk estimates improve as evidence accumulates
- Static probability assumptions can lead to poor decisions

## Next Steps
Future analysis will automate Bayesian updates using statistical methods and Python.
