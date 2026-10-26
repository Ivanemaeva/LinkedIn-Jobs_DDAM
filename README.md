# LinkedIn Job Postings — DDAM Project

**Course:** Distributed Data Analysis and Mining (Prof. Valentina Pansanella)  
**University:** Università di Pisa — M.Sc. Data Science & Business Informatics  
**Academic Year:** 2026/27  
**Author:** Ivane Maeva Nague  

## Overview

You work as a labour market analyst for a public employment agency.
The agency wants to understand how companies advertise jobs: where pay
and remote work are disclosed, and how job offers differ across companies.
The project is built with PySpark.

## Dataset

**Source:** Kaggle — LinkedIn Job Postings (2023–2024) by arshkon  
**Scope:** 123,849 job postings, 24,473 companies, 20 March – 20 April 2024 (US)  
**Tables:** postings, companies, company_industries, company_specialities,
employee_counts, benefits, job_industries, job_skills, salaries,
industries, skills  

Data is not stored in this repo. Download it from Kaggle and place the CSVs in `data/`.

## Questions

**Analytical**
- **Q1:** Which industries and states are more likely to include salary information in their job ads?
- **Q2:** Which companies and industries advertise remote work, and how does their pay compare with jobs that have no remote label?
- **Q3:** Do large and small companies offer different kinds of jobs?

**Learning**
- **Q4 (Supervised):** Can we predict whether a job ad includes salary information?
- **Q5 (Unsupervised):** Can we group similar job ads using skill categories and job titles?

## Repository Structure

    data/        CSV files (not tracked)
    notebooks/   01_setup → 02_cleaning → 03_analytics → 04_supervised → 05_unsupervised
    figures/     Charts used in the report
    report/      Final report (PDF)

## Technologies

Python · PySpark · Spark MLlib · Spark SQL · Pandas · Matplotlib · Google Colab

## Results

*To be added.*

## Report & Presentation

*To be added upon completion.*
