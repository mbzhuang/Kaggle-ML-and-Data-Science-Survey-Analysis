# A Deep Dive into the 2017 Kaggle ML and Data Science Survey Results


DATA 512 - UW Interdisciplinary Data Science Masters Program

Course Project Plan

Mobing Zhuang


## 1. Project Introduction

### 1.1 About the survey

In 2017, Kaggle conducted a [survey](https://www.kaggle.com/kaggle/kaggle-survey-2017) through Kaggle channels with the intention to establish a comprehensive view of the current state of data science and machine learning field.

16,716 usable survey responses were received from 171 countries and territories. The respondents were found through kaggle’s email list, discussion forums and social media channels. Questions in the survey consists of required and non-required ones. Survey responses were flagged as “spam” if their employment status, which is the first required question, was not answered. The survey is designed to only asking relevant questions to each respondent. In summary, this was a very well designed survey.

### 1.2 About the data

The data sets includes 5 files:

- schema.csv: This CSV file includes the survey questions that correspond to each column name in both the multipleChoiceResponses.csv and freeformResponses.csv.
- multipleChoiceResponses.csv: Respondents' answers to multiple choice and ranking questions. A single row is the answer from the same respondent.
- freeformResponses.csv: Respondents' freeform answers to Kaggle's survey questions. A single row is not the answer from the same respondent.
- conversionRates.csv: Currency conversion rates to USD 7.
- RespondentTypeREADME.txt: This describes respondent type in the "Asked" column of the schema.csv file.

### 2. Project Goal

Data scientist has been referred to as the "sexiest job of the 21st century" and "best job of the year 2016" by Harvard Business Review and Glassdoor respectively. The goal of this project is to dive deep into the survey results and get a comprehensive understanding of state of data science and the job itself. This project will inform us what’s happening at the cutting edge of data science across industries and subsequently guide new data scientists breaking into the field.

I will design the analyses in attempt to answer the following questions, which are potentially important information for people in the field.

- What hardware and cloud service are being used? Which one is the most popular and what are their advantages over others?
- What programming languages do data scientists know? Or do data scientists need to know any language like C++, C##, or Java?
- In terms of data analysis, Python or R? Which one is gaining popularity? How about the global distribution of Python and R users.
- What software or tools are being used for data visualization?
- What do data scientists want to learn? What are the hottest skills?
- How is the gender balance among data scientists? Is the balance or imbalance same globally?

### 3. Research Approach

Add additional notes about how to deploy this on a live system

##### Step 1. Data munging and exploration
Tools: R

Visualization: R Plotly

In this step, I will first deal with data quality issues, like missing value and formatting. Subsequently, merging datasets in preparation for later analysis. And then explore the final dataset by data aggregation and interactive visualization.

##### Step 2. Refine research questions

This step is mainly brainstorming and research. I will refine the questions in section 2 and bring out more questions that seems potentially interesting after know exploring the data more. Additional dataset may be brought to this research as reference or comparison. For instance, in the gender balance question, compare the results with the gender balance of college science and engineering major students of the corresponding country, if there is dataset available.

##### Step 3. Data visualization product development
Tools: R Shiny

Visualization: R Plotly

A dashboard will be built using R Shiny, which is the major deliverable of this project. Analysis results will be shown in this interactive dashboard so that users or audiences of the study will explore the topic better. Other deliverables are a report and a well documented github repo.

### 4. Human Centered Data Science Elements of the Project

Here are the key elements of human centered data science that I will always remind myself of as the study goes on.

- Replicability and reproducibility
- License of source data,  copyright,
- Privacy policy and terms of use


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
