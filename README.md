# Analyse A/B test results
## By Rahal Mehdi Abdelaziz


## Datasets

We have two datasets for this project: ab_data and countries
ab_data: comports 294478 rows with 5 features ( user_id, timestamp, group, landing_page, and converted)
countries: user_id, country



## Introduction

A/B tests are very commonly performed by data analysts and data scientists. It is important that you get some practice working with the difficulties of these
In this notebook, an A/B test is runned by an e-commerce website, the goal is to understand if the company shouldimplement the new page , keep the old page or run the expriment longer to make their decision



## In this notebook the study is done on three parts:

Part I: for statistical exploration
Part II: A/B Test
Part III: A regression approach




## Summary of findings

pval>0.05, zscore<1.64
nb: 1.64 is the critical value for  a=0.05 
conclusion: we fail to reject the nul hypothesis, so we should keep the old page.
