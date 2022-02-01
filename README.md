# language-development-among-ecuadorian-children
Assessed the association between home environment and language development among children aged 1-3 years using the Ecuadorian National Health and Survey data, ENSANUT 2018

## Introduction

#### Language development is one of the core skills that help in the assessement of developmental trajectories among young children. While individual variation in trends are common,external factors such as physical environment, and parental behaviours and engagement with the child can higly affect the overall developmental process.


#### In-survey tools used:
* [HOME inventory](https://uwm.edu/mcwp/wp-content/uploads/sites/337/2015/12/HOME12-1-14.pdf)
* [Shortform MacArthur Bates Communicative Developmental Inventories](https://mb-cdi.stanford.edu/documents/Fensonetal2000.pdf)


#### Analytical Process:
* Weighted survey data was obtained from [ENSAUT website](https://www.ecuadorencifras.gob.ec/salud-salud-reproductiva-y-nutricion/) in the form of csv files.
* Based on the MacArthur scales, data was split into three subgroups: 12- 18 months, 19-30 months and 31-35 months
* Data Wrangling was perfomred using R software.
  * Libraries used: tidyverse, data.table, tableone, ggplot2, quantreg, srvyr, gtsummary, survey, psych, corrplot
* Cronbach's alpha score was used to validate both in-survey measurement tools
* Language development scores were calculated separately for 12- 18 months (word prodution and word comprehension) and for 19-30 months (word prodution) and 31-35 months (word prodution) and fitted scores were plotted.

![This is an image](/Assets/CDI_scores/.png)

* HOME Inventory scors were calculated for each of the age categories.

* Mother's education one of the most important factor known to contribute towards the physical environment of the child was assessed in relation to both HOME and language developmental scores.

* Unadjusted and adjusted liner regression models were build to quantify the statistical significance of primary and secondary independent variables in our analysis.


#### Results:
* Home environment does have a positive effect on the Language development during the early stages of life
* Effect of HOME on language development is mediated by maternal education
* Difference exists in the level of emphasis of HOME subscales for correlation vs. causation
  * Provision of appropriate play materials had the highest correlation with language scores.
  * However, variety in opportunity for daily stimulation had the largest effect on language scores.








