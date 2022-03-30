## Given the blood test results of a patient, <br> can we set an accurate machine learning model <br> for hepatic illness diagnosis ? 

#### We have blood tests results from 615 patients
Based on the original Kaggle dataset : 
https://www.kaggle.com/fedesoriano/hepatitis-c-dataset



#### Content 

All attributes except Category and Sex are numerical.

##### Attributes 1 to 4 refer to the data of the patient:
1) X (Patient ID/No.)
2) Category (diagnosis) (values: '0=Blood Donor', '0s=suspect Blood Donor', '1=Hepatitis', '2=Fibrosis', '3=Cirrhosis')
3) Age (in years)
4) Sex (f,m)
Attributes 5 to 14 refer to laboratory data:
5) ALB = Albumin
6) ALP = Alkaline phosphatase
7) ALT = Alanine Transaminase
8) AST = Aspartate Transaminase
9) BIL = Bilirubin
10) CHE = Acetylcholinesterase
11) CHOL = Cholesterol
12) CREA = Creatinine 
13) GGT = Gamma-Glutamyl Transferase
14) PROT = Proteins

 ##### Target attributes for illness classification  :  
- Blood donors (hepaticly sane) 
- Hepatitis C 
- Fibrosis 
- Cirrhosis

