# Superstore Sales Analysis
## Overview
Sales analysis of a fictional (what is this company about?) company (synthetic Kaggle Dataset, 9,993 oders), framed as if I was advising the Sales Director. Almost 1 in 5 sales is a lloss. Superstore made $2.30M in sales and $286K in profit, a 12.5% margin.

## Recomendation

---

## Author
**Belén Micó Velarde**
[LinkedIn](https://www.linkedin.com/in/belenmicovelarde)

---
## Tools
- **Power Query** --> import, profiling, cleaning and preparation of the dataset
- **Excel** --> pivot tables & interactive dashboard

---

## Business Problem

- **Client:** Sales Director, responsible of (profit?)
- **Pain:** they sell a lot but earn little (something else?)
- **Decision:** to understand which products, regions or discount make money and which ones lose it

---

## Business Questions & Metrics

1. How do discounts affect sales and profit? And how much of our sales depend on high discounts?
2. Which products lose money, and how much?
3. Which regions are profitable, and which are not?
4. Which customer segments are most and least profitable?

| Role | Metric | Why |
|---|---|---|
| Primary | Profit | Defines if the business is actually making money out of sales |
| Supporting | Sales | Can look good even if the business is losing money |
| Diagnostic | Discount | The one they can decide about |

---

## Key Findings

1. Almost 1 in 5 **sales** loses money.
2. **The bigger the discount, the worse the margin**: every discount group above 20% loses money.
3. Without sales with **discounts of 30% or more**, profit would be 47% higher, even if all those sales were lost.
**Only 3 of 17 sub-categories lose money.** Tables loses the most, because 43% of its sales carry high discounts.
**Central is the weakest region:** 7 of its 17 sub-categories lose money, and it has the highest share of high-discount sales.

---

## Interpretation

Superstore has a 12.5% margin, but **almost 1 in 5 sales loses money.** The main driver is **discounting:** the bigger the discount, the worse the margin, and every sale with a discount of 30% or more loses money overall (−$135K). Even if all those sales were lost, **profit would rise by 47%.**

**Only Tables, Bookcases and Supplies lose money,** with margins between −2.5% and −8.6%. 43% of Tables’ sales carry discounts of 30–50%. Most sub-categories offset their high-discount losses with profitable low-discount sales; Tables can’t. Supplies are different: it rarely gets high discounts, so its problem is likely the margin between cost and selling price, not discounting.

No **region** loses money, but **Central underperforms:** 7 of its sub-categories lose money, against 2–3 elsewhere, and it makes the most sales with high discounts (25.8%). West has the best margin and only 2.4% of high-discount sales. Discounts explain most of the gap between regions, though not all of it.

**Segments** perform similarly, so they are **not a priority.**

---

## Recommendation

**Cap discounts at 20%,** starting with Tables and the Central region.

**Where to start:**
1. Tables: the biggest loss (−$17.7K) and the highest share of high discounts (43%). Without them, Tables are profitable.
2. Central: the region with the most high-discount sales and the most losing sub-categories.

**How to measure it:** Apply the cap in Central for one quarter and compare its profit and sales with the other regions. If profit rises and sales don’t drop much, roll it out to everyone.

**Separately:** review Supplies’ prices or supplier costs. Its problem isn’t discounts.

**What not to do:**
- Don’t remove all discounts. Discounts up to 20% are still profitable (11.9% margin).
- Don’t drop Tables. It makes money when it isn’t heavily discounted.
- Don’t target segments. They show no meaningful difference.

  ---

  ---

## Dashboard

Built in Excel from the data retrieved from the Pivot Tables.

**Where to Act**: size of the problem, the riskiest segment, where revenue is lost and when to act.

![Where to Act](dashboard_page1.png)

**Why Customers Leave**: churn rate by payment method, protection services and contract.

![Why Customers Leave](dashboard_page2.png)
