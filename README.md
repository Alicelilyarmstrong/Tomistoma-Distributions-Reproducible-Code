# 🐊 Tomistoma-Distributions-Reproducible-Code🐊 #
This is all the code for my master’s thesis, **Uncovering the geographic distribution of *Tomistoma schlegelii* and the role of anthropogenic pressures to inform their current status and future risk**

This Github repository was completed as part of my master’s course (Ecology, Evolution and Conservation Research) at Imperial College London.

# Raw data #

**False gharial presence records**
All *Tomistoma schlegelii* presence records sourced from; both published and unpublished datasets, 211 from Steubing et al., (2006), 113 from Sideleau (2023), 36 from Dr Agata Staniewicz and 23 from The Global Biodiversity Information Facility (2023), with additional data from; museum specimen records, sightings, published journal articles and archival field expedition journals.

**All wrangled data** for analysis and plotting has been provided on Google Drive:
<link>

**References for original sources of data:**

**GBIF False garial presence records-**
Global Biodiversity Information Facility. (2023). Occurrence Download. https://api.gbif.org/v1/occurrence/download/request/0167752-230224095556074.zip

**Steubing et al., 2006 False garial presence records-**
Stuebing, R.B., Bezuijen, M.R., Auliya, M. and Voris, H.K. (2006). The current and historic distribution of Tomistoma schlegelii (the False Gharial) (Müller 1838) (Crocodylia,Reptilia). The Raffles Bulletin of Zoology 54: 181-197. https://www.researchgate.net/publication/237301072 

**Sideleau, 2023. False garial presence records-**
Sideleau, B. (2023). The worldwide crocodilian attack database. CrocBITE. http://www.crocodile-attack.info/ 

**IUCN range polygons-**
The IUCN Red List of Threatened Species (IUCN)., (2022). Spatial Data Download. [Accessed 4th December 2022]. https://www.iucnredlist.org/resources/spatial-data-download 

**Anthropogenic land use-**
Ellis, Erle; Klein Goldewijk, Kees, 2019, "Anthromes 12K Full Dataset", , Harvard Dataverse, V3, https://doi.org/10.7910/DVN/G0QDNQ 

**Landwater mask-**
HydroSHEDS. (2023). HydroSHEDS Core Data Downloads. Version 1.1. Land Mask https://www.sciencedirect.com/science/article/pii/S0341816217303004 


**Peatland shapefiles-**
Xu, Jiren and Morris, Paul J. and Liu, Junguo and Holden, Joseph (2017) PEATMAP: Refining estimates of global peatland distribution based on a meta-analysis. University of Leeds. [Dataset] https://doi.org/10.5518/252 

# Plotting, Analyses and Wrangling #

**Some code has been adapted from:**
Alice Armstrong., (2023).Project-one-Nile-crocodile-reproducible-code. https://github.com/Alicelilyarmstrong/Project-one-Nile-crocodile-reproducible-code- 

All the R code utilized for mapping, wrangling and analysis is given in this repository. Underneath I provide a short explanation of every script.

**Mapping.Rmd-** This script plots *Tomistoma schlegelii* presence records sourced from; both published and unpublished datasets, museum specimen records, sightings, published journal articles and archival field expedition journals.

**Wrangling Presence Records.Rmd-** This script wrangles *Tomistoma schlegelii* presence records sourced from; both published and unpublished datasets, museum specimen records, sightings, published journal articles and archival field expedition journals.

**MaxEnt.Rmd-**

**Analysis.Rmd-**
