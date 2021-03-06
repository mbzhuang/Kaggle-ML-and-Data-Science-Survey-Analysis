# A Deep Dive into the 2017 Kaggle Machine Learning and Data Science Survey Results
DATA 512 - UW Interdisciplinary Data Science Masters Program, Final Project

Created by: Mobing Zhuang

Abstract:
This study is conducted on the datasets from Kaggle's 2017 industry-wide survey on machine learning and data science. The analysis in this study revealed insights from the Kaggle survey results in the aspects of the career, the salary, and the language use of data scientists. The respondents are mostly from U.S. and India, with at least bachelor degree, and mostly major in computer science, maths or stats, electrical engineering, and other engineering disciplines. We also found that globally, as a data scientist, higher education lead to higher annual salary. But in the U.S., the salary is similar between bachelor and master graduates. In terms of language choice, Python is more popular compared to R and people tend to use them for different tasks. With many high tech companies, U.S. is most advanced in the data science field, thus receiving most respondents from here and having the highest annual average salary.

Source Data Information:
- Kaggle: the data sets includes 5 files:
  - schema.csv: This CSV file includes the survey questions that correspond to each column name in both the multipleChoiceResponses.csv and freeformResponses.csv.
  - multipleChoiceResponses.csv: Respondents' answers to multiple choice and ranking questions. A single row is the answer from the same respondent.
  - freeformResponses.csv: Respondents' freeform answers to Kaggle's survey questions. A single row is not the answer from the same respondent.
  - conversionRates.csv: Currency conversion rates to USD 7.
  - RespondentTypeREADME.txt: This describes respondent type in the "Asked" column of the schema.csv file.

- Accessed on 12/10/2017.
- Downloaded from: https://www.kaggle.com/kaggle/kaggle-survey-2017/downloads/kaggle-survey-2017.zip
- The data is released under Open Database license, specifically, [ODC Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/1.0/). Users are free to share, to produce works, to modify, transform and build upon the data, as long as they attribute, share-alike, and keep open. [Click to read detailed explanations of how the data can be used.](https://opendatacommons.org/licenses/odbl/summary/)

Files:
- LICENSE
  - The MIT License for the code (Kaggle-ML-and-Data-Science-Survey-Analysis.ipynb).
- Kaggle-ML-and-Data-Science-Survey-Analysis.ipynb
  - Fully documentated jupyter python notebook that uses data from Kaggle.
  - Includes a reflection on biases present in these data.
  - Input: data files from Kaggle (RawData folder).
  - Output: visualizations in the (Visualization folder).
