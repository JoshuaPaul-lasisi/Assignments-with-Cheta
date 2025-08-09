# 7. Business recommendations (printable)

BUSINESS_RECOMMENDATIONS = 

"""
1) Forecasting:
   - Use monthly forecasts per category and sub_category to adjust inventory reorder points.
   - For short SKU lists, run Prophet; for large numbers of SKUs consider hierarchical models or aggregate-to-category then disaggregate.

2) Churn:
   - Score customers by churn probability and target the top X% with personalized offers.
   - Use RFM features plus discount sensitivity and segment to design retention campaigns.

3) Discounts & Profit:
   - Use the regression coefficients to estimate marginal profit impact of increasing discounts.
   - Identify categories where discounts consistently erode margin; consider alternative promotions (bundle, loyalty).

Next steps:

- Cross-validate time-series models and measure forecast accuracy (MAE, RMSE) per series.
- Build an automated pipeline to refresh forecasts monthly and export top SKUs that need reorders.
- Deploy churn model to production to score customers weekly and A/B test retention interventions.
"""
