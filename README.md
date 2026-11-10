# Gikomba Stall Analysis

**Name:** YOUR FULL NAME
**Cohort:** YOUR COHORT

## Business problem

Wanjiku runs a fresh-produce stall at Gikomba Market. For two weeks she has recorded her daily sales in a notebook and kept a rough record of her stock (quantity, reorder level, cost and selling price per kg for five products). She has hired me as a freelance analyst to answer four questions: How is my business doing? Is it growing? What should I restock? Where should I focus my effort? Using only core Python (lists, dictionaries, slicing, functions and f-strings, with no pandas or NumPy), this project calculates her sales statistics, week-on-week growth, strong and weak days, weekday versus weekend performance, reorder needs and product margins, and ends with data-backed recommendations.

## How to run

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/plp-da-a1-gikomba-stall-analysis/blob/main/stall_analysis.ipynb)

Click the badge above, then choose **Runtime → Run all**. No extra libraries are needed.

## Top three findings

1. **The business is growing:** week 2 sales were KES 24,400 against KES 22,050 in week 1, which is **+10.66%** week-on-week (total KES 46,450 over 14 days, average KES 3,317.86 per day).
2. **Weekends drive the business:** Saturday and Sunday average KES 4,900 per day versus KES 2,685 on weekdays, which is **82.5% higher**. All 4 "Strong" days were weekend days, while **6 of 14 days were "Weak"**.
3. **Two products need restocking now:** Tomatoes (18 kg vs 25 kg reorder level) and Sukuma (9 kg vs 15 kg). Avocado has the best gross margin at **42.9%**, while Onions has the lowest at 30.0%.
