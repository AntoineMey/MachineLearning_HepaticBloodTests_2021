## Given the blood test results of a patient, <br> can we set an accurate machine learning model <br> for hepatic illness diagnosis ? 

#### Hepatic blood tests from 615 patients
Based on the original Kaggle dataset : 
https://www.kaggle.com/fedesoriano/hepatitis-c-dataset



#### Content 

All attributes except Category and Sex are numerical.

Attributes 1 to 4 refer to the data of the patient:
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

The target attributes for illness classification  : 
- Blood donors (hepaticly sane) 
- Hepatitis C 
- Fibrosis 
- Cirrhosis




#### Acknowledgements

Creators: Ralf Lichtinghagen, Frank Klawonn, Georg Hoffmann
Donor: Ralf Lichtinghagen: Institute of Clinical Chemistry; Medical University Hannover (MHH); Hannover, Germany; lichtinghagen.ralf '@' mh-hannover.de
Donor: Frank Klawonn; Helmholtz Centre for Infection Research; Braunschweig, Germany; frank.klawonn '@' helmholtz-hzi.de
Donor: Georg Hoffmann; Trillium GmbH; Grafrath, Germany; georg.hoffmann '@' trillium.de

#### Relevant Papers

Lichtinghagen R et al. J Hepatol 2013; 59: 236-42
Hoffmann G et al. Using machine learning techniques to generate laboratory diagnostic pathways â€“ a case study. J Lab Precis Med 2018; 3: 58-67
