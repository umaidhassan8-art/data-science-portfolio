# Discrete Probability Distributions – Practical Use Cases

This document explains real-world business and data science use cases of common discrete probability distributions.

---

## 1. Uniform Distribution

### Description
A uniform distribution is used when all outcomes have equal probability.

### Use Case: Random Customer Selection
A company wants to randomly select one customer from a list of 10,000 customers for a feedback survey.  
Each customer has an equal chance of being selected.

### Why Uniform Distribution?
- All outcomes are equally likely
- No bias in selection
- Fair random sampling

### Applications
- Random sampling
- A/B testing
- Monte Carlo simulations

---

## 2. Bernoulli Distribution

### Description
A Bernoulli distribution represents a single experiment with two possible outcomes:
- Success (1)
- Failure (0)

### Use Case: Email Click Prediction
A marketing team sends a promotional email to a user.

Possible outcomes:
- User clicks the email (1)
- User does not click the email (0)

### Why Bernoulli Distribution?
- Single trial
- Binary outcome
- Probability of success equals click-through rate

### Applications
- Conversion analysis
- Binary classification
- Feature engineering

---

## 3. Binomial Distribution

### Description
A Binomial distribution models the number of successes in multiple independent Bernoulli trials.

### Use Case: Product Purchase Campaign
An e-commerce company sends a promotion to 100 customers.  
Each customer has a 5% probability of purchasing the product.

The business wants to estimate the probability that exactly 10 customers make a purchase.

### Why Binomial Distribution?
- Fixed number of trials
- Two possible outcomes per trial
- Constant probability of success

### Applications
- Marketing response modeling
- Quality control
- Risk assessment

---

## 4. Poisson Distribution

### Description
A Poisson distribution models the number of events occurring in a fixed time or space interval.

### Use Case: Customer Support Tickets
A support center receives an average of 5 tickets per hour.

The operations team wants to estimate the probability that 8 tickets will arrive in the next hour.

### Why Poisson Distribution?
- Events occur independently
- Known average rate
- Fixed time interval

### Applications
- Call center staffing
- Web traffic analysis
- Fraud detection
- Network monitoring

---

## Summary

| Distribution | Typical Use Case |
|-------------|------------------|
| Uniform | Equal probability outcomes |
| Bernoulli | Single binary event |
| Binomial | Multiple binary trials |
| Poisson | Event frequency over time |

---

## Portfolio Note
This project demonstrates foundational understanding of discrete probability distributions, which are essential for statistics, machine learning, and data-driven decision-making.
