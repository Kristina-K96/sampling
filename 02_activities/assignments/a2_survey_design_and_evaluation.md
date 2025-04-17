# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `#1`

Describe the purpose of your survey:
```
The purpose of this survey is to better understand the reasons behind the high turnover rates among entry- and lower-level employees at the company. The survey aims to gather feedback on employee satisfaction, workplace culture, management, and perceived opportunities for growth in order to identify areas for improvement.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target population: All current employees working in entry- and lower-level positions across departments.
Sampling frame: The company’s internal employee database filtered by job level and time at the company (e.g., employees with less than 2 years of employment in entry-level roles).
Sampling units: Individual employees within the sampling frame
Observational units: The number of employees who respond to this survey.
Sampling strategy: Stratified random sampling, ensuring representation from different departments.
```

Your 5-10 question survey:
```
1. How long have you been working at the company?
    * Less than 3 months
    * 3-6 months
    * 6-12 months
    * 1-2 years
    * More than 2 years

2. How satisfied are you with your current role?
    * Very satisfied
    * Somewhat satisfied
    * Neutral
    * Somewhat dissatisfied
    * Very dissatisfied

3. To what extent do you agree with the following statement: "I see opportunities for career growth at this company."
    * Strongly agree
    * Agree
    * Neutral
    * Disagree
    * Strongly disagree

3. How would you rate the quality of onboarding and training you recieved when you joined?
    * Excellent
    * Good
    * Fair
    * Poor
    * Very poor
    
5. Do you feel recognized for your contributions at work?
    * Always
    * Often
    * Sometimes
    * Rarely
    * Never

6. How supported do you feel by your direct supervisor?
    * Very supported
    * Somewaht supported
    * Neutral
    * Not very supported
    * Not supported at all

7. Which of the following factors would most influence your decision to leave the company? (Select up to 2)
    * Compensation and benefits
    * Lack of career advancement
    * Workload
    * Company culture
    * Work-life balance
    * Other (Please specify)

8. What is one thing the company could change to improve your work experiment? (Open-ended text answer)

```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: 
Stratified design employing probability sampling. The stratification is done geographically by province/census metropolitan area, and then each strata is randomly sampled.

2. Sample size: 20,950

3. Target population: 
All people 15 years old and older living in the 10 provinces in Canada, who are not living in institutions.

4. Sampling frame: 
One or several telephone numbers associated with a single address based on the Census and administrative sources from Statictics Canada's dwelling frame.

5. Survey mode(s): 
The survey is delivered either through an electronic questionnaire or over the telephone, with an average time of 44 minutes to complete.

6. Timeline: 
September to December of 2018

7. Response rate: 
41.8 %

8. Weights: 
Each person in the sample represents a larger number of people in the population, and the weights are adjusted to ensure that characteristics of the sample represent the population.

9. Data processing: 
Data processing uses the Social Survey Processing Environment (SSPE), which is a software program that follows a series of steps to process the data. 

10. Cleaning, imputation, etc: 
Edits were made to the data both automatically and manually to ensure respondents followed the correct path and fix off-path situation. Error detection was done through the CATI system, which allowed a valid range of codes for each question and identified any out-of-range values. Imputations were made using a score function to determine the "nearest" donor record to fill in the missing information.

11. Sources of error: 
Sampling error, inaccurate and incomplete answers, imperfect coverage of the population, and non-response.

12. Limitations, known biases, etc:
Non-response bias was a known limitation and was reduced by invovling a series of adjustments to the survey weights to account for non-response as much as possible.

13. Link to documentation and any additional sources used
https://www150.statcan.gc.ca/n1/pub/89-653-x/2013002/05-eng.htm#a52
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 18/04/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
