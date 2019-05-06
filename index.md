
The ECVPH workshop entitled **Additive Bayesian Networks as an alternative for risk factor studies** using the R package [Additive Bayesian Networks](https://cran.r-project.org/package=abn) is a funded training workshop by The European College of Veterinary Public Health ([ECVPH](https://ecvph.org/meetings-events/ecvph-residents-workshop-abn-modeling)) from May 7-9th, 2019 in Zurich (Switzerland).

# General information

**When:** May the 7-9th 2019

**Where:** Zurich, Switzerland. Room: **BIN-1-E.01 EV**

**Requirements:** Personal laptop. Basic statistics and basic knowledge of R. No prior knowledge about graph theory or Bayesian statistics is needed. Please follow the getting started [checklist](getting_started.md)

**Instructors:** Sonja Hartnack & [Gilles Kratzer](https://gilleskratzer.netlify.com/)

Additive Bayesian Networks (ABN) have been developed to disentangle complex relationship of highly correlated datasets as frequently encountered in risk factor analysis studies. ABN is an efficient approach to sort out direct and indirect relationships among variables which is surprisingly common in systemic epidemiology. The participants are able to run the particular steps within an ABN analysis with real world data. They are able to contrast this approach with standard regression (linear, logistic, Poisson and multinomial models) used for classical risk factor analysis. The participants will be introduced to general machine learning techniques (bootstrapping, variable importance plot, random forest).

Despite the fact that the theoretical foundations of ABN have been well established for decades, the practical implementation is not yet readily available in standard software. The purpose of the organisers is to make this methodology more accessible for wider audience. Ultimately, this workshop aims at empowering residents with new innovative statistical methods relevant for quantitative research.

# Learning outcomes

- To understand the basic theory behind structure discovery and Additive Bayesian
Networks modelling
- To learn how to set up and interpret an Additive Bayesian Network model for
multivariate analysis of animal health data using the R package [abn](https://cran.r-project.org/package=abn)
- To learn more about alternative methodologies for risk factor analysis coming from machine learning such as stepAIC, RandomForest, ensemble methods, feature extraction

# Schedule

**Tuesday 07.05.2019**

| Time         | Topic                          | Material|
|--------------|--------------------------------|---------|
| Morning      | Welcome & info (housekeeping, learning objectives)| [Presentation](source/Presentations/gk_welcome.pdf) |
|              | Talk on an ABN example         |         |
| 12:30 - 13:30| <span style="color:blue"> Lunch </span> ||
| Afternoon    | Check installation R (Rstudio, RGraphiz, INLA, JAGS)| [Test](test_install.html) |
|         | Warm up Hands-on exercises | [Exercice Salmonella](exo_descr_stats_salm.html) <br>  [Solution Salmonella](sol_descr_stats_salm.html) / [Exercice PIG](exo_descr_stats_pig_adg.html) / [Solution PIG](sol_descr_stats_pig_adg.html) / [Data](source/data.zip) |
|              | Regression models        |         |

**Wednesday 08.05.2019**

| Time         | Topic                          | Material|
|--------------|--------------------------------|---------|
| Morning      | Methods for risk factor analysis||
|              | Hands-on exercises         |         |
| 12:30 - 13:30| <span style="color:blue"> Lunch </span> ||
| Afternoon    | ABN in a nutshell |         |
|              | Hands-on exercises          |         |



**Thursday 09.05.2019**

| Time         | Topic                          | Material|
|--------------|--------------------------------|---------|
| Morning      | Advanced methods with ABN||
|              | Hands-on exercises         |         |
| 12:30 - 13:30| <span style="color:blue"> Lunch </span> ||
| Afternoon    | ABN on your own data |         |
|              | Wrap up discussion                               |         |

The hands-on exercises of the workshop is based on two open access datasets that can be downloaded here:

- [adg dataset](source/data/pig_adg.csv)
- [salmonela dataset](source/data/sal_outbrk.csv)

The two dataset are described in [Dohoo, Martin and Wayne - Veterinary Epidemiologic Research (second edition)](http://projects.upei.ca/ver/).

# Selected list of reference papers

*Application papers*:

- [Comin et al.](https://www.sciencedirect.com/science/article/pii/S0167587718304665?via%3Dihub#kwd0010)
- [Ruchti et al.](https://www.sciencedirect.com/science/article/pii/S0167587718306159?via%3Dihub)
- [Hartnack et al.](https://bmcvetres.biomedcentral.com/articles/10.1186/s12917-016-0649-0)

*Background papers:*

- [Lewis et al.](https://ete-online.biomedcentral.com/articles/10.1186/1742-7622-10-4)
