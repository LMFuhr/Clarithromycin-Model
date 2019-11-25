### 2.3.1	Absorption

The specific intestinal permeability was optimized during parameter identification to accurately describe the absorption of clarithromycin after oral administration.

### 2.3.2	Distribution

Values for logP and fu were fixed according to literature values. 

For clarithromycin, it was not possible to adequately describe the concentration-time profile after intravenous administration using standard input parameters (e.g., logP) and calculation methods (e.g., partition coefficients). Simulated concentration-time profiles over-predicted Cmax and under-predicted the observed data for time > Tmax. According to literature, clarithromycin accumulates in mononuclear (MN) and polymorphonuclear (PMN) leukocytes, probably via active transport ([Ishiguro 1989](#5 References)). This process was implemented, and it improved the model significantly. Due to limited knowledge on this transport (unknown transporter, unknown Vmax, and KM value), an adjustment of the clarithromycin permeability between plasma and RBC compartments was applied. The clarithromycin permeability optimization (Pplasma→RBC, PRBC→plasma) led to an asymmetric permeability ratio Pplasma→RBC/PRBC→plasma of 13, indicating that clarithromycin can more easily enter than exit the RBC compartments.

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim, observed clinical data was best described by choosing the partition coefficient calculation by `Rodgers and Rowland` and cellular permeability calculation by `PK-Sim Standard`. 

### 2.3.3	Metabolism and Elimination

The final model applies partitioning into blood cells, metabolism by CYP3A4 including mechanism-based auto-inactivation and a renal clearance. 

Metabolism was described using Michaelis Menten kinetics, while the Michaelis-Menten constant Km was taken from in-vitro experiments from literature and the turnover rate kcat was optimized during parameter identification. 

Ki and kinact to describe the mechanism-based inhibition of CYP3A4 were optimized during parameter identification.

A kidney plasma clearance was implemented to describe the renal elimination of clarithromycin. The specific renal clearance CLren was optimized during parameter identification.



### 2.3.4	Automated Parameter Identification

This is the result of the final parameter identification.

| Model Parameter      | Optimized Value | Unit |
| -------------------- | --------------- | ---- |
| `PK-Sim parameter 1` |                 |      |
| `PK-Sim parameter 2` |                 |      |
| `PK-Sim parameter 3` |                 |      |
| `PK-Sim parameter 4` |                 |      |

