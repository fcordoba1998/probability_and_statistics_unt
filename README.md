# Statistical Analysis of Stock Returns - YPF


---

## Main Objectives
1. **Evaluate statistical behavior** of daily returns through:
   - Central tendency measures (mean) and dispersion (standard deviation, CV).
   - Frequency distributions and normality tests.
2. **Analyze risks and opportunities**:
   - Return-volatility relationship.
   - Probability of extreme events (distribution tails).
3. **Discuss practical implications**:
   - Model suitability (normal vs. alternatives).
   - Investment strategies (short/long term).

---

## Methodology
- **Data source**: [Specify source: Yahoo Finance, Bloomberg, etc.].
- **Tools**:
  - Python (`pandas`, `numpy`, `scipy`, `matplotlib`, `seaborn`).
  - Statistical tests (Kolmogorov-Smirnov, Shapiro-Wilk).
  - Distribution modeling (normal, t-Student, etc.).
- **Key metrics**:
  ```python
  average_return = df['Returns'].mean()
  volatility = df['Returns'].std()
  cv = volatility / average_return
