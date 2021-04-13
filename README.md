# Healthcare Analytics Assessment Exercise
**OVERVIEW**
The following files in .csv format represent information describing a group of patient accounts from a healthcare organization’s hospital inpatient setting.  This information, which includes information about patient accounts (also known as encounters or patient visits), diagnoses and charges for services, can be used to answer a variety of analytical questions about the state of a hospital’s patient population over a two year period.  This exercise provides an opportunity to both organize the data for analysis and formulate and answer specific questions about the patient population using that data.

**DATA DESCRIPTIONS**
Transactional data:  These files contain information describing patients’ journeys through a hospital.   Transaction data consists of identifiers, dates and codes that can be associated with descriptive reference data to add meaningful context.
+ Accounts: Each record provides a subset of descriptive information about an individual patient account. This includes a unique identifier for the account (Account ID), when the patient was admitted to the hospital (Admit Date), when they were discharged (Discharge Date), the diagnosis related group (MS-DRG) that was used to classify the patient’s condition and treatment, the facility where care was provided and the patient’s zip code.
+ Diagnoses: Each patient account is expected to have at least one diagnosis (Diagnosis Code). Most patients will have more than one. The Diagnosis Sequence indicates whether a diagnosis is “primary” (Diagnosis Sequence = 1) or “secondary” (any number greater than 1.)
+ Charges: Charges represent services that are billed for during a patient encounter. They provide details about what transpired during the encounter as well as the basis for the total amount charged  to the patient account.
Note: these datasets are related to each other by Account ID

Reference data: These files contain descriptive information that can be joined with coded data to add context to the transactional data that will aid in analysis.
+ MS-DRG: Contains the descriptive name of the diagnosis related group (MS-DRG) as well as quantitative data reflecting national averages for length of stay (LOS) and a resource utilization index called Relative DRG Weight that can be used to compare expected utilization among patients, providers and facilities with what actually happened.
+ MS-DRG Service Line: Includes a categorization of diagnosis related groups (MS-DRGs) by the type of service provided.
+ Providers: Associates provider identifiers with their names and specialties.
+ Diagnoses: Descriptive information for coded diagnoses along with the clinical groupings that the diagnoses belong to.
+ Charges: Descriptive information associated with types of charges.
+ Facilities: The facility names associated with facility codes

**ANALYSIS QUESTIONS**
1)	For accounts discharged during 2019, which were the most common primary diagnoses? Secondary diagnoses?
2)	Which diagnosis related groups (MS-DRGs) have the highest average charges per patient account?
3)	Which Attending Provider Service had the highest volume of accounts (encounters) during December 2018?
4)	What is the “average length of stay” (number of hospital days between admit date and discharge date, but not including discharge date) for each of the 4 facilities for each of the years for which account information are provided (2018 & 2019).
5)	Which MS-DRGs Service Lines had the largest different between the observed length of stay and the national average  provided in the MS-DRG reference file?

**EXTRA CREDIT**

Based on your observations and analysis of the data, come up with a few more questions and provide quantitative answers to those questions. 
