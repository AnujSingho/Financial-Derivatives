# Financial-Derivatives
This repository analyzes **equity price volatility** using two advanced models: the **Heston stochastic volatility model and the Merton jump-diffusion model**. 
Monte Carlo simulations are used to study **option (Derivatives) pricing, Greeks estimation, and the impact of continuous variance dynamics versus sudden price jumps under risk-neutral valuation**.

# Volatility Modelling: Heston & Merton Frameworks

## OBJECTIVE

Assess the cause of volatility using two mechanisms:
- Stochastic Volatility (Heston Model)
- Jump Risk in underlying prices (Merton Model)

---

## GENERAL PARAMETERS

- Initial Stock Price: `S₀ = 80`
- Risk-Free Rate: `r = 5.5%`
- Volatility: `σ = 35%`
- Time to Maturity: `T = 3 months`

---

## HESTON PARAMETERS

- Initial Variance: `V₀ = 3.2%`
- Mean Reversion Speed: `κ = 1.85`
- Long-Term Variance: `θ = 0.045`
- Correlation: `ρ ∈ {−0.30, −0.70}`

---

## MERTON PARAMETERS

- Jump Mean: `μ = −0.5`
- Jump Volatility: `δ = 0.22`
- Jump Intensity: `λ ∈ {0.75, 0.25}`

---
