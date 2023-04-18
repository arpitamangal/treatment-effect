# Should the legal age for drinking be reduced from 21?
The code implements a regression discontinuity design (RDD) to answer the question.
* Determines if alcohol increases the chances of death by 
  - accident, 
  - suicide and/or 
  - others
* Concludes the trade-offs of choosing different bandwidths for the design. Bandwidth used: 
  - 1 year (i.e., 21 +- 1).
  - 6 months (i.e., 21 +-0.5).
  - maximum (i.e. entire data).
  
Inference: 
There is a correlation between deaths above and below the legal drinking age, but we cannot conclude that the age limit causes these deaths, as there may be other confounding factors unrelated to alcohol. If alcohol is indeed the cause, lowering the drinking age would not solve the problem and could lead to a similar issue with younger age groups. Before making any conclusions, we need to account for confounding factors, identify true treatment effects, and take informed decisions.

Dataset: "drinking.csv"
