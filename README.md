# First Project 
## Decision Tree and Random Forest

For this project I will be using the Dataset **SouthGermanCredit**, that can be obtained in the following link: https://archive.ics.uci.edu/ml/datasets/South+German+Credit 

The below list consists of a detailed breakdown of all the features in the Dataset. 'Kredit' is our target variable, the one whose value must be predicted.

1. Id = Id of individual entries, for evaluation

2. laufkont = status
  1: no checking account
  2: … < 0 DM 3 : 0<= … < 200 DM 4 : … >= 200 DM / salary for at least 1 year

3. laufzeit = duration

4. moral = credit_history
  0 : delay in paying off in the past
  1 : critical account/other credits elsewhere
  2 : no credits taken/all credits paid back duly
  3 : existing credits paid back duly till now
  4 : all credits at this bank paid back duly

5. verw = purpose
  0 : others
  1 : car (new)
  2 : car (used)
  3 : furniture/equipment
  4 : radio/television
  5 : domestic appliances
  6 : repairs
  7 : education
  8 : vacation
  9 : retraining
  10 : business

6. hoehe = amount

7. sparkont = savings
  1 : unknown/no savings account
  2 : … < 100 DM 3 : 100 <= … < 500 DM 4 : 500 <= … < 1000 DM 5 : … >= 1000 DM

8. beszeit = employment_duration
  1 : unemployed
  2 : < 1 yr 3 : 1 <= … < 4 yrs 4 : 4 <= … < 7 yrs 5 : >= 7 yrs

9. rate = installment_rate
  1 : >= 35
  2 : 25 <= … < 35
  3 : 20 <= … < 25
  4 : < 20

10. famges = personalstatussex
  1 : male : divorced/separated
  2 : female : non-single or male : single
  3 : male : married/widowed
  4 : female : single

11. buerge = other_debtors
  1 : none
  2 : co-applicant
  3 : guarantor

12. wohnzeit = present_residence
  1 : < 1 yr 2 : 1 <= … < 4 yrs 3 : 4 <= … < 7 yrs 4 : >= 7 yrs

13. verm = property
  1 : unknown / no property
  2 : car or other
  3 : building soc. savings agr./life insurance
  4 : real estate

14. alter = age

15. weitkred = otherinstallmentplans
  1 : bank
  2 : stores
  3 : none

16. wohn = housing
  1 : for free
  2 : rent
  3 : own

17. bishkred = number_credits
  1 : 1
  2 : 2-3
  3 : 4-5
  4 : >= 6

18. beruf = job
  1 : unemployed/unskilled - non-resident
  2 : unskilled - resident
  3 : skilled employee/official
  4 : manager/self-empl./highly qualif. employee

19. pers = people_liable
  1 : 3 or more
  2 : 0 to 2

20. telef = telephone
  1 : no
  2 : yes (under customer name)

21. gastarb = foreign_worker
  1 : yes
  2 : no

22. kredit (target column) = credit_risk
  0 : bad
  1 : good
