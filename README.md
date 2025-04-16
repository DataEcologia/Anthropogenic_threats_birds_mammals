# Anthropogenic_threats_birds_mammals
# Global impacts of anthropogenic threats on bird and mammal functional groups


## Abstract:

Anthropogenic threats vary in how they affect individual species, functional diversity, and consequently, ecosystems as a whole. However, which groups of species are most affected by specific threats remains poorly understood. Here, we use data aggregated by the International Union for Conservation of Nature (IUCN) to evaluate the extent to which diet functional groups and body size explain the global impacts of the most common anthropogenic threats to birds and mammals. Using logistic regression models, we found that vertivores (terrestrial vertebrate predators), aquatic predators, and frugivores are most negatively impacted by anthropogenic threats. For both birds and mammals, crops and livestock are the top threats to vertivores, climate change and pollution are the top threats to aquatic predators, and logging is the top threat to frugivores. Crops and hunting affect many functional groups including vertivores, frugivores, and herbivores, while plantations and recreation/work affect less than 5% of species in every functional group. Body mass is positively correlated with threat impacts across anthropogenic threats but especially for hunting, such that globally, larger species are substantially more threatened by hunting than smaller species. Our results reveal that bird and mammal vulnerabilities vary by diet functional group, species body size, and the type of anthropogenic threat. Given our findings that functionally important groups, such as predators and frugivores, are disproportionately impacted by multiple anthropogenic threats, and that individual threats differ in their severity across functional groups, we recommend targeting conservation actions to mitigate threats in a manner that will preserve threatened ecosystem functions.



## Data
This folder contains:
            i) Anthropogenic threat data for bird and mammal species downloaded from the the International Union for Conservation of Nature (IUCN) online database.
            (https://www.iucnredlist.org/resources/threat-classification-scheme).
            ii) Trait data for bird and mammal species - obtained from the AVONET database for birds, and the PHYLACINE and EltonTraits databases for mammals.


The files are in a.csv format.


## Code

This folder contains all the code required to:
                  i)   Download anthropogenic threat data from the International Union for Conservation of Nature (IUCN) online database for bird and mammal species.
                  ii)  Combine anthropogenic threat data and trait data (diet functional groups and body mass).
                  iii) Fit logistic regression models.

We carried out our data processing, cleaning and model fitting using R (R Core Team 2024).
