# **Test Plan and Output**
## High-Level Requriements
<html>
<body>
<!--StartFragment-->

Test ID | HLR | Description | Inputs | Expected O/P | Actual O/P
-- | -- | -- | -- | -- | --
TD01 | HLR01 | Calculating Rural areas electricity bill | Choice | Sucess | Sucess
TD02 | HLR02 | Calculating Urban areas electricity bill | Choice | Sucess | Sucess
TD03 | HLR03 | Calculating total amount at Domestics places | Choice | Sucess | Sucess
TD04 | HLR04 | Calculates total unit consumed at Domestics places | Choice | Sucess | Sucess

<!--EndFragment-->
</body>
</html>

## Low-Level Requriements
<html>
<body>
<!--StartFragment-->

Test ID | LLR | Description | Inputs(Units) | Expected O/P (Amount) | Actual O/P (Amount)
-- | -- | -- | -- | -- | --
TD01 | LLR01_HLR01 | Electricity bill calculation at Rural areas if(units<30) | 25 | 78.75 | 78.75
TD02 | LLR02_HLR01 | Electricity bill calculation at Rural areas if(units>30 && units <100) | 45 | 198.0 | 198.0
TD03 | LLR03_HLR01 | Electricity bill calculation at Rural areas if(units>101 && units <200) | 112 | 666.4 | 666.4
TD04 | LLR04_HLR01 | Electricity bill calculation at Rural areas if(units<200) | 235 | 1598.0 | 1598.0
TD05 | LLR05_HLR02 | Electricity bill calculation at Urban areas if(units<30) | 15 | 48.75 | 48.75
TD06 | LLR06_HLR02 | Electricity bill calculation at Urban areas if(units>30 && units <100) | 55 | 258.5 | 258.5
TD07 | LLR07_HLR02 | Electricity bill calculation at Urban areas if(units>101 && units <200) | 101 | 631.25 | 631.25
TD08 | LLR08_HLR02 | Electricity bill calculation at Urban areas if(units<200) | 201 | 1467.3 | 1467.3

<!--EndFragment-->
</body>
</html>