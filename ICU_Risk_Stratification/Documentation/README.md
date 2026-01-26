# ADS1002_Project

## DATASET: ICU

### TOPIC QUESTION: "When an illness isn’t alone: How can we improve insurance risk-pricing strategies through comorbidity-informed ICU survival prediction?”

### Group Members:
1. Anusha, 35216603, A-Singha
2. Joyceline, 35237635, LeeJoy06
3. Alvin, 35363304, JingYung047
4. Jingfeng, 35598352, jf666-coder

### Sub-Questions:
##### **JOYCELINE:**
1. "Why should we model ICU mortality and what is its relevance for insurance?"
##### Variables used: 
- `In.hospital_death`
- `Age`
- `Gender`
- `ICUType2`
- `ICUType3`
- `ICUType4`
- `SAPS.I`
- `SOFA`



##### **JINGFENG:**
2. "How does high blood pressure affect ICU survival risk?"
##### Variables used: 
- `SysABP` (Min, Mean, Max)
- `DiasABP` (Min, Mean, Max)
- `MAP` (Min, Mean, Max)
- `MechVent`
- `In.hospital_death`
- `Age`
- `Gender`
- `Height`
- `SAPS.I`
- `SOFA`



##### **ALVIN:**
3. "What is the predictive strength of kidney function markers in ICU mortality?"
##### Variables used: 
- `Creatinine` (Min, Mean, Max)
- `BUN` (Min, Mean, Max)
- `Urine` (Min, Mean, Max)
- `Lactate` (Min, Mean, Max)
- `In.hospital_death`
- `Age`
- `Gender`
- `SOFA` 



##### **ANUSHA:**
4. "How can our comorbidity-informed predictions be used for insurance risk stratification?"
##### Variables used: 
- `Predicted mortality probabilities from Sub-Questions 2 to 4`
- `In.hospital_death`
- `Age`
- `Gender`
- `Height`
- `ICUType2`
- `ICUType3`
- `ICUType4`
- `SAPS.I`
- `SOFA`
