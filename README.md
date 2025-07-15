# Analysis of Lok Sabha Elections (India) using Power BI

## Overview / Objective

This project focuses on analyzing historical data from Lok Sabha elections — the lower house of India's bicameral Parliament. Given the size and diversity of India's democracy, the goal is to uncover insights into:

- Voting patterns  
- Party performance  
- Regional strongholds  
- Demographic influence on elections  

The primary objective was to build an **interactive Power BI dashboard** that enables scalable and meaningful visual analysis of India's general elections. This is helpful for:

- Political analysts  
- Students and researchers  
- Data science learners  
- Policy and campaign strategists  

---

## Problem Statement

Indian elections involve thousands of constituencies, hundreds of political parties, and complex voter behaviors. Manually analyzing such data is both tedious and error-prone.

**Problem Statement:**  
_“How can historical Lok Sabha election data be visualized and analyzed to uncover trends in party dominance, regional patterns, voter turnout, and electoral behavior?”_

This Power BI project aims to simplify this through interactive visual storytelling.

---

## Dataset Description

The dataset was sourced from a **Codebasics Power BI Challenge**, comprising constituency-level results from **2009, 2014, and 2019** Lok Sabha elections. It contains **5,000+ records** with essential features such as:

### Key Columns:
- `Election Year`: Year of election (2009, 2014, 2019)  
- `State`: Indian state or UT  
- `Constituency`: Parliamentary constituency name  
- `Candidate Name`: Name of the contestant  
- `Party`: Candidate’s political party  
- `Votes Received`: Votes polled  
- `Position`: Final rank (1 = Winner)  
- `Total Electors`: Registered voters in constituency  
- `Turnout`: Voter turnout  
- `Margin`: Difference between winner and runner-up  
- `Gender`: Candidate gender  
- `Age`: Candidate age (if available)  

---

## 🧹 Data Cleaning & Preprocessing

Performed using **Power Query in Power BI**:

- Removed null values and duplicate rows  
- Standardized party names (e.g., “BJP” vs “Bharatiya Janata Party”)  
- Created calculated columns:
  - `Vote Share`
  - `Voter Turnout % = Turnout ÷ Total Electors`
  - `Winning Margin %`
- Formatted state and year columns for slicers  
- Aggregated data for:
  - State-wise & year-wise seat share
  - Gender & age distribution
  - Party-wise trends  

---

##  Power BI Dashboard

An interactive Power BI dashboard was created featuring:

- **Bar Charts**: Party-wise vote share, top seats  
- **Line Charts**: Yearly performance trends  
- **Maps**: State-wise seat share and margins  
- **Tables & Cards**: Key figures like margin, turnout, winners  
- **Slicers**: Filter by year, party, gender, state, and more  

 _Dashboard screenshots can be found in the `/screenshots` folder._

---

##  Key Findings & Insights

- **BJP and INC** are the leading parties across the 3 election years, though regional dominance varies.  
- **Uttar Pradesh**, **Maharashtra**, and **West Bengal** are pivotal states due to high seat counts.  
- **Regional parties** like TMC (West Bengal), DMK (Tamil Nadu), BJD (Odisha), and AAP (Delhi) dominate their respective territories.  
- **Winning margins** tend to be tighter in urban constituencies, indicating close competition.  
- **Voter Turnout Ratio** (Turnout ÷ Total Electors) has steadily increased:
  - In **2019**, the average turnout was **~67%**, the highest in recent years.  
  - **North-eastern states** like Nagaland and Mizoram often exceed **75% turnout**.  
  - **Urban areas** like Mumbai, Delhi, and Bengaluru generally have **<55% turnout**, despite high literacy.  
- **Female representation** is increasing in both candidacy and voter participation, though still underrepresented.  
- **Vote Share vs Seats Won**: Some regional parties with small vote share manage higher seat counts due to concentrated local support.

---

##  Tools & Technologies Used

- **Power BI Desktop**  
  - Power Query for data wrangling  
  - DAX for measures and calculated columns  
  - Slicers, maps, custom visuals  
- **Excel** for preliminary cleanup and checks  

---

## Conclusion & Recommendations

### Conclusion:

Analyzing Lok Sabha election data using Power BI provided a comprehensive and scalable approach to visualize India's democratic trends. The dashboard serves as a powerful tool to explore voter behavior, party strategy, and electoral outcomes interactively.

### Recommendations:

- **Boost urban voter turnout** with awareness campaigns in cities like Mumbai and Bengaluru.  
- **Focus on close-margin constituencies** for optimized political campaigning.  
- **Encourage female candidacy and leadership** through reservation and awareness policies.  
- **Analyze vote-to-seat conversion efficiency** for parties to assess regional strategy.  
- **Replicate high-turnout state strategies** in low-engagement regions.

---


---

## Acknowledgements

- Data Source: Monthly Power BI Challenge by <a href="https://codebasics.io/challenges/codebasics-resume-project-challenge/14"> Codebasics </a> 
- Thanks to the **Power BI community and mentors** for guidance  
- Created as part of a data storytelling and visualization practice project


