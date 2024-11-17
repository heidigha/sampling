# Assignment: Data Documentation Comparison Worksheet

For each of the three sources listed, find any and all available documentation for the data gathered and identify and describe the survey features indicated in the table below. Some may not be available for all sources.

Sources: - Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33), conducted by Statistics Canada - Canadian Election Study Online Survey, 2019, conducted by Laura Stephenson, Allison Harell, Daniel Rubenson and Peter Loewen - Trophic niche flexibility in Glossophaga soricina: how nectar seeker sneaks an insect snack, conducted by Elizabeth Clare et al.

|                                                       | Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33) | Canadian Election Study Online Survey, 2019 | Trophic niche flexibility in Glossophaga soricina: how nectar seeker sneaks an insect snack |
|----------------|:--------------------|----------------|---------------------|
| Sample type                                           |    Stratified sampling , random sampling and reject sampling                                                                                      |Stratified sampling and Quota sampling |                                                                                             |
| Sample size                                           |    Target sample size: 20,000 respondents; Total usable responses before rejections: 19,857; Actual achieved sample size: 16,149 respondents |Campaign Period Survey: Total completed responses: 37,822 (high quality: 33,905 slightl lower quality:3917  Post-Election Survey: Total completed responses: 10,340 (high quality: 8,313/ slightly lower quality: 2,027 )|
| Target population                                     |    Canadian citizens aged 15 and older in Canada's 10 provinces excluding ukon, Northwest Territories and Nunavut. | Age: 18 or older; Canadian citizens or permenant residents; Location: must reside in Canada; |                                                                                             |
| Sampling frame                                        |    Lists of telephone numbers in use (both landline and cellular) available to Statistics Canada from various sources (Telephone companies, Census of population, etc.) The Address Register (AR): List of all dwellings within the ten provinces.   | members of various online panels managed by Qualtrics|                                                                                             |
| Survey mode(s)                                        |    1. Electronic Questionnaire (rEQ) 2. Computer Assisted Telephone Interviews | Online Survey|                                                                                             |
| Timeline                                              |    Start date: September 4, 2018; End date: December 28, 2018  | Campaign Period Survey -Start date: September 13, 2019; End date: October 21, 2019 (closed at 9:00am); Post-Election Survey-Start date: October 24, 2019; End date: November 11, 2019  |                                                                                             |
| Response rate                                         |    41.9 %                                                                                        | Campaign Period: 45.48% ; Post-Election: Less than 50%                                            |                                                                                             |
| Weights                                               |    500 bootstrap weights (wtbs_001 to wtbs_500)  provided for variance estimation | Weights were created using an iterative "raking" process and the documentation emphasizes that these weights should be used to ensure the data is representative of the Canadian population. |                                                                                             |
| Data processing                                       |    1. Data Capture 2. Coding 3. Edit & Imputation 4. Creation of Derived Variables 5. Additional PUMF Processing 6. Quality Assurance  |1.Data Quality Checks & Removal 2.Data Quality Categories Retained in Dataset 3.Duplicate Response Identification 4. Variable Naming|                                                                                             |
| Cleaning, imputation, etc.                            |    -Main Method - Donor Imputation       -Mean imputation among a pool of donors was used where donor imputation couldn't be applied | 1. Response Removal by Criteria (e.g. Duplicates, Incomplete responses) 2.Duplicate Identification  3. Data Quality Flags; No mention of imputation procedures |                                                                                             |
| Sources of error                                      |   1. Non-response Errors 2.Data Collection Errors 3. Processing Errors 4. Sampling Errors | 1. Sampling(e.g.No random selection procedures) ; 2. Coverage (e.g. Panel composition may not match population)  3. Processing Error; 4. Technical Issues |                                                                                             |
| Limitations, known biases                             |   1. First time offering Internet option in 2018 (Not appropriate to compare 2018 results with previous iterations due to mode changes) 2. The exclusion of residents in Yukon, NW Territories & Nunavut; households without telephone; Full-time residents of institutions 3.Overall response rate was 41.9% (lower than previous years) Biases: Non-respondents more likely to be: Males and yonger people. |1. Online Panel Limitations 2. Geographic Coverage (Territories not included ) 3. Return Rate Issues (< 50%) 4. Online-only survey 5. Limited campaign period coverage 6. Selection Bias (Online panel recruitment) 7. Excludsion of non-internet users 8.Panel Bias |
| Citation                                              | 2018 General Social Survey Cycle 33: Giving, Volunteering and Participating  |2019 Canadian Election Study (CES) - Online Survey | Clare, E. L., Goerlitz, H. R., Drapeau, V. A., Holderied, M. W., Adams, A. M., Nagel, J., Dumont, E. R., Hebert, P. D. N., & Fenton, M. B. (2014). Trophic niche flexibility in Glossophaga soricina: How a nectar seeker sneaks an insect snack. Functional Ecology, 28(3), 632-641. doi: 10.1111/1365-2435.12192|
| Links to any documentation or additional sources used |https://www150.statcan.gc.ca/n1/pub/45-25-0001/index-eng.htm#a5 | https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DUS88V|   |https://www.researchgate.net/profile/Holger-Goerlitz/publication/240024344_Trophic_niche_flexibility_in_Glossophaga_soricina_How_a_nectar_seeker_sneaks_an_insect_snack/links/5cac4398299bf118c4bd0e31/Trophic-niche-flexibility-in-Glossophaga-soricina-How-a-nectar-seeker-sneaks-an-insect-snack.pdf?origin=publication_detail&_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InB1YmxpY2F0aW9uRG93bmxvYWQiLCJwcmV2aW91c1BhZ2UiOiJwdWJsaWNhdGlvbiJ9fQ

## Criteria

|Criteria|Complete|Incomplete|
|--------|----|----|
|Population of the data table|The table has been correctly populated from the sources.|The table has been populated, but the information provided is incorrect.|

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `data-documentation`
* What to submit for this assignment:
     * This markdown file (data_documentation_comparison_worksheet.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
     * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist: 
- [ ] Create a branch called `data-documentation`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
