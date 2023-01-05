
**1  Introduction**

Term deposit is always a key business of a bank and a good marketing campaign plays an important role in financial selling. Nowadays, the telephone marketing, which can assist consulting institution to extract potential clients, has been one of the most general marketing campaigns. The objective of this project is to predict the result of phone calls to long term deposits. The results will be valuable to assist managers in prioritizing and selecting the next customers to be contacted during the term deposit campaigns.

**2  Machine learning problem**

The classification approach to predict which clients are more likely to subscribe for the term deposits.

**3  Dataset information**

Dataset is collected from UCI Machine learning Repository.

Link: https://archive.ics.uci.edu/ml/datasets/bank+marketing#

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. The classification goal is to predict whether the client will subscribe (1/0) to a term deposit (variable y).

The dataset provides the customers' information of the bank from May 2008 to November 2010. It includes 41,188 records and 21 fields.

**3.1  Input variables**

Bank client data

1 - age (numeric)

2 - job : type of job (categorical: 'admin.','blue- collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')

3 - marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)

4 - education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')

5 - default: has credit in default? (categorical: 'no','yes','unknown')

6 - housing: has housing loan? (categorical: 'no','yes','unknown')

7 - loan: has personal loan? (categorical: 'no','yes','unknown')

related with the last contact of the current campaign 8 - contact: contact communication type (categorical: 'cellular','telephone')

9 - month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')

10 - day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')

11 - duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

other attributes

12 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

13 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

14 - previous: number of contacts performed before this campaign and for this client (numeric)

15 - poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')

social and economic context attributes

16 - emp.var.rate: employment variation rate - quarterly indicator (numeric) - Cylical employment variation is essentially the variation of how many people are being hired or fired due to the shifts in the conditions of the economy (Formula: ((number of employees in this quarter - number of employees in previous quarter)/average employees in the time period))

17 - cons.price.idx: consumer price index - monthly indicator (numeric) - A Consumer Price Index measures changes in the price level of a weighted average market basket of consumer goods and services purchased by households.The CPI for the current year is either more or less than 100, with the former indicating an increase in the prices of the goods and services and the latter signifying the decrease in the costs over a period.

18 - cons.conf.idx: consumer confidence index - monthly indicator (numeric) - Consumer confidence index provides an indication of future developments of households' consumption and saving, based upon answers regarding their expected financial situation, their sentiment about the general economic situation, unemployment and capability of savings.

19 - euribor3m: euribor 3 month rate - daily indicator (numeric) - The 3 month Euribor interest rate is the interest rate at which a panel of banks lend money to one another with a maturity of 3 months.

20 - nr.employed: number of employees - quarterly indicator (numeric)

**3.2  Output variable (desired target)**

21 - y - has the client subscribed a term deposit? (binary: 'yes','no')

