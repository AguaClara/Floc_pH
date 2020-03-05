#### Justin Lee, Jena Rozanski, Rafaella Bruzual
 #### Oct 4, 2019


## Abstract

The performance of the AguaClara flocculator, floc blanket, and sed system most likely depends on three distinct factors: pH, floc blanket depth, and coagulant dosage. However, the performance is difficult to measure when the coagulant dosage is high because the coagulant will coat the pH probe, thereby leading to inaccuracies. Our goal is to measure the steady state performance of these systems as we vary the pH and keep the coagulant dosage constant.  The flocculator and tube settler used within our experiment was nearly identical to the ones used in the experiments varying coagulant dosage, and floculator depth, making pH the only variable within our system. ProCoDa and Python were used to develop stock solutions of acid or base that would allow us to reach target tap water pHs. A peristaltic pump automated the addition of stock solutions of acid and  to maintain these target pH levels. 

## Introduction

To test the performance of a flocculator system with respect to varying pH, it is important to note that four pumps are needed for each of the following: the tap water, the water with pH adjustments, the water with coagulant, and the clay mixture (the impurity being filtered). Upflow velocity of 1 milimeter per second should be implemented in the design as well as 100 NTU of clay. The flocculator used must have a Gt of 37,000 and approximately a 50 cm headloss.
Understanding how the three factors affect the systems simulataneously requires us to first understand how each factor indiviudally affects these systems. We used a coagulant dosage that will give a settled water turbidity of less than 3 NTU when using tap water that has not been pH adjusted. To test the performance of a flocculator system with respect to varying pH, it is important to note that four pumps are needed for each of the following: the tap water, the water with pH adjustments, the water with coagulant, and the clay mixture (the impurity being filtered). Upflow velocity of 1 milimeter per second should be implemented in the design as well as 100 NTU of clay. The flocculator used must have a Gt of 37,000 and approximately a 50 cm headloss. The tube settler that we are using will be of this shape.

![Tube Settler](https://raw.githubusercontent.com/AguaClara/high_rate_sedimentation/master/Images/Setup/Sedimentation%20Tank%20A.png) **Figure 1:** Tube Settler used within experiments 

Our system deals with a carbonate system and requires more mathematical rigor than creating stock solutions with the target pH. To account for the carbonate system, we first determined the Acid Neutralizing Capacity of tap water using ProCoda and developing and analyzing Gran Plots. After receiving a low error (less than 0.1 mL of titrant), we use this data and plug them within equations in a Python script and determined the amount of acid or base needed to adjust the pH to our target pHs: 5,6,7,8. We then developed stock solutions with concentrations that would allow our pump to deliver the required flows to cover the target pH range. The steady state performance of the system at each pH was measured and extra data points would be considered to provide a more information on pH vs performance. The data was then plotted and analyzed hoping to lead to a relationship between pH and performance and a possible performance maximization point. Observations about floc formation and floc blanket formation were recorded at different pHs in hopes of discovering some interesting behavior.

## Previous Work

Not sure what previous work there is?

## Literature Review
In the "Analysis and optimization of coagulation and flocculation process" , optimal pH conditions were determined to be around 6, 7 and 8.

## References
Lee, M., Benitez,L. (2019, April). Spring 2019 Reports. Retrieved from:
https://github.com/AguaClara/HRS-Bot-Geo/blob/master/2019%20Spring/Reports/HRSBotGeo2FinalReportDraft.md

V. Saritha, N. Srinivas, N. V. Srikanth Vuppala. (2014, May). Analysis and optimization of coagulation and flocculation process. 