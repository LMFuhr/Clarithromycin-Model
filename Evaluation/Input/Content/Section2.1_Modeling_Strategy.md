The general concept of building a PBPK model has previously been described by Kuepfer et al. ([Kuepfer 2016](# 5 References)). Information regarding the relevant anthropometric (height, weight) and physiological parameters (e.g. blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in adults was gathered from the literature and has been previously published ([PK-Sim Ontogeny Database Version 7.3](# References)). The information was incorporated into PK-Sim® and was used as default values for the simulations in adults.

The  applied activity and variability of plasma proteins and active processes that are integrated into PK-Sim® are described in the publicly available PK-Sim® Ontogeny Database Version 7.3 ([Schlender 2016](# 5 References)) or otherwise referenced for the specific process.

A typical European individual was used for the development of the clarithromycin model. The relativ tissue specific expression of CYP3A4 was implemented in accordance with literature using the PK-Sim expression database RT-PCR profile. Enterohepatic cycling was enabled as it is active under physiological conditions. 

Unknown parameters (see below) were identified using the Parameter Identification module provided in PK-Sim®. 

The model was then verified by simulating:

- the whole reported dose range including single and multiple doses
- DDIs with CYP3A4 or P-gp substrates (shown elsewhere)

Details about input data (physicochemical, *in vitro* and clinical) can be found in  [Section 2.2](#2.2	Data).

Details about the structural model and its parameters can be found in  [Section 2.3](#2.3 Model Parameters and Assumptions).

