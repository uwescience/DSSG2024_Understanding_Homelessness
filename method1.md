---
layout: page
title: DSSG
---

# Summary Methods - Data Collection and Analysis

## Data

### What data sets are you using?

We are using the 2023 RDS (Respondent-Driven Sampling) and PSD (Point-in-Time Survey) datasets.

### What did you do to prepare the data?

We prepared the data by:
- Creating functions to clean the data and impute additional columns where needed.
- Standardizing common columns in both RDS and PSD datasets to harmonize them, ensuring consistent factor levels and data formats.

## Tools (Component Specification)

### What software packages, modules, etc., did you use?

We used:
- **R Studio** for data analysis.
- **GitHub** for version control and collaboration.

### What are the dependencies between these and how did you render them interoperable?

- **R Studio**: Provides the environment for writing and executing R code.
- **GitHub**: Manages version control and collaboration.
- **Interoperability**: R Studio integrates with GitHub for version control through the RStudio IDE, allowing seamless collaboration and tracking of changes in scripts and data processing functions.

## Processes

### What does your workflow or pipeline look like?

The workflow was divided into several steps:
1. **Function Creation**: Fellows created functions to target specific columns and tasks in the data.
2. **Function Integration**: All created functions were consolidated into a single script.
3. **Data Cleaning**: The script produced cleaned dataframes, including:
   - A clean RDS dataset
   - A clean PSD dataset
   - A clean combined dataframe for integrated analysis.

### What steps did you follow?

- Created and tested individual functions for data cleaning and imputation.
- Standardized columns across datasets for harmonization.
- Combined the functions into a unified script.
- Ran the script to generate cleaned dataframes for subsequent analyses.

## Analyses

### What approaches did you try that didn’t work? What analyses did you end up sticking with?

- **Successful Approaches**: The final approach involved using standardized functions to clean and harmonize data, resulting in reliable datasets for analysis. We then apply the RDS-II estimators and bootstrap methods for robust statistical analysis.

## Limitations

### What are the shortcomings of your approach? How can your work be improved?

- **Shortcomings**:
  - **Column Standardization**: Despite efforts, discrepancies might still exist if initial datasets had inconsistencies or errors.
  - **Dependency on Tools**: Reliance on R Studio and GitHub requires users to be proficient with these tools; any issues with tool integration or updates could impact the workflow.

- **Improvements**:
  - **Ongoing Harmonization**: Continuously review and update column standardization procedures to address any emerging inconsistencies.
  - **Tool Flexibility**: Consider incorporating additional tools or methods to improve interoperability and address any potential limitations of the primary tools used.
 
## Survey Design and Sampling

### Survey Design

The survey was designed to capture comprehensive data on the unsheltered population using the following methodology:

- **Hub Locations:** Established up to twelve hub locations, including public libraries and veterans shelters, to facilitate survey participation.
- **Seed Participants:** Recruited around twenty initial seed participants who distributed coupons to their peers.
- **Coupon Distribution:** Participants were given coupons to refer others, with incentives including cash cards and Metro bus tickets. Referring participants received credit for each completed referral.
- **Data Collection:** Conducted at hub locations with the assistance of trained students and volunteers, using tablets and the UW Qualtrics data entry form.

### Sampling Methodology

The sampling methodology employed includes:

- **Respondent-Driven Sampling (RDS):** Utilized for individuals without addresses, with a focus on network-based sampling.
- **Household Survey:** Randomized sampling approach for individuals with addresses.

**Survey Phases:**

1. **Initial Screener:** Approximately 5 minutes, interviewer-administered, with a $20 gift card and two Metro bus tickets.
2. **Individual Interview:** About 30 minutes, self-administered via tablet, with an additional $10 gift card as incentive.

### Eligibility Criteria

Participants were selected based on the following criteria:

- **Age:** 18 years or older.
- **Consent:** Capability of providing informed consent.
- **Housing Status:** Identified as unsheltered, as per HUD definitions.

Interviews were conducted in English and Spanish, with real-time translation available for other languages.
