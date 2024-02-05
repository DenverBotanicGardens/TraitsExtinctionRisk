# Plant matrix population models and simulations
---

Plant matrix population models were used to simulate asymptotic growth, demographic and environmental stochasticity. 
## Description of the data and file structure
In the Rdata folder:
“plants_data” contains plant matrix population models and associated information gathered from the COMPADRE Plant Matrix Database v6.22.5.0. 

“Exist_” refers to populations projected from stable stage distribution while “Novel_” refers to populations projected from either the seed or seedling stage. “Asymptotic”, “demostoch”, “environ”, and “environ-demo” refer to the treatment of each simulation. 

R code:
"2023_PhylogenyCovarianceMatrix.Rmd" explores the phylogentic relationships of the species within the dataset.

"COMPADRE_matrixdata.Rmd" pulls and subsets plant matrix population models from https://compadre-db.org/.

"NovelExist_ParityShape" has the JAGS code for the log-odds of extinction. 

"_treatments.Rmd" are code to run the 100 year projections for both population histories (existing, novel) and treatments (control = asymptotic, demographic stochasticity, environmental stochasticity, demographic and environmental stochasticity). These pull matrices from "plants_data.Rdata"

## Sharing/Access information

Links to other publicly accessible locations of the data:
  * https://github.com/DenverBotanicGardens/TraitsExtinctionRisk
  * dryad (https://doi.org/10.5061/dryad.2547d7wzv)

Data was derived from the following sources:
  * COMPADRE Plant Matrix Database v6.22.5.0


## Code/Software

Scripts in the github repository are written in R4.2.2 and require JAGS (https://sourceforge.net/projects/mcmc-jags/).
