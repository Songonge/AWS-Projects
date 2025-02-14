# Project: Loan Analysis

## Table of Contents  
1. [Introduction](#introduction)
2. [Objective](#objective)
3. [Data Acquisition and Preparation](#data-acquisition-and-preparation)
4. [Data Processing](#data-processing)
5. [Data Analysis and Visualization](#data-analysis-and-visualization)
   * [Total Loan Amount Over Time](#total-loan-amount-over-time)
   * [Loan Amount by Grade](#loan-amount-by-grade)
   * [Loan Purpose Overview](#loan-purpose-overview)
   * [State Comparison](#state-comparison)
6. [Recommendations](#recommendations)
   * [Recommendations for State A](#recommendations-for-state-a)
   * [Recommendations for State B](#recommendations-for-state-b)
   * [Self-Service Debt Tools](#self-service-debt-tools)
   * [Virtual Financial Counseling](#virtual-financial-counseling)
   * [Call To Action](#call-to-action)
7. [Conclusion](#conclusion)

## Introduction
This project is a hands-on training experience to build powerful business use cases using Amazon Q in QuickSight in the context of pseudo imaginary use case of the Home Mortgage Disclosure Act (HMDA). The HMDA requires financial institutions to maintain, report, and publicly disclose loan-level information about mortgages.  This project examines trends in the loan domain to shed light on the debt challenges facing many consumers. By analyzing lending patterns across different locations and credit profiles, it aims to identify opportunities for more affordable options that can help ease financial burdens and set citizens up for long-term prosperity.

## Objective
Provide an overview of residential mortgage lending in 2022 based on the data collected under the Home Mortgage Disclosure Act (HMDA).
The report summarizes: 
* Mortgage applications and originations, characteristics of home loans originated.
* Denial rates of mortgage applications in 2022.
* Monthly trends and activities of the mortgage market in 2022 including total applications.
* Trends in interest rates and their impact on payment burdens
* Breakdown of lending institutions that reported data under the HMDA in 2022 and their market shares.

## Data Acquisition and Preparation
Data were collected under the Home Mortgage Disclosure Act (HMDA) and provided by AWS. This dataset was already cleaned and had 14 columns in total.

## Data Processing
The tool I used to perform the analysis was Amazon Q in Amazon QuickSight. That is because Amazon Q in Amazon QuickSight enhances business productivity using Generative BI capabilities to accelerate decision-making. It also allows delivering easy-to-understand insights to your colleagues, no matter where they are. Moreover, it combines different data sources into one analysis and publishes/shares it as a dashboard.
* To begin with, the Amazon Q application was created and Amazon Q in QuickSight was configured. 
* Then the dataset was added by uploading the Sample_Top_Respondents file (previously downloaded).

## Data Analysis and Visualization

### Total Loan Amount Over Time
  
<figure>
  <img src="https://github.com/Songonge/Data-Analytics-Projects/blob/main/All Projects/Loan Analysis/Amount by Month.png" width=50% height=50% alt="alt text">
  <figcaption>Figure 1: Total Loan Amount Over Time </figcaption>
</figure>
<br/><br/>

  * Total loan amounts across all states have fluctuated substantially over the past few years. 
  * Loan balances typically peak in December of each year, coinciding with holiday spending. 
  * From November to December 2023 alone, total debt grew by over half a million dollars - an increase of nearly 6%. 
  * Loan levels exhibit strong seasonal patterns and consistent year-over-year growth. 
  * Exploring opportunities to streamline lending and promote responsible personal finance practices has become increasingly important. 
	
### Loan Amount by Grade
  
<figure>
  <img src="https://github.com/Songonge/Data-Analytics-Projects/blob/main/All Projects/Loan Analysis/Amount by Grade.png" width=75% height=75% alt="alt text">
  <figcaption>Figure 2: Loan Amount by Grade</figcaption>
</figure>
<br/><br/>

  * Borrowers with credit grades of A, B, and C, carried the highest total loan amounts, with Bgrade having $44,834,450 outstanding loans. This suggests that individuals with fair-to-good credit are utilizing loan programs more than those with lower credit scores.  
  * Borrowers with grades of E, F, and G had significantly lower total loan balances, with Ggrade having just $1,689,225 in debt.  
  * Analyzing lending patterns across credit tiers can provide insights for helping more customers improve their financial wellness through debt consolidation or programs tailored to their credit needs. 

### Loan Purpose Overview

<figure>
  <img src="https://github.com/Songonge/Data-Analytics-Projects/blob/main/All Projects/Loan Analysis/Amount by Purpose.png" width=75% height=75% alt="alt text">
  <figcaption>Figure 3: Loan Amount by Purpose </figcaption>
</figure>
<br/><br/>

  * Small business, house, and debt consolidation loans accounted for the majority of loan purposes, with totals of 35,000, 35,000, and 32,000 respectively.  
  * Educational and car loans also represented sizable portions at 15,350 and 14,400.  
  * Other, credit card, and vacation loans had significantly lower totals.  
  * Exploring opportunities to refinance high-interest small business, housing, and debt consolidation loans could help borrowers reduce costs and better manage their finances in line with the presentation's objective. 

### State Comparison

<figure>
  <img src="https://github.com/Songonge/Data-Analytics-Projects/blob/main/All Projects/Loan Analysis/Loan By State.png" width=75% height=75% alt="alt text">
  <figcaption>Figure 4: Total Loan Amount by State</figcaption>
</figure>
<br/><br/>

  * The FILLED_MAP graph shows Total Loan Amount by State and provides valuable context to analyze differences in loan trends across geographic regions.  
  * This visual aids in accomplishing the section objective by highlighting for stakeholders how total debt levels vary between locations. 
  * Additional insights may help address the user’s goal of providing recommendations on better debt consolidation and lowering loan interest rates in specific states.  
  * By examining loan patterns between states uncovered in the data, opportunities could emerge to tailor financial wellness solutions and messaging to particular audiences.

<figure>
  <img src="https://github.com/Songonge/Data-Analytics-Projects/blob/main/All Projects/Loan Analysis/Loan Analysis Dashboard.png" width=100% height=100% alt="alt text">
  <figcaption>Figure 5: Loan Analysis Dashboard</figcaption>
</figure>
<br/>

## Recommendations

### Recommendations for State A
This section aims to provide targeted recommendations for a high-debt state. A graph showing forecasted loan trends for State A is needed to effectively visualize potential debt growth and identify opportunities for intervention. None of the available graphs appear to match this ideal visual or support the objective of recommending customized solutions. For example, with this forecast graph, the text could explain that projecting future loan amounts in State A reveals the need for programs tailored to its residents’ specific financial challenges.

### Recommendations for State B
This section aims to provide targeted recommendations for State B. A graph showing the loan purpose breakdown for residents in this state would help achieve the objective by visualizing how funds are currently allocated. None of the available visuals appear tailored to this need. For example, with this ideal visual, one could say that residents in State B would benefit from financial wellness courses focused on discretionary spending habits, as the graph indicates a pattern of high-interest debt in that category.

### Self-Service Debt Tools
To better assist customers in improving their financial wellness, our company has developed a suite of online debt management tools. These Self-Service resources budgeting assistance, loan payment calculators, and refinancing options to help users make more informed financial decisions at their own convenience. Through accessible debt resources, our goal is to empower users to take control of their financial obligations.

### Virtual Financial Counseling
Virtual Financial Counseling offers a personalized approach to resolving debt-related issues. Through individualized sessions, certified counselors can evaluate a client’s unique financial circumstances and recommend tailored strategies. This specialized guidance provides comprehensive debt solutions for those facing complex debt management needs.

### Call to Action
It is time for change. By utilizing the resources now available, individuals can take important steps to better their financial future and ease the burden of debt. With tools for guidance and support, audiences hold the power to chart a new course toward greater financial wellness.

## Conclusion
The presentation provided a comprehensive analysis of loan trends in different states and regions. By exploring patterns in total debt levels, loan purposes, and credit attributes, several opportunities were identified to help more individuals and communities access financial tools and resources to reduce debt burdens sustainably.
 

<br/><br/>

**Thank you for taking the time to read this report!** 

**Please reach out for any updates.**

### Author
[Edwige Songong](https://github.com/Songonge) Powered by [AWS Summit](https://aws.amazon.com/events/summits/washington-dc/)
