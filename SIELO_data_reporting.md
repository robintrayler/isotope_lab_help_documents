
---
title: SIELO Data Reporting
author: Robin B. Trayler
pdf-engine: xelatex
mainfont: Helvetica
geometry: margin=1in
fontsize: 12pt
tblPrefix: Table
figPrefix: Figure
indent: true
---

Since this if your first time getting data from the SIELO let me explain what you’re getting. Each batch of samples analyzed is assigned a run ID. This is the name of the instrument (EA) followed by the date of analysis in year-month-day format. So these samples were analyzed on 2022 - 05 - 23 so the run ID is EA20220523. It was also the first batch of the day so it gets an `a` after the ID. Each individual sample also gets a unique identifier number called “identifier 1”. If you ever have a question about your data telling me the Run ID or identifier 1 numbers means I will be able to quickly track it down (note that the Identifier numbers are in the 19,000’s now so I have a lot of data to keep track of).

1) the _corrected.csv file has your corrected isotope and elemental content data in it. 
2) the _report.html details the corrections made and has some summary statistics about the reference materials. There is also a methods section at the bottom. 
3) the _raw.csv file contains the raw data from the mass spectrometer. 
4) the _code.Rmd file is an R markdown file that will parse the _raw.csv and generate the report and corrected data. 

I give you these files each time to ensure that SIELO data analysis is completely open and reproducible. 
