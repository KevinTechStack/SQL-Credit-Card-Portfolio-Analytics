# Business Insights Report
## Power BI Dashboard Findings (XYZ Bank Portfolio)

---

## Dashboard Preview (Screenshots)

### Portfolio Overview
![Portfolio Overview](images/Portfolio_Overview_page_1.png)

### Spend & Channels
![Spend and Channels](images/Spend_and_Channels_page_2.png)

### Rewards & Profitability
![Rewards and Profitability](images/Rewards_and_Profitability_page_3.png)

### Fraud & Risk
![Fraud and Risk](images/Fraud_and_Risk_page_4.png)

### Segments & Customers
![Segments and Customers](images/Segments_and_Customers_page_5.png)

---

## Portfolio Snapshot (Verified)

| Metric | Value |
|--------|-------|
| Customers (unique) | 10,000 |
| Cards issued | 51,598 |
| Total Spend (USD) | $508.31M |
| Avg Monthly Spend (USD) | $21.18M |
| Fraud Rate (overall) | 0.257% |
| Time Window | Jan 2024 → Dec 2025 |

---

## 1) Revenue Growth Insights (Spend, Categories, Channels)

### Category mix: everyday spend dominates
Spending is led by essential, high-frequency categories:
- **Groceries**: **$126M** (24.71%)
- **Shopping**: **$103M** (20.32%)
- **Fuel**: **$78M** (15.41%)
- **Electronics**: **$76M** (14.91%)
- **Dining**: **$76M** (14.90%)
- **Travel**: **$50M** (9.74%)

**Implication**: Growth is best driven through everyday-category partnerships (Groceries, Shopping, Fuel) rather than only “aspirational” categories like Travel.

### Channel behavior: spend is digital-first, transactions are balanced
- **Spend**: Online **$455.64M** vs Offline **$52.67M**
- **Transactions**: Offline **1.26M** vs Online **1.17M**

**Implication**: Revenue is increasingly driven by online value even though transaction volume is comparable; this is a digital-first portfolio from a spend perspective.

### Weekend effect: lifestyle timing is real
- **Weekend spend share**: **71.55%**
- **Weekday spend share**: **28.45%**

**Implication**: Campaign timing should be weekend-led (Fri–Sun) for meaningful uplift, with everyday merchants as the primary offer surface.

---

## 2) Customer Segments & Concentration (Portfolio Value Distribution)

### Segment sizing (customer base)
Customer distribution is concentrated in Mass Market:
- **Mass Market**: **5K** (54.3%)
- **Low Value**: **3K** (25.58%)
- **Emerging Affluent**: **2K** (20.12%)

### Segment spend contribution (where revenue comes from)
- **Mass Market**: **$282.87M**
- **Emerging Affluent**: **$157M**
- **Low Value**: **$68.44M**

**Implication**:  
- **Mass Market** is the volume engine and the largest revenue pool.  
- **Emerging Affluent** delivers high spend per customer and is the best cohort for retention + upgrade offers.  
- **Low Value** is the activation cohort (lower spend, higher operational sensitivity).

### Pareto concentration (top customers drive most value)
The cumulative spend curve confirms concentration: **top customers account for a disproportionately large share of portfolio spend**.

**Implication**: retention and experience design must protect top spend percentiles from unnecessary friction (especially in digital flows).

---

## 3) Fraud & Risk (Frequency vs Value)

### Fraud frequency is concentrated in one segment
Fraud share by segment (percent of fraud transactions):
- **Low Value**: **50.20%**
- **Emerging Affluent**: **23.00%**
- **Mass Market**: **21.50%**

Fraud transaction counts by segment:
- **Mass Market**: **2.9K**
- **Emerging Affluent**: **1.8K**
- **Low Value**: **1.6K**

### Fraud value exposure is highest in Mass Market
Fraud value by segment:
- **Mass Market**: **$1.35M**
- **Emerging Affluent**: **$0.77M**
- **Low Value**: **$0.31M**

### Fraud by category (counts)
Highest fraud counts appear in high-frequency categories:
- **Groceries**: **1543**
- **Shopping**: **1213**
- **Dining**: **957**
- **Fuel**: **957**
- **Electronics**: **947**
- **Travel**: **646**

**Implication**: Fraud strategy must separate:
- **Frequency control** (Low Value, high count categories): automated, low-friction rules to reduce operational load.
- **Severity control** (Mass Market, higher fraud value): stronger monitoring for high-value events without broadly degrading customer experience.

---

## 4) Rewards & Profitability (Economics)

### Rewards: cashback drives the most redemptions
Reward redemption counts:
- **Cashback**: **217K**
- **Gift Cards**: **144K**
- **Flights**: **129K**

**Implication**: Cashback is the primary lever for cost control because it dominates redemption volume.

### Profitability distribution (customers and profit bands)
Customers by profitability band:
- **Mid (100–1k)**: **6.0K**
- **Low (0–100)**: **2.2K**
- **High (1k–10k)**: **1.5K**
- **Loss**: **0.3K**

Profit by band (USD, in millions):
- **Mid (100–1k)**: **$2.55M**
- **High (1k–10k)**: **$2.43M**
- **Low (0–100)**: **$0.09M**
- **Loss**: **-$0.02M**

**Implication**: Portfolio profit is carried primarily by the Mid and High bands; the Loss cohort is small but should be actively controlled (reward leakage and risk costs).

### Reward cost vs spend (customer-level pattern)
The reward cost vs spend scatter indicates many customers sit at low spend with non-trivial reward cost, which can become inefficient if not tiered.

**Implication**: Reward design should be value-based (tiered thresholds, caps for inefficient cohorts) while preserving benefits for high-value customers.

---

## 5) Utilization / Spend-to-Limit Signal (Early Risk Indicator)

The spend-to-limit view shows rising utilization over time and visible spikes in the monthly ratio series.

**Implication**: utilization trend should be treated as an early warning signal and monitored alongside fraud and profitability to guide limit management and risk interventions.

---

**[Next: Results & Recommendations →](05_Results_and_Recommendations.md)**
