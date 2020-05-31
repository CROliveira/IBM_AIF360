# NuEnergy
Credit Default Risk Prediction using German dataset

Description of the German credit dataset.

1. Source Information:
Professor Dr. Hans Hofmann  
Institut f"ur Statistik und "Okonometrie  
Universit"at Hamburg  
FB Wirtschaftswissenschaften  
Von-Melle-Park 5    
2000 Hamburg 13 


2. Encoded Attribute description as follows:

Financial: Status of existing checking account
1:      ... <    0 DM 

2: 0 <= ... <  200 DM
3:      ... >= 200 DM /salary assignments for at least 1 year
0: no checking account 

Duration: Credit history in months
3: no credits taken/ all credits paid back duly
2: existing credits paid back duly till now
1: delay in paying off in the past
0: critical account/ other credits existing (not at this bank)

Purpose: Of the credit
1: car (new)
2: car (used)
3: furniture/equipment
4: radio/television
5: domestic appliances
6: repairs
7: education
8: (vacation - does not exist?)
9: retraining
10: business
11: others

Amount: Requested credit amount

Bonds: Or savings account
1:          ... <  100 DM
2:   100 <= ... <  500 DM
3:   500 <= ... < 1000 DM
4:          .. >= 1000 DM
0:   unknown/ no savings account

Employment: Present employment since
0: unemployed
1:       ... < 1 year
2: 1  <= ... < 4 years  
3: 4  <= ... < 7 years
4:       .. >= 7 years

Installments: Installment rate in percentage of disposable income


Gender: Sex on birth
0: Female
1: Male

Civil: Civil Status
3: divorced/separated
2: married/widowed
1: single

Guarantor: Other debtors / guarantors
0: co-applicant
1: none
2: guarantor

Residence = Present residence since

Property: 
3: real estate
2: building society savings agreement/life insurance
1: car or other, not previously mentioned
0: unknown / no property

Age: Age in years

Installments2: Other installment plans 
1: bank
2: stores
0: none

Housing: Housing owning condition 
1: rent
2: own
0: for free

Products: Number of existing credits at this bank

Job: Type of work/position
0: unemployed/ unskilled
1: skilled employee / official
2: management/ self-employed/highly qualified employee/ officer

Resident:
0: Non-resident
1: Resident

Liabler: Number of people being liable to provide maintenance for

Telephone: Telephone under his/her own name
0: none
1: yes, registered under the customers name

Foreign: foreign worker
0: yes 
1: no


Default: According to cost matrix that follows
1: No
2: Yes

Cost Matrix
This dataset requires use of a cost matrix (see below)
      1        2
----------------------------
  1   0        1
-----------------------
  2   5        0

(1 = Good,  2 = Bad)


It is worse to class a customer as good when they are bad (5), 
than it is to class a customer as bad when they are good (1).



