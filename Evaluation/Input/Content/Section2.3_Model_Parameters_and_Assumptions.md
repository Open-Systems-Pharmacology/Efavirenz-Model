### 2.3.1	Absorption

Absorption observed in clinical studies can be fully explained by passive absorption.

### 2.3.2	Distribution

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim®, observed clinical data was best described by choosing the partition coefficient calculation by `Schmitt` and cellular permeability calculation by `PK-Sim Standard`. 

### 2.3.3	Metabolism, Elimination and Induction

Efavirenz is metabolized by CYP2B6, CYP3A4, CYP3A5, CYP1A2 and CYP2A6. 

Induction of CYP3A4 ([Shou 2008](#5-References)) and CYP2B6 ([Ke 2016](#5-References)) was taken into account.

### 2.3.4	Automated Parameter Identification

The parameter identification tool in PK-Sim® has been used to estimate selected model parameters. For some of the parameters, factors were optimized to maintain their absolute value, e.g. a global factor for the k<sub>cat</sub> values of CYP2B6, CYP3A4, CYP3A5, CYP1A2 and CYP2A6 was optimized (rather than the absolute k<sub>cat</sub> values) to keep the ratio between the different k<sub>cat</sub> values constant.

The result of the final parameter identification is shown in the table below:

| Model Parameter            | Optimized Value | Unit |
| -------------------------- | --------------- | ---- |
| `Lipophilicity` | 3.437       |        |
| `Specific intestinal permeability` | 2.972E-5    | cm/min |
| `Solubility at Ref-pH` | 39.922   | mg/l |
| `Fraction Unbound` | 5.955E-3 |  |
| `kcat` (CYP2B6) | 1.601 (factor: 0.31833 of literature reference) | 1/min |
| `kcat` (CYP3A4) | 0.051 (factor: 0.31833 of literature reference) | 1/min |
| `kcat` (CYP3A5) | 0.191 (factor: 0.31833 of literature reference) | 1/min |
| `kcat` (CYP1A2) | 0.191 (factor: 0.31833 of literature reference) | 1/min |
| `kcat` (CYP2A6) | 0.318 (factor: 0.31833 of literature reference) | 1/min |
| `EC50` (CYP3A4) | 0.071 (factor: 0.009711of literature reference) | µmol/l |
| `EC50` (CYP2B6) | 0.012 (factor: 0.009711of literature reference) | µmol/l |
| `Dissolution time (50% dissolved)` | 60 | min  |
| `Dissolution shape` | 0.272 |   |

