# GEOG5990
ID: 201416775
Do health promoting neighbourhoods have lower neighbourhood churn in Manchester?

Background and context:

This data analysis aims to understand the relationship between how 'healthy' Manchester LSOAs are and the mobility of households across these LSOAs. This is achieved through using two datasets from the Consumer Data Research Centre (CDRC) - Residential Mobility Index (across 2011 LSOA boundaries) and Access to Healthy Assets & Hazards (across 2021 LSOA boundaries). The relationship between neighbourhood characteristics and residential mobility has been widely investigated in the literature with some finding no relationship while others find neighbourhood quality influences residential mobility as well as age, education, income and employment (Rabe and Taylor, 2010). Rabe and Taylor (2010) explore the relationship between subjective and objective dimensions of neighbourhood and residential mobility through combining survey data with indices of multiple deprivation, which includes indices relating to health. They find that while neighbourhood quality influences mobility, life events such as having a baby and becoming unemployed played a more significant role.
This is an important preliminary analysis as it demonstrates whether health inequalities across Manchester affect population stability, which can have wider implications on social relations and attachment to place – associated with belonging and enjoyment (Bailey et al., 2011). For instance, in a study in Leicester, “it was stability and the ability to feel comfortable in the neighbourhood that was most highly sought after and prized by all the respondents” (Burrell, 2016, p.1612). The code aims to demonstrate any relationship between healthy promoting LSOAs and residential mobility through correlation analysis, and spatial relationships through interpreting choropleth maps of the two variables.

Data used:

The CDRC Residential Mobility Index (RMI) measures the proportion of households that have changed between any year going back to 1997 and the beginning of 2023 (CDRC, 2024b). It is useful in this analysis for representing the neighbourhood 'churn' as it is represented at small geographical scale at 2011 LSOA boundaries and it allows for more short-term analysis (over 5 years) as opposed to relying on census data which is collected every 10 years. This analysis focuses on residential mobility within a 5-year period between 2018 and 2023 as this is deemed representative of household change. For instance, Coulton et al. (2012) use 3-year mobility rates to determine high rates of residential mobility. (….) It is estimated based on administrative and consumer datasets including electoral registers, consumer registers and land registry house sale data. The dataset is also available at 2021 LAD boundaries; however, this analysis uses 2011 LSOA boundaries because, although being slightly outdated, they offer more "fine-grained area analysis at the local level than more heterogenous census tracts or wards" (Rabe and Taylor, 2010, p.536). It is worth noting that the recent RMI data used in this analysis may not include some household changes due to delays in the change of registered addresses (CDRC, 2024b).
The CDRC Access to Health Assets and Hazards (AHAH)(Version 4) was also used in this analysis as it is a multi-dimensional index representing how 'healthy' neighbourhoods are in terms of access to certain retail environments (fast food outlets, pubs, gambling outlets), health services (GPs, hospitals, dentists, leisure facilities), air quality and physical environment (bue and green spaces) (CDRC, 2024a). It consists of a total of 14 inputs, making up these 4 domains. The data is represented across 2021 LSOAs in England. The sources in the dataset are high quality and of low bias (CDRC, 2024a).
Both 2011 and 2021 LSOA datasets were downloaded from the Open Geography Portal and clipped to Manchester and are included in the GitHub repository. 

References:

Bailey, N., Kearns, A. and Livingston, M. 2011. Place attachment in deprived neighbourhoods: The impacts of population turnover and social mix. Housing Studies. 27(2), pp.208-231.

Burrell, K. 2016. Lost in the ‘churn’? Locating neighbourliness in a transient neighbourhood. Environment and Planning A: Economy and Space. 48(8), pp.1599-1616.

CDRC. 2024a. Access to Healthy Assets & Hazards (AHAH). [Online]. [Accessed April, 24]. Available from: https://data.cdrc.ac.uk/dataset/access-healthy-assets-hazards-ahah

CDRC. 2024b. CDRC Residential Mobility Index. [Online]. [Accessed April, 24]. Available from: https://data.cdrc.ac.uk/dataset/cdrc-residential-mobility-index

Coulton, C., Theodos, B. and Turner, M.A. 2012. Residential mobility and neighbourhood change: Real neighbourhoods under the microscope. Cityscape. 14(3), pp.55-89.

Rabe, B. and Taylor, M. 2010. Residential mobility, quality of neighbourhood and
life course events. Journal of the Royal Statistical Society Series A: Statistics in Society. 173(3), pp.531-555.



