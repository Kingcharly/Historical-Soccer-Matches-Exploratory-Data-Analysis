# Historical International Football Match Analysis

# INTRODUCTION
This portfolio project aims to analyze historical international football matches to gain valuable insights into team performance, match outcomes, and tournament trends. By examining a dataset containing records of past matches, our objective is to uncover factors that have influenced team success, understand the prevalence of different match outcomes, and identify noteworthy trends or patterns in tournament participation and performance. The analysis conducted in this project will provide a comprehensive understanding of the historical landscape of international football, offering stakeholders actionable insights to inform decision-making and enhance future strategies pertaining to team performance and tournament participation

## PROBLEM STATEMENT
In the realm of international football, a wealth of historical match data exists, which, when carefully examined and analyzed, can yield valuable insights into the game. Our project centers around the exploration and examination of a dataset comprising records of historical international football matches. We seek to uncover essential details and patterns hidden within the data, shedding light on team performance, match outcomes, and tournament trends. By focusing on these key aspects, we aim to identify the factors that have contributed to team success and failure, ascertain the prevalence of different match outcomes, and discern any notable trends or patterns in tournament participation and performance.

Through this analysis, we endeavor to address fundamental questions related to historical international football matches. What are the key determinants of team success? How have match outcomes varied over time? Are there specific tournament trends that emerge from the data? By delving into these inquiries, we seek to provide stakeholders with a deeper understanding of the historical landscape of international football. Armed with this knowledge, stakeholders can make informed decisions and develop strategies that enhance team performance and optimize tournament participation.

The outcomes of this analysis hold significant implications for various stakeholders within the realm of international football. Coaches and team managers can leverage the insights gained to fine-tune their training programs, identify areas of improvement, and devise effective strategies for future matches. Football associations and governing bodies can utilize the findings to inform the development of policies and regulations that promote fair play and enhance the overall quality of international tournaments. Additionally, media organizations and sports analysts can use the insights to provide comprehensive coverage, engaging audiences with in-depth analyses and discussions.

In summary, this portfolio project aims to leverage historical international football match data to extract insights into team performance, match outcomes, and tournament trends. By unraveling the factors influencing team success, understanding match outcomes, and identifying notable trends and patterns, this analysis will contribute to a deeper understanding of the historical landscape of international football. The resulting insights will empower stakeholders to make informed decisions and develop strategies that enhance team performance and optimize tournament participation.

## Tools Used
To clean, analyze and provide insights, the following tools were used
- Pandas
- Matplotlib.pyplot

# DATA COLLECTION AND PRE-PROCESSING 
To conduct our analysis, we collected a comprehensive dataset of historical international football matches from an [International Football results from 1872 to 2023](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017?select=shootouts.csv)

The original dataset includes **44,341** rows spread accross 3 different CSV file format which encompasses matches range from FIFA World Cup to FIFI Wild Cup to regular friendly matches. The matches are strictly men's full internationals and the data does not include Olympic Games or matches where at least one of the teams was the nation's B-team, U-23 or a league select team.

Before proceeding with the analysis, we performed preprocessing steps to ensure data quality and consistency. This involved handling missing values, standardizing data formats, and resolving any discrepancies in the dataset. 
