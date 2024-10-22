# COMPAS

COMPAS is a risk assessment instrument developed by Northpointe Inc. Of the 22 scales it provides, the Recidivism risk and Violent Recidivism risk scales are the most widely used. Scores are calculated using criminal history, jail and prison time, demographics and COMPAS risk scores for defendants from Broward County from 2013 and 2014.

<b>Data Types:</b> Multivariate

<b>Default Task:</b> Classification

<b>Attribute Types:</b> Categorical, Integer, Real

<b>Format:</b> csv

<b>Number of Entries:</b> 60843

<b>Number of Attributes:</b> 28

<b>Year:</b> 2016

<b>Source:</b> [ProPublica Data Store](https://www.propublica.org/datastore/dataset/compas-recidivism-risk-score-data-and-analysis) - Extracted from Broward County Clerk’s Office, Broward County Sherrif's Office, Florida Department of Corrections (2013-2014).

## Attributes

- Person_ID
- AssessmentID
- Case_ID
- Agency_Text
- LastName
- FirstName
- MiddleName
- Sex_Code_Text
- Ethnic_Code_Text
- DateOfBirth
- ScaleSet_ID
- ScaleSet
- AssessmentReason
- Language
- LegalStatus
- CustodyStatus
- MaritalStatus
- Screening_Date
- RecSupervisionLevel
- RecSupervisionLevelText
- Scale_ID
- DisplayText
- RawScore
- DecileScore
- ScoreText
- AssessmentType
- IsCompleted
- IsDeleted

## Download link

[Download](https://github.com/propublica/compas-analysis/)

## Reference

Julia Angwin, Jeff Larson, Surya Mattu, and Lauren Kirchner. How we analyzed the compas recidivism algorithm. 2016. URL https://www.propublica.org/article/ how-we-analyzed-the-compas-recidivism-algorithm.

```
 {
 @misc{Angwin, Larson, Mattu:2013 ,
 author = "Angwin, J. and Larson, J. and Mattu, S. and Kirchner, L.",
 year = "2016",
 title = "How We Analyzed the COMPAS Recidivism Algorithm",
 url = "https://www.propublica.org/article/ how-we-analyzed-the-compas-recidivism-algorithm",
 }
 ```
