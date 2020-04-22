# stackoverflow_2019_insights
This project is data analysis for the Stack Overflow 2019 Survey dataset to analyse gender disparity from different aspects.

## Project Motivation:
I was interested in understanding what Stack Overflow survey result can tell us about gender diversity, bias and disparity so I chalked out following questions that I find would be interesting to find answers for from the available dataset:

- How many IT professional took part in the survey? How many Pakistani IT professional took part in the survey
- How many of them were Men, Women and others? which one was in the majority of participating in the Survey?
- Is there any profession in which women have more representation than men (based on this survey)?
- What is the distribution of women across different years since coding? how is it different from men?

## What is included?

The dataset used has 2 parts/files:
- survey-results-schema.csv file: contains code book for columns in "survey-results-public.csv" file, it shows detailed description of the question asked.
- survey-results-public.csv: contains actual survey result

- Analysis of the dataset is available in jupyter notebook with title: "StackOverflow_Survey_Insights_Code.ipynb"

## Installation
Since the dataset was too large to be uploaded directly on Github, I have uploaded a zipped folder containing the dataset files, user of this repo should unzip/extract those files and put that in the same folder in which jupyter notebook is present for running notebook locally.
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

## Results
The main findings of the code can be found at the post available [here](https://medium.com/@Sidrah/what-does-stackoverflow-2019-survey-tell-us-about-gender-diversity-93df57b32b38).

## Acknowledgements
I must give credit to Stack Overflow for the data. The dataset can be found [here](https://insights.stackoverflow.com/survey)
