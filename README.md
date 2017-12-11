# HCDS 512 Final Project

# Analyzing Developers on Stack Overflow

## Abstract

The tech industry has gender diversity problem, which is not a secret. Men vastly outnumber women in developer jobs, where much of the power in the industry is located. Gender disparity in tech jobs is wide and deep. It exists at U.S., European and Asian companies. Female tech entrepreneurs also get far less venture capital than startups led by men.

Stack Overflow, as the largest online community for developers, represents the current state of the developers worldwide from some circumstance. Stack Overflow conducted annual developer survey since 2011. The purpose of this survey is to share information of technology and current state of industry with developers. It also helps Stack Overflow to educate their employers to get to know the developers about what they think and what they want.

This project aims to analyze the gender difference of developers on Stack Overflow from multiple perspectives, by conducting quantitative analysis. We can take a closer look at how women and men different in race, developer rols and activities on StackOverflow, by analyzing StackOverflow Developer Survey data.

## Data

Stack Overflow conducts an annual survey for developers on the site since 2011, covering information like programming languages, salary, code style and various other information. In 2017, there are 64,000 responses from 213 countries participated in this survey.

The dataset is dowloaded from Kaggle https://www.kaggle.com/stackoverflow/so-survey-2017

There are two csv files:

survey_results_public.csv is the main dataset where we conduct the data analysis
survey_results_schema.csv is a explaination of each variable in the main dataset, since each variable in the main dataset is a survey question. 

## Data Liscence

Open Database License (ODbL) https://opendatacommons.org/licenses/odbl/1.0/

## Data Cleaning and Analysis

Prerequiste Packages:

- pandas

- numpy

- matplotlib.pyplot

The dataset conatains large amount of text data. We delete irrelevant content in target columns. for most analysis part, under gender catogories, we only select respondents who identify themselves as male or female. People chose the same option will be grouped together. In order to display information efficiently, we c
reated different dataframes to answer each questions. 

Final Project.ipynb contains the project report and the complete data cleaning and analysis process with detailed comments. 

## License and Terms

MIT License

Copyright (c) 2017 Jane Yang

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## References

Roose, Kevin. “Survey Says: 92 Percent of Software Developers Are Men.” Splinter, Splinternews.com, 8 Apr. 2015, splinternews.com/survey-says-92-percent-of-software-developers-are-men-1793846921.

“Google's Gender Problem Is Actually a Tech Problem.” Fortune, fortune.com/2017/08/08/google-gender-struggle-tech/.

Vasilescu, Bogdan, et al. “Gender, Representation and Online Participation: A Quantitative Study of StackOverflow.” 2012 International Conference on Social Informatics, 2012, doi:10.1109/socialinformatics.2012.81.
