# YTK-heterogeneity-flow
Raw flow data from Patel et al.,

This contains all the raw data from the flow cytometry of pYTK-sfGFP strains sampled at different growth phases and media conditions.

Each folder is for one replicate: 
- 311020... 
- 091120...
- 161220...

Within each folder, the runs for each sample point have been collated in a .csv file:
- x1 - YPD10 exponential phase
- x2 - YPD10 stationary phase
- y1 - YPD exponential phase
- y2 - YPD stationary phase
- m1 - YNB exponential phase
- m2 - YNB stationary phase
- g1 - YEPG exponential phase
- g2 - YEPG stationary phase

Within each .csv file, the first column contains the cell count (1-50000) followed by the log-transformed sfGFP intensity as measured on the Attune Nxt BL1-H channel. 

The following columns contain the log(sfGFP) data for the following pYTK promoters/controls:
C - pTDH3
E - pCCW12
G - pPGK1
I - pHHF2
K - pTEF1
M - pTEF2
O - pHHF1
Q - pHTB2
S - pRPL18B
U - pALD6
W - pPAB1
Y - pRET2
AA - pRNR1
AC - pSAC6
AE - pRNR2
AG - pPOP6
AI - pRAD27
AK - pPSP2
AM - pREV1
AO - BP (Control strain)
AQ - BP heat-killed control (propidium iodide dead stain control)(BL1-/YL2+)
AS - BP no dead stain control (BL1-/YL2-)
AU - pCCW12-sfGFP control (BL1+/YL2-)
