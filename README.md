# language-development-among-ecuadorian-children
Assessed the association between home environment and language development among children aged 1-3 years using the Ecuadorian National Health and Survey data, ENSANUT 2018

## Introduction

#### Language development is one of the core skills that help in the assessement of developmental trajectories among young children. While individual variation in trends are common,external factors such as physical environment, and parental behaviours and engagement with the child can higly affect the overall developmental process.


#### In-survey tools used:
* [HOME inventory](https://uwm.edu/mcwp/wp-content/uploads/sites/337/2015/12/HOME12-1-14.pdf)
* [Shortform MacArthur Bates Communicative Developmental Inventories](https://mb-cdi.stanford.edu/documents/Fensonetal2000.pdf)


#### Analytical Process:
* Weighted survey data was obtained from [ENSAUT website](https://www.ecuadorencifras.gob.ec/salud-salud-reproductiva-y-nutricion/) in the form of csv files
* Data Wrangling was perfomred using R software.
  * Libraries used: tidyverse, data.table, tableone, ggplot2, quantreg, srvyr, gtsummary, survey, psych, corrplot
* Cronbach's alpha score was used to validate both in-survey measurement tools
* Language development scores were calculated separately for 1-1.5 years (word prodution and word comprehension) and for 1.6-2.5 years (word prodution) and 2.6-<3 years (word prodution) and fitted scores were plotted
