---
layout: page
title: Method 1
---


Data

What data sets are you using?

This project uses the 2023 RDS and PSD data.

What did you do to prepare the data?

To prepare the data, we created functions to clean the data and impute additional columns as needed. As part of this process, we also ensured the common columns in the RDS and PSD were standardized so they could be harmonized (e.g., had the same factor levels).

Tools (aka “component specification”)

What software packages, modules, etc. did you use?

We used R Studio and GitHub.

What are the dependencies between these and how did you render them interoperable?

Processes

What does your workflow or pipeline look like?

The fellows divided work among ourselves, assigning each person to create certain functions that targeted certain columns. Once the functions were created, all of them were called in a single script, which produced a series of cleaned dataframes for analyses: A clean RDS, a clean PSD, and a clean cominbed dataframe.

What steps did you follow?

Analyses

What approaches did you try that didn’t work? What analyses did you end up sticking with?

RDS

Limitations

What are the shortcomings of your approach? How can your work be improved?
