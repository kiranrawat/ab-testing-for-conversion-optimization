# A/B Testing for Conversion Optimization

This project analyzes whether a new landing page improves user conversion rates compared to the existing design. Using real A/B testing data, the analysis includes data cleaning, sanity checks, hypothesis testing, and statistical evaluation using a two-proportion z-test.

A second notebook extends the analysis by merging country-level data to explore whether the treatment effect varies across regions.

---

## Data Source
The dataset used in this project comes from Kaggle's Ecommerce A/B Testing dataset.

---

## Project Structure

- **AB_Testing_Landing_Page_Analysis.ipynb**  
  End-to-end global A/B test: data cleaning, randomization checks, conversion rate comparison, and statistical significance testing.

- **AB_Test_Country_Segmentation.ipynb**  
  Segmentation analysis using country data: conversion rates by region, uplift analysis, country-level z-tests, and insights for a targeted rollout.

---

## Key Findings

- The new landing page does **not** significantly improve conversions globally.  
- UK users show a **positive conversion uplift**, indicating a stronger response to the new design.  
- US and CA users show minimal or no improvement.  
- Segment-level analysis reveals patterns that are hidden by global averages.

---

## Conclusion

A global rollout of the new landing page is **not recommended**, but a phased rollout starting with the UK may provide value. Further testing is suggested to validate market-specific behavior.

---

Feel free to explore the notebooks for full analysis and visualizations.

