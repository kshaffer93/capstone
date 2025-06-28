# Data Analytics Capstone Project

> _A comprehensive data analysis project conducted as part of a Data Analytics Bootcamp._

## Veterans Acute Care Facility Performance
_This capstone explores the perfomance of VA Acute Care Facilities in comparison to civilian hospitals in the US in terms on performance. Performance here is decided by Patient Satisfaction Survey ratings, Readmission rates, and facility area density._

---

## Table of Contents

- [Project Overview](#project-overview)
- [Datasets Used](#datasets-used)
- [Methodology](#methodology)
- [Tools and Technologies](#tools-and-technologies)
- [Key Findings](#key-findings)
- [Dashboard](#dashboard)
- [How to Run](#how-to-run)
- [Project Structure](#project-structure)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

---

## Project Overview

VA facilities exist as a service connected option for veterans to seek healthcare services. This is commonly a first option for many veterans who have VA benefits. I was curious to see how these facilities compare to the rest of the nation's healthcare facilities. 
- Are veterans more or less satisfied with their healthcare experience compared to the national average?
- How effective are the VA facilities at preventing readmission or complications compared to the national average?
- Are there regions of the country which lack VA facilities in the face of demand? 

---

## Datasets Used

**All data is for the year 2023**

*capstone_agesex*: Veteran and Civilian population data by Age Range\
*capstone_civilian_star_ratings*: Patient survey results, civilian hospitals only\
*capstone_combined_scores*: Facility info including Facility_ID, with composite complications and deaths score, and readmission rating\
*capstone_readmission_comparison*: Facility_ID, lat, lng, State, Region and Readmission Ratings\
*capstone_state_region_count*: Number of facilities by state, with ratio of facilities to patient by state\
*capstone_VA_HCfacilities*: VA facilties list, with Facility_ID primary key\
*capstone_VA_star_ratings*: Patient Survey Results, by facility\
*capstone_VetPop2023_Race_Ethnicity_State_NCVAS*: Veteran race population by state


---

## Methodology

1. Data cleaning
2. Exploratory data analysis
3. Visualization and interpretation
4. Conclusion

---

## Tools and Technologies

- Python 
- Pandas, NumPy, Matplotlib, Seaborn
- Jupyter Notebooks, Power BI, Excel 

---

## Key Findings

Through data exploration and visualization, the conclusion made is that VA facilities perform better than civilian facilities in terms of patient ratings. Readmission rates are about the same as the national average. Interestingly, the Southern area of the US tends to rate lower overall compared to the rest of the VA facilities in other regions. This may be due to less VA facility density in the area, and increase in demand due to population increase.

---

## Dashboard

Note: This Dashboard has 3 pages, toggled at the bottom of the page. The third page is interactive, visualizations change by clicking on the Region Tiles\
[PowerBI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMTI2YzcwMGEtMDI3OC00ODk3LTk2NzEtYTkyMDYxYWIwMzVlIiwidCI6IjEwMWRhNTg3LTE4NDMtNGY1Mi04YjhhLTE3YjA2OWM2NmQzMyIsImMiOjJ9)


---

## 🚀 How to Run

```bash
git clone https://github.com/kshaffer93/capstone.git
pip install -r requirements.txt
jupyter notebook facilities_list.ipynb
```

---

## 📁 Project Structure

```
📦capstone
 ┣ 📂data
 ┣ 📂notebooks
 ┣ 📂slides
 ┣ requirements.txt
 ┗ README.md
```

---

## Acknowledgements

Sources obtained from data.CMS.gov, VA.gov, and census.gov

Thank you to my NSS instructors and cohort mates for support and feedback

---

## 📬 Contact

Kelli Shaffer  
[LinkedIn](https://www.linkedin.com/in/kellishaffer/)  
Email: KLShaffer93@gmail.com
