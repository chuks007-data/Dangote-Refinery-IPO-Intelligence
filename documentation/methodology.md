# Methodology

## Valuation

### Price-to-Earnings (P/E)
EPS = (H1 2026 PAT × 2) ÷ Post-offer shares
P/E = IPO price ÷ EPS

### EV/EBITDA
EV = (IPO price × Post-offer shares) + Net debt
Annualised EBITDA = (H1 2026 EBIT + D&A) × 2
EV/EBITDA = EV ÷ Annualised EBITDA

### Price-to-Sales (P/S)
P/S = Market cap ÷ (H1 2026 revenue × 2)

## Scenario Modelling

Investment capital is treated as total outflow. Shares are purchased at IPO price plus buy cost.

- Shares = floor(Capital ÷ (IPO price × (1 + buy cost)))
- Total outflow = Shares × IPO price × (1 + buy cost)
- Net exit = Shares × Exit price × (1 − sell cost)
- Net profit = Net exit − Total outflow
- ROI = Net profit ÷ Total outflow × 100

## Break-Even Price

- Break-even = IPO price × (1 + buy cost) ÷ (1 − sell cost)
- = 525 × 1.02235 ÷ 0.97840
- = ₦548.58

## Minimum Capital for Target Profit

- Profit per share = Exit price × (1 − sell cost) − IPO price × (1 + buy cost)
- Shares needed = ceil(Target profit ÷ Profit per share)
- Minimum capital = Shares needed × IPO price × (1 + buy cost)

## Annualisation

H1 2026 financials are doubled as a conservative baseline. Full-capacity production was reached in March 2026, so Q1 was partial. H2 2026 at full capacity may exceed this baseline.

## Limitations

- No Monte Carlo simulation was performed; probability distributions could not be defensibly justified.
- Dividend payments are excluded from scenarios; if paid, they are subject to 10% withholding tax.
- Peer multiples are analyst estimates, not audited figures.
- The tax exemption under the Free Zone framework is assumed to remain active through 2027.