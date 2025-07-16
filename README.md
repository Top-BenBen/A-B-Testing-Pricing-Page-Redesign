# A-B-Testing-Pricing-Page-Redesign

## Documentation: A/B Testing – Pricing Page Redesign

### 1. **Project Title & Goal**

**A/B Testing Report: Pricing Page Redesign**
A controlled experiment comparing two pricing page layouts (Group A vs. Group B) to evaluate impact on user behavior—measuring both **conversion rate** (upgrades) and **visit duration**.

**Objective**: Determine which pricing design increases upgrade conversions and revenue per visit, while also assessing time spent on page.



### 2. **Data Overview**

The dataset captures user engagement metrics with the following columns:

* **User\_ID**: Unique participant identifier
* **Group**: ‘A’ or ‘B’ indicating control vs. variant
* **Upgrade\_Flag**: 1 if user upgraded (yes), 0 if not
* **Revenue**: Dollar value of upgrade (e.g., \$66.00)
* **Visit\_Duration (s)**: Time spent on page in seconds



### 3. **Summary Metrics & Aggregates**

| Metric                      | Group A | Group B |
| --------------------------- | ------- | ------- |
| **Conversion Rate**         | 16%     | 34%     |
| **Average Revenue / Visit** | \$9.15  | \$20.58 |
| **Average Time Spent (s)**  | 45.3    | 45.2    |
| **Upgrades (YES)**          | —       | —       |
| **Non-Upgrades (NO)**       | —       | —       |

Note: Specific counts for upgraded vs non-upgraded users are summarized in the workbook.



### 4. **Statistical Analysis**

The spreadsheet includes t-tests to determine statistical significance in outcome differences:

* **Revenue Difference p-value**: 0.00396 — *Statistically significant at p < 0.01*
* **Visit Duration Difference p-value**: 0.3758 — *Not statistically significant*

This suggests the pricing redesign significantly impacted revenue without significantly changing time on page.



### 5. **Key Insights**

1. **Conversion Impact**
   Group B doubled the conversion rate (34%) compared to Group A (16%), indicating strong positive user response to the variant design.

2. **Revenue Efficiency**
   Average revenue per visit was more than twice as high in Group B (\$20.58 vs. \$9.15), reinforcing its superior financial performance.

3. **Engagement Metric**
   Similar time-on-page between both groups (≈45 seconds) confirms consistent engagement level; the design change didn’t deter or delay users.

4. **Revenue Significance**
   The low p-value confirms the revenue uplift is statistically significant, supporting the case for adopting Group B’s design.



### 6. **Recommendations**

* **Implement Group B design** across pricing pages due to strong conversion and revenue gains.
* **Monitor user flow and support funnel** to validate broader impact and uncover new optimization opportunities.
* **Track long-term revenue** post-launch to ensure sustained results and watch for any behavioral shifts over time.


### 7. **Dashboard & Workflow Suggestions**

To enhance monitoring and decision-making, consider:

* Building a **dynamic dashboard** (Excel, Google Sheets, Power BI) with:

  * Real-time metrics by group
  * Cumulative conversions and revenue timeline
  * Alerts for A/B testing thresholds
* Automating the **t-test and metrics report** with scripting (Python or R) to streamline future experiments.


### 8. **Conclusion**

This spreadsheet reveals that the redesigned pricing page (Group B) significantly improves both conversion rate and revenue per visit without compromising engagement. The observed uplift is statistically valid, making a compelling case to adopt the new design organization-wide.

