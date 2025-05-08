# NHS A&E Data Analysis (Provider Level)

A real-world data analysis project using NHS England’s monthly A&E attendance data.  
This project focuses on cleaning, exploring, and visualising provider-level emergency attendance trends.

---

## Table of Contents
- [About the Dataset](#about-the-dataset)
- [Project Goals](#project-goals)
- [Tools Used](#tools-used)
- [Summary of Cleaning Steps](#summary-of-cleaning-steps)
- [Folder Structure](#folder-structure)
- [Key Insights](#key-insights)
- [License](#license)

---

## About the Dataset

Source: [NHS England – A&E Attendances and Emergency Admissions](https://www.england.nhs.uk/statistics/statistical-work-areas/ae-waiting-times-and-activity/)  
Sheet Used: **Provider Level Data**  
The dataset contains monthly A&E attendances and emergency admissions across NHS trusts in England.

---

## Project Goals

- Clean and structure raw NHS Excel files
- Analyze hospital-level trends in A&E usage
- Identify wait time performance issues
- Present visual insights for policy and planning

---

## Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Excel / CSV
- Visual Studio Code

---

## Summary of Cleaning Steps

- Loaded Excel file and reviewed available sheets
- Selected the correct sheet: "Provider Level Data"
- Skipped unnecessary top rows to reveal headers
- Saved cleaned version as CSV


## Folder Structure

<pre>
project-folder/
│
├── data/
│   ├── raw/            # Original NHS Excel file
│   └── cleaned/        # Cleaned CSV ready for analysis
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── 03_visualizations.ipynb
│
└── README.md  </pre>


## License

This project is licensed under the MIT License.  
The dataset is sourced from publicly available NHS England publications.
