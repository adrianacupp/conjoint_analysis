# Exercise Adriana
The exercise is structured in three distinct parts:
1. Crosstab for segmentation understanding
2. Soft launch data check
3. Optional: Conjoint simulator

With this exercise, we are interested in better understanding your technical skills and do not intend to overwhelm you.
We understand that this case study may involve some areas where you might not have extensive prior experience. We’re primarily interested in seeing your approach, problem-solving skills, and how you think through unfamiliar tasks. Partial solutions are completely acceptable, and we encourage you to explain any steps you’d take if given more time or resources. We value sound methodology and a thoughtful approach.

Please treat this exercise and the data contained in it as **confidential**. Please do not put any part of this case study in public github repos or similar services. 

## Part 1: Create a crosstab for segmentation understanding
In part 1, we provide survey data and a datamap for a segmentation project.

Please create a **Excel workbook** that will help researchers better understand the segmentation contained in the data (variable `Segment`).
Your Excel output should show researchers at a glance what the key differentiators of the segments are and how segments relate to each other.

Of course you're free to analyze whatever you see fit (however, just invest a reasonable amount of time)

## Part 2: Run a soft launch datacheck
For this part, we provide a mock survey dataset, as well as a questionnaire and a brand list.
Write code (in Python or R) to check the correctness of the simulated data according to the specifications in the questionnaire. Please submit both your code and a brief summary of your checks.

We are looking for
- Clear and well-documented code.
- An approach that shows familiarity with data check tasks

### Part 3: Conjoint Simulator 
Draft a market simulator using Excel that generates preference shares based on the provided dataset and auxiliary data from the questionnaire. 
The simulator may take additional inputs from the questionnaire for calibration and/or filtering.
Please note that we have used slope coding for the price attribute.

Inputs:
- Word questionnaire. Please note that this is an excerpt only. 
  The questionnaire is appended with additional information on the conjoint 
  analysis. 
- CSV data file. The file contains data from the main survey, as well as 
  utilities from the conjoint.

Instructions:
- Familiarize yourself with the dataset provided in the CSV file + questionnaire.
- Develop an Excel-based simulator to calculate preference shares
    - Please prioritize functions, features and structure over design. We do not expect a client-ready interface.
    - Please document both the methodology as well as your process. 