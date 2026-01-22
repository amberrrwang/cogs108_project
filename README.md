# Pink Tax Analysis: Gender-Based Pricing in Retail Clothing

This project analyzes gender-based pricing differences (commonly referred to as the “pink tax”) in retail clothing using real-world data from Zara. The goal is to examine whether women’s clothing is systematically priced higher than men’s clothing across different product categories, and to understand how pricing patterns vary by category and data composition.

This project was developed as part of the Data Science in Practice course at the University of California, San Diego.

---

## Project Motivation

The “pink tax” refers to the phenomenon where products marketed toward women are priced higher than similar products marketed toward men. While this concept is widely discussed, empirical evidence can vary significantly depending on product category, brand strategy, and dataset composition.

This project uses data-driven analysis to investigate:
- Whether gender-based price differences exist in retail clothing
- How pricing patterns differ across clothing categories
- How dataset imbalance can affect conclusions drawn from analysis

---

## Data Source

- Retail clothing data scraped from **Zara**
- Each item includes:
  - Gender (Men / Women)
  - Product category
  - Price
  - Additional product attributes (when available)

---

## Methodology

### 1. Data Cleaning & Preparation
- Standardized gender and category labels
- Removed missing or invalid price entries
- Grouped items by gender and product category

### 2. Exploratory Data Analysis (EDA)
- Compared mean and median prices by gender
- Visualized price distributions across categories
- Examined price ranges and variability

### 3. Visualization
Key visualizations include:
- Mean price comparison by gender and category
- Price distribution plots (boxplots / histograms)
- Price range comparisons across categories

### 4. Interpretation & Validation
- Identified cases where initial hypotheses were contradicted by visual evidence
- Discovered that unequal sample sizes between men’s and women’s categories significantly affected results
- Refined conclusions based on data composition and variability rather than raw averages alone

---

## Key Findings

- Gender-based pricing differences are not uniform across categories
- In several categories, men’s clothing was more expensive on average than women’s
- Men’s apparel often showed greater price variability
- Apparent “pink tax” effects can be misleading if item counts between genders are not balanced
- Data interpretation and visualization played a critical role in correcting initial assumptions
