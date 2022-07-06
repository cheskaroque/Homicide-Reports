# Homicide-Reports
The data was compiled and made available by the Murder Accountability Project, founded by Thomas Hargrove. According to the organization, the data "includes murders from the FBI’s Supplementary Homicide Report from 1976 to the present and Freedom of Information Act data on more than 22,000 homicides that were not reported to the Justice Department. This dataset includes the age, race, sex, ethnicity of victims and perpetrators, in addition to the relationship between the victim and perpetrator and weapon used.”

## Dataset
For this notebook we will be working on a dataset called homicidesreport. This dataset contains information on murders from the FBI's Supplementary Homicide Report from 1976 to the present and Freedom of Information Act data on more than 22,000 homicides that were not reported to the Justice Department.

## Dataset Structure

The dataset contains 638,454 observations (rows) which each represent a homicide report across 24 variables (columns). The following are the descriptions of each variable in the dataset.

- recordid: record id number (numeric: 1 - 638454)

- agencycode: (a six-digit alphanumeric code used to classify accounts by the federal or non-federal agency) 

- agencyname: name of agency
- agencytype: type of agency 

- city: city where the homicide incident occured 
- state: state where the homicide incident occurred 
- year: year of the given report, ranging from 1980-2014
- month: month of the given report
- incident: how many incidences occured in the report
- crimetype:  (Murder or Mansloughter or Mansloughter by negligence)
- crimesolved: indicates if crime was solved (yes or no)
- victimsex: gender of victim
- victimage: age of victim
- victimerace:  (Native American/Alaska Native, White, Black, Unknown, Asian/Pacific Islander)
- victimethnicity:  (Unknown, Not Hispanic, Hispanic)
- perpetratorsex: gender of perpetrator
- perpetratorage: age of perpetrator
- perpetratorrace:  (Native American/Alaska Native, White, Black, Unknown, Asian/Pacific Islander)
- perpetratorethnicity: (Unknown, Not Hispanic, Hispanic)
- relationship:  (Victim of a crime i.e. Son)
- weapon: weapon used to commit the homicide 
- victimcount: count of victims in the report
- perpetratorcount: count of perpetrators in the report
- recordsource: source of the record
