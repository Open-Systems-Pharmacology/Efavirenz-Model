### 2.3.1 Absorption

Absorption observed in clinical studies can be fully explained by passive absorption.

### 2.3.2 Distribution

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim, observed clinical data was best described by choosing the partition coefficient calculation by `Schmitt` and cellular permeability calculation by `PK-Sim Standard`. 

### 2.3.3 Metabolism, Elimination and Induction

Efavirenz is metabolized by CYP2B6, CYP3A4, CYP3A5, CYP1A2 and CYP2A6. Km values were taken from literature and corrected for unspecific binding of efavirenz in microsomal preparations (fu, incubation). If no fu, incubation was reported for the in vitro assay, it was calculated according to [Austin 2002](#5-References), using logP and microsomal protein concentration (Cmic). If no microsomal protein concentration was reported for the in vitro assay, a low protein concentration of 0.25 mg/ml was assumed.

Corresponding kcat values were optimized using the parameter identification tool of PK-Sim. 

Induction of CYP3A4  ([Shou 2008](#5-References)) and CYP2B6 ([Ke 2016](#5-References)) was taken into account. EC50 values were also taken from literature and corrected for fu, incubation, while corresponding Emax values were optimized. The CYP3A4 Emax values was optimized using efavirenz-midazolam DDI studies.



