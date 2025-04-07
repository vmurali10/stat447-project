# Data Dictionary

This document provides an overview of the fields contained in the CSV file "merged_data.csv" along with descriptions, and data types. The data were collected from the Centers for Disease Control and Prevention (CDC) as part of environmental public health tracking efforts.

---

## 1. StateFIPS
- **Description:** The Federal Information Processing Standard code identifying the state.
- **Data Type:** Integer

## 2. State
- **Description:** The name of the state for the record.
- **Data Type:** String

## 3. Year
- **Description:** The calendar year for the observation.
- **Data Type:** Integer

## 4. ANNUAL_MEDIAN_HOUSEHOLD_INCOME
- **Description:** The median household income for the state in the given year.
- **Data Type:** Integer

## 5. ER_visits_hri_age_0_4
- **Description:** Number of emergency room visits for heat-related illness (HRI) among children aged 0–4.
- **Data Type:** Integer

## 6. ER_visits_hri_age_5_14
- **Description:** Number of emergency room visits for HRI among individuals aged 5–14.
- **Data Type:** Integer

## 7. ER_visits_hri_age_15_34
- **Description:** Number of emergency room visits for HRI among individuals aged 15–34.
- **Data Type:** Integer

## 8. ER_visits_hri_age_35_64
- **Description:** Number of emergency room visits for HRI among individuals aged 35–64.
- **Data Type:** Integer

## 9. ER_visits_hri_age_over_65
- **Description:** Number of emergency room visits for HRI among individuals aged over 65.
- **Data Type:** Integer

## 10. total_ER_visits
- **Description:** The total number of emergency room visits for HRI, summed across age groups.
- **Data Type:** Integer

## 11. days_over_90_degrees
- **Description:** Count of days in the year when the temperature exceeded 90°F.
- **Data Type:** Integer

## 12. days_over_95_degrees
- **Description:** Count of days when the temperature exceeded 95°F.
- **Data Type:** Integer

## 13. days_over_100_degrees
- **Description:** Count of days when the temperature exceeded 100°F.
- **Data Type:** Integer

## 14. days_over_105_degrees
- **Description:** Count of days when the temperature exceeded 105°F.
- **Data Type:** Integer

## 15. num_counties
- **Description:** The number of counties in the state included in this dataset or analysis.
- **Data Type:** Integer

## 16. HSP_visits_age_0_4
- **Description:** Number of hospital visits (other than ER) for heat-related illness among children aged 0–4.
- **Data Type:** Integer

## 17. HSP_visits_age_5_14
- **Description:** Number of hospital visits (other than ER) for heat-related illness among individuals aged 5–14.
- **Data Type:** Integer

## 18. HSP_visits_age_15_34
- **Description:** Number of hospital visits (other than ER) for heat-related illness among individuals aged 15–34.
- **Data Type:** Integer
- **Example Value:** 76

## 19. HSP_visits_age_35_64
- **Description:** Number of hospital visits (other than ER) for heat-related illness among individuals aged 35–64.
- **Data Type:** Integer

## 20. HSP_visits_age_over_65
- **Description:** Number of hospital visits (other than ER) for heat-related illness among individuals aged over 65.
- **Data Type:** Integer

## 21. total_HS
- **Description:** The total number of hospital stays or visits (aggregated across age groups) for heat-related conditions.
- **Data Type:** Integer

## 22. HE_over_90_degrees
- **Description:** Total number of days in the year with extreme heat (where temperatures exceed 90°F), with the event defined as lasting at least two consecutive days.
- **Data Type:** Integer

## 23. HE_over_95_degrees
- **Description:** Total number of days in the year with extreme heat (where temperatures exceed 95°F), with the event defined as lasting at least two consecutive days.
- **Data Type:** Integer

## 24. HE_over_100_degrees
- **Description:** Total number of days in the year with extreme heat (where temperatures exceed 100°F), with the event defined as lasting at least two consecutive days.
- **Data Type:** Integer

## 25. HE_over_105_degrees
- **Description:** Total number of days in the year with extreme heat (where temperatures exceed 105°F), with the event defined as lasting at least two consecutive days.
- **Data Type:** Integer

## 26. mortality_HRI
- **Description:** The number of deaths attributed to heat-related illnesses. Supressed: data not reported
- **Data Type:** Integer, String

## 27. worker_HRI_cases
- **Description:** The number of reported heat-related illness cases among workers. No data: data not reported 
- **Data Type:** Integer, String

---
