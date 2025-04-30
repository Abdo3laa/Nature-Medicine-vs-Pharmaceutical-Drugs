# 📊 Nature Medicine vs Pharmaceutical Drugs – Survey & Data Analysis Project

## 📌 Project Overview
This university project explores public perceptions and usage patterns of **natural medicines** versus **pharmaceutical drugs**, particularly antibiotics. With growing concern over the overuse of pharmaceutical drugs, this survey-based study aims to highlight treatment preferences across different age groups and environments (urban vs rural). 

## 🎯 Objectives
The project investigates:
- The percentage of people who prefer natural medicine.
- Opinions on long-term antibiotic use.
- Perceptions of effectiveness and recovery speed.
- Treatment choices based on recent illness experiences.
- Preferences between natural and pharmaceutical treatments.
- Demographic trends: age group differences and rural vs urban upbringing.

## 👥 Participants
Participants were divided into three main age groups:
- **Children (1–15)**
- **Teens & Young Adults (16–27)**
- **Adults (28+)**

At least 5 individuals from each group were surveyed to ensure diversity. Urban/rural background was also considered to assess its influence on treatment preferences.

## 📄 Survey Design
The survey was built using **Google Forms** and included:
- **Demographics** (age, gender, chronic illnesses)
- **Multiple-choice** and **Likert scale** questions
- **Open-ended** responses for personal insights

## 🧹 Data Cleaning & Preprocessing

### 🔧 Power BI (Power Query)
- Translated data from **Arabic to English**
- Extracted and normalized **multi-select columns** into a new relational table
- Built relationships between original and split tables for dynamic analysis

### 🐍 Python (Pandas & Sklearn)
- Cleaned data (removed **nulls**, **duplicates**, and **outliers**)
- Generated a **correlation matrix** and **Chi-square test matrix**
- Performed **dimensionality reduction** based on impurity thresholds
- Built a **Decision Tree Model** to explore key influencing factors

## 📊 Dashboard & Visualization
Created an **interactive Power BI Dashboard** with 4 pages:
1. **Population Overview**
2. **Medication Usage and Preference**
3. **Medical Advice and Cost Accessibility**
4. **Health and Medication Usage**

The dashboard is **live-updated** with every new response submitted through the survey.

## 📅 Timeline

| Week | Task                                   |
|------|----------------------------------------|
| 1    | Survey design & question finalization  |
| 2    | Survey distribution                    |
| 3    | Data collection                        |
| 4    | Data cleaning & analysis               |
| 5    | Final reporting & dashboard deployment |

## 💰 Budget
- **Cost: $0**
- Tools used: Google Forms, Power BI, Python (free libraries)
- No paid tools or participant incentives required

## 🔒 Ethics & Confidentiality
- No sensitive data collected
- Anonymized responses
- One-response limit per participant to avoid duplicates

## ✅ Conclusion
This project offers **data-driven insights** into public attitudes on healthcare choices. The integration of Power BI for real-time visualization and Python for statistical modeling provides a holistic view of the treatment landscape. The findings can inform discussions on **holistic healthcare**, combining natural and pharmaceutical methods effectively.
