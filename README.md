# Marketing Mix Modeling: Channel ROI Optimization

## Overview
A Marketing Mix Model (MMM) built to measure and optimize 
the revenue impact of digital marketing channels including 
Paid Search, Social Media, and Display advertising.

## Objective
- Measure channel-level contribution to revenue
- Apply adstock transformation to capture lag and 
  carryover effects of media spend
- Estimate ROI per channel using Linear Regression
- Recommend smarter budget allocation across channels

## Methodology
### 1. Synthetic Data Generation
Synthetic marketing spend and revenue data was generated 
to simulate real-world channel dynamics across a 
defined time period.

### 2. Adstock Transformation
Applied adstock decay to account for the delayed and 
diminishing effect of media spend on consumer behaviour.
Decay rate tuned per channel based on typical 
industry assumptions.

### 3. Linear Regression Modeling
Used Simple and Multiple Linear Regression to estimate 
the contribution of each channel to revenue.
Model evaluated using R-squared and coefficient analysis.

### 4. ROI Calculation
Channel-level ROI calculated as:
ROI = (Revenue Contribution / Media Spend) x 100

### 5. Budget Reallocation Recommendation
Insights from ROI analysis used to recommend optimal 
budget allocation across Paid Search, Social Media, 
and Display channels.

## Key Findings
- Identified highest and lowest performing channels 
  by ROI
- Quantified revenue contribution per channel
- Recommended budget reallocation to maximise 
  overall marketing ROI

## Tools & Technologies
- Python 3.x
- Pandas — data manipulation
- NumPy — numerical computation
- Matplotlib & Seaborn — data visualization
- Scikit-learn — Linear Regression modeling
- Statsmodels — statistical analysis

## Project Structure
├── mmm_analysis.ipynb  # Main analysis notebook

├── README.md           # Project documentation

└── requirements.txt    # Dependencies

## Note
Dataset used in this project is synthetic, generated 
within the notebook to simulate real-world marketing 
spend and revenue patterns. This approach ensures 
confidentiality while demonstrating the full MMM 
methodology.

## Author
Shreya Verma
Data Analyst | Marketing Analytics | MMM
www.linkedin.com/in/shreyav05
