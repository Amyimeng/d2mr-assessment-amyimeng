---
title: "Project Overview: Data Wrangling and Analysis on Star Wars Universe"
editor_options: 
  markdown: 
    wrap: 72
---

# Main Purpose

The purpose of this repo is to wrangle data and analyze the Star Wars
universe dataset, specifically focusing on transforming, cleaning, and
organizing character data to uncover insights about species, physical
attributes, and demographic distributions. Through systematic data
manipulation, I aim to provide a well-structured dataset that can serve
as a foundation for advanced statistical analysis and visualization. The
project demonstrates the practices of data wrangling using the dplyr,
tidyr, and stringr packages within the tidyverse framework.

# Data Used

The dataset is derived from the built-in **starwars** dataset, which
contains detailed information about characters from the Star Wars
universe.

Key attributes include:

**Name:** Full name of each character.

**Height and Mass:** Physical measurements in centimeters and kilograms.

**Hair Color:** Character's hair color, including various shades and
baldness.

**Gender and Species:** Demographic and biological classifications.

**Homeworld:** Planet of origin.

**During the data wrangling process, the following transformations were
made:**

**Renaming and Relocating Columns:** Height was converted to inches
(height_in) for better interpretability.

**Handling Missing Values:** hair_color was standardized with "bald" for
missing values.

**Character Splitting and Initials Creation:** Names were split into
first_name and last_name, and initials were generated.

**Logical Variable Creation:** A new column brown_hair was added to
indicate whether a character's hair contained the word "brown".

**Data Type Standardization:** Categorical variables were converted to
factors to ensure consistency in analysis.

# Additional Operations

Species that have low frequencies were combined into "other".

# Repo Structure

```{=html}
<pre>
d2mr-assessment-amyimeng/
│
├── .gitignore
├── .RData
├── .Rhistory
│
├── 00_in-class-materials/
│
├── 01_data-cleaning/
│
├── 02_data-wrangling/
│   ├── 00_wrangling-walkthrough/
│   ├── 01_wrangling-level-1/
│   │   ├── assessment.md
│   │   ├── README.md
│   │   ├── recreate-level-1.qmd
│   │   └── sw-wrangled.csv
│   │
│   ├── 02_wrangling-level-2/
│   ├── 03_group-make-a-mess/
│   └── 04_ots-nonrect-nested/
│
├── 03_data-viz/
│
├── 04_data-analysis/
│
├── 05_data-communication/
│
├── 06_r-programming/
│
├── 07_git-github/
│
├── 08_unassessed-misc/
│
└── 99_off-the-menu/
│
├── assessment.md
├── d2mr-assessment-amyimeng.Rproj
└── ...
</pre>
```
