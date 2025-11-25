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

* The purpose of my survey is to understand why entry- to lower-level employees are leaving the company, and to see if there are any ways my company can implement to prevent this from happening. With my survey, I want to identify any potential problems that these employees are facing and what changes would prevent these employees from leaving.

Describe your target population, sampling frame, sampling units, and observational units:

* Target population: 
    * Current full-time employees from Tech Company who earn a salary band from: $0 - $50,000 or are classified under new graduate status
* Sampling frame: The portion of current full-time employees from Tech Company who earn a salary band from: $0 - $50,000, or are classified under new graduate status, who completed my survey
* Sampling units: employees (rows, eg. trees)
* Observational units: company culture, career progression, salary, work-life balance, stress levels, vacation allotment (columns, eg. characteristic of trees - height, species)
* Sampling strategy: I want to use Stratified Sampling --> stratify across all departments in my company and then do a random sampling of employees in these departments. 

Your 5-10 question survey:

1. Do you like the company culture? 
            Yes     No
2. Do you like your current position? 
            Yes     No
3. From 1-5, how do you feel about your career progression and/or possibility for promotions? (1 - bad, 5 - good)
            1   2   3   4   5
4. From 1-5, how do you feel about your salary? (1 - bad, 5 - good)
            1   2   3   4   5
5. From 1-5, how do you feel about your work-life balance? (1 - bad, 5 - good)
            1   2   3   4   5
6. From 1-5, what do you feel are your current work stress levels? (1 - bad, 5 - good)
            1   2   3   4   5 
7. From 1-5, how do you feel about your current vacation allotment? (1 - bad, 5 - good)
8. Which area of improvements below do you believe could contribute to a better work environment for you?
    * company culture
    * career progression
    * salary
    * work-life balance
    * stress levels
    * vacation allotment
9. write your question here... (optional)
10. write your question here... (optional)


## Part B - Survey Evaluation:

Identify and describe survey features:

1. Sample type
    * Stratified sampling - each province (10 total) were divided into strata or geographic areas. Many census metro areas were considered a separate strata (ie. Toronto)
2. Sample size
    * Target sample size: 20,000
    * Actual sample size: 16, 149 (excluding rejected respondents)
3. Target population
    * All persons 15 years of age and older in Canada, excluding: 
    * Residents of the Yukon, Northwest Territories, and Nunavut
    * Full-time residents of institutions
4. Sampling frame
    * Survey frame using 2 different components:
    1. lists of telephone numbers in use (both landline and cellular) available to Stats Can (telephone companies, census of population)
    2. The Address Registrar (AR): List of all dwellings within the 10 provinces
5. Survey mode(s)
    * telephone interviews
    * self-competed questionnaire
6. Timeline
    * 3 months (Sept - Dec, 2018)
7. Response rate
    * 41.9%
8. Weights
    1. Initial weight calculation
        * phone numbers belonging to same address were grouped together. However, some groups may not be correct (ie. grouped phone numbers do not belong to same address). Questions were then added to surveys in order to make adjustments to the initial probability of selection to account for the fact that some households have higher probability of being selected. 
        * initial weight is inverse of this adjusted probability of selection --> **Household weight**
    2. Removing out-of-scope telephone numbers (eg. business/not in service phone numbers)
    3. Three-stage non-response adjustment
        * stage 1: adjustments for complete non-response
        * stage 2: adjustments made non-repsponse with additional information available to Stats Can outside of the questionnaire
        * stage 3: adjustments made for partial non-response with additional information available to Stats Can outside of the questionnaire
    4. Person weight calculation
        * a person weight was calculated for the respondent by multiplyng household weight by the # of persons 15 years of age or older
        * Initial household weight s Factor 1 x Number of eligible house members
    5. Adjustment of person weights for Rejective Sampling
        * multiply respondents who didn't respond and were not volunteers by a factor
        * (sum of weights for non-volunteer respondents in each stratum - age group)/(sum of weights for non-volunteer respondents not 'rejected' in each stratum - age group)
    6. Adjustment of person weights to external totals
        * adjusted for geographical stratum, age-sex groups by province, and income

9. Data processing
    * responses were entered directly into computers by either respondents themselves during self-completed electronic questionnaires, or by telephone intervieweres
    * same data capture system was used for both respondents and telephone intervieweres
    * data capture system allowed for codes, built in edits, and automatically followed flow of questionnaire
    * data output was encrypted and electronically transmitted to Ottawa
    * data was coded into existing categories if a match was possible, new categories, or "other-specify".
    * demographics (eg. occupation, industry, language, education, country of birth, religion) was coded using standard classification systems used by the General Social Survey and Statistics Canada's harmonized content program
10. Cleaning, imputation, etc
    * dropped any duplicate data records, non-responses, and out-of-scope records
    * missing or incorrect data were imputed
        * item non-responses were handled using "not stated" codes or imputed
        * partial non-response were handled like non-reponses 
11. Sources of error
    * sampling errors
        * we can try to estimate using either standard error or coefficient of variation
    * non-sampling errors (interviewers misunderstood, respondents make mistakes, answers incorrectly entered, or during processing of data)
        * non-response (item or partial non-response - not answering one or more questions) --> happened mostly because participants misinterpreted, did not want to, or forgot the requested information 
        * this was handled by imputing respondent's answers
12. Limitations, known biases, etc
    * Non-sampling errors like systemic errors could have contributed to bias: 
        * selection bias -> this study only captured those who picked up the phone calls or responded to the online survey
        * nonresponse -> complete non-response dropped from sample and partial non-response were imputed
13. Link to documentation and any additional sources used: https://abacus.library.ubc.ca/file.xhtml?persistentId=hdl:11272.1/AB2/GBFDYG/FF7L7T&version=1.0

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 29/06/2025`
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
