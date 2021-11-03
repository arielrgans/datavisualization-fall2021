# Assignment 4: Interviewing a Dataset

## Dataset

[CPS Aug 2021 Data](https://github.com/juliashapero/datavisualization-fall2021/blob/main/CPS%20Aug%202021%20Data%20Cleaned%20FINAL.csv)

## Cleaning Dataset (alongside group members)

* Removed rows that did not have 201 under HUFINAL (201s were completed interviews)
* Deleted last two rows that were missing data
* Deleted 334 columns that were not relevant to information we're looking for

## Questions about Dataset

1. How hourly/non-hourly job status differ by age? 
2. How does employment status differ by citizenship status?
3. How does family income differ by hours worked?

## Analyzing Dataset

### Question 1

* Made a pivot table with the dataset
* Used peernhry (hourly/non-hourly) in the rows section
* Used prtage (person’s age) in the values section
* Looked at average of prtage by hourly/non-hourly status

### Question 2
* Made a pivot table with the dataset
* Used prcitship (citizenship status) in the rows section
* Used pemlr (employed/not) in the values section
* Looked at count of pemlr by citizenship status

### Question 3
* Made a pivot table with the dataset
* Used hefaminc (family income) in the rows section
* Used prhrusl (hours worked) in the values section
* Looked at average of prhrusl by family income

## Answers to Questions

1. In this study, the average age of an hourly worker was less than that of a non-hourly worker. The average age of hourly workers was 40.3 years, and the average age of non-hourly workers was 44.5 years.

2. In this study, 45,549 non-citizens were employed, while 2,293 non-citizens were unemployed.

3. According to this study, on average those who work the most hours (50 hours or more) per week have higher annual incomes ($150,000 or more) than those who work fewer than 50 hours per week.

## Sample Headline and Nut Graf

HED: Study finds that those who work more, make more

Nut Graf: A 2021 census study of over 97,000 American residents found that those who work 50 hours or more per week have higher annual incomes on average than those who work fewer than 50 hours per week. More specifically, those working the longest hours were most likely to have incomes of $150,000 per year or more. This implies that, for many, the American dream may be a reality.
