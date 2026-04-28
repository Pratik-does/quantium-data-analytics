# Quantium Data Analytics Project
Retail Layout Optimization, Customer Segmentation, and Trial Uplift Testing

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-0D1F3C?style=for-the-badge)
![Retail Strategy](https://img.shields.io/badge/Retail%20Strategy-1E3A5F?style=for-the-badge)

A client-ready retail analytics project that examines chip purchasing behaviour, identifies the most commercially valuable customer segments, and evaluates the impact of a new store layout through controlled experimentation.

## Executive Summary

This project answers two business questions:

1. Which customer segments and products drive the chip category?
2. Did the trial store layout produce meaningful uplift worth scaling?

The analysis shows that:
- Older Families (Budget) is the highest-value segment.
- Kettle is the dominant brand and 175g is the leading pack size.
- All three trial stores outperformed their matched control stores.
- Store 77 delivered the strongest commercial result, with the clearest sales and customer uplift.

Final recommendation: proceed with a phased rollout, using Store 77 as the primary reference case.

## Business Objective

Quantium’s Category Manager needed a data-backed recommendation on whether a new retail layout should be rolled out more broadly.

This project was designed to:
- understand chip purchasing behaviour,
- identify the most commercially valuable customer segments,
- evaluate the trial layout against matched control stores,
- convert analysis into a clear rollout recommendation.

  ## Key Findings

### Customer and Segment Insights
- Older Families (Budget) generated the strongest revenue contribution at **$168.4k**.
- Young Singles/Couples (Mainstream) was the largest mainstream volume segment at **$157.6k**.
- Retirees (Mainstream) also contributed materially at **$155.7k**.

### Product Insights
- Kettle led the brand ranking at approximately **$390.2k** in sales.
- 175g was the top pack size at approximately **$485.4k** in sales.
- The category is anchored by family-sized, high-frequency purchases.

### Trial Store Results
- Store 77 vs Control 233: **+29.1% sales uplift**, **+23.5% customer uplift**
- Store 88 vs Control 237: **+12.3% sales uplift**, **+5.8% customer uplift**, **+7.5% transactions per customer**
- Store 86 vs Control 155: **+9.8% sales uplift**, **+13.5% customer uplift**

  ## Final Recommendation

Proceed with a phased rollout of the new layout, with Store 77 as the strongest reference case.

Priority actions:
1. Protect Kettle and 175g in the planogram.
2. Maintain family-oriented value messaging.
3. Use mainstream-led merchandising to convert younger volume shoppers.
4. Monitor Store 86 carefully before replicating its exact execution.

## Methodology

### Task 1: Customer Analytics and Purchase Behaviour
- Cleaned and merged transaction and customer datasets.
- Converted date fields and created derived variables such as brand and pack size.
- Analyzed category performance by life stage, premium segment, brand, and pack size.

### Task 2: Experimentation and Uplift Testing
- Aggregated store performance monthly.
- Selected matched control stores based on pre-trial similarity.
- Compared trial stores against control stores during the Feb–Apr 2019 window.
- Evaluated uplift using sales, customer counts, and transactions per customer.

  ## Repository Structure

```text
.
├── certificate/
├── data/
│   ├── processed/
│   └── raw/
├── notebooks/
│   ├── task1_customer_analytics.ipynb
│   └── task2_uplift_testing.ipynb
├── output_figures/
├── report/
└── README.md
```

### 10) Outputs Included
```markdown
## Outputs Included

### Figures
- Customer segment analysis
- Brand and pack size analysis
- Control-store selection logic
- Trial vs control comparisons for Stores 77, 86, and 88
- Final scorecard
- Strategic synthesis
- Commercial recommendations
- Scaling roadmap
```
### Reports
- Final PDF report
- Supporting project visuals
- Certificate of completion

## How to Run

1. Clone the repository.
2. Open `notebooks/task1_customer_analytics.ipynb` and run Task 1.
3. Open `notebooks/task2_uplift_testing.ipynb` and run Task 2.
4. Review the generated charts in `output_figures/`.
5. Open the final report in the `report/` folder.

## Skills Demonstrated

- Data cleaning and preparation
- Customer segmentation
- Exploratory data analysis
- Data visualization
- Retail experimentation
- Control-store matching
- Uplift analysis
- Business recommendation writing
- Executive reporting

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel
- Statistical comparison methods
- Consulting-style business reporting

## Certificate

The Quantium Data Analytics Job Simulation certificate is included in the `certificate/` folder.

## Author

Pratik Bairagi
  
