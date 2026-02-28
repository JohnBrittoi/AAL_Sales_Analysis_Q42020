# AAL_Sales_Analysis_Q42020
Jupyter notebook to analyse Quarter 4 2020 sales data across Australian states and customer groups. Its created for the Assessment for the topic 'Applied Data Science with Python' (Purdue AI ML professional Certification).

## Table of Contents

- [Dataset](#-dataset)
- [Features](#-features) 
- [Requirements](#-requirements)
- [Key Findings](#-key-findings)
- [Acknowledgments](#-acknowledgments)

## Dataset

**`[Sales Analysis4thQrt2020.csv](https://github.com/JohnBrittoi/AAL_Sales_Analysis_Q42020/tree/main)`** (7,560 rows × 6 columns)

| Column | Description | Key Stats |
|--------|-------------|-----------|
| Date | Oct 1 - Dec 30, 2020 | Daily |
| Time | Morning/Afternoon/Evening | - |
| State | NSW, VIC, QLD, SA, WA, NT, TAS | VIC highest |
| Group | Kids, Men, Women, Seniors | Men highest |
| Unit | Units sold | Mean: 18 (2-65) |
| Sales | Revenue ($) | Mean: $45K ($5K-$162K) |

**No missing values**

## Features

- Data exploration & cleaning
- State/Group/Time aggregations  
- Descriptive statistics
- Box plots, histograms, bar charts

## Requirements
pandas
matplotlib  
seaborn
jupyter

## Key findings
- State: VIC is the highest performing state  
- Group: Men is the highest spender  
- Time: Evening sessions have more sales  
- Month: December had peak sales

## Acknowledgements
Purdue University AI ML Online Certification by Simplilearn


