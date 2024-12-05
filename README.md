# A.V._Data

This GitHub serves as the central repository for all codes and notebooks related to the study on the social, economic, and cultural impact of immigration in Cataluña. The study aims to provide a comprehensive understanding of how immigration has shaped various aspects of life in the region, offering insights into demographic trends, labor market dynamics, social integration, and cultural transformation. The dataset used for this study and its results can be obtained from [Exploring the Social, Economic, and Cultural Impact of Immigration in Cataluña](https://figshare.com/projects/Exploring_the_Social_Economic_and_Cultural_Impact_of_Immigration_in_Catalu_a/229650).

## Folders details
The Project is divided in 4 different folders.

### carto
This folder contains the data necesary to plot the maps.

### Economic_Sector
This folder holds the notebooks used to study the correlation between nationality and the economic sector in which a given person is working.
The code is divided into three notebooks
- Poblacion_edad_trabajar.ipynb: Filters the dataset 'Poblacion_inmigrante.csv' to extract information about the number of migrants (by country of birth and municipality) who are of working age.
- Correlacion_Sector-Nacionalidad.ipynb: computes the Pearson coefficent correlation between the number of migrants of each nationality nd the number of Jobs in the four main economic activities in the región (primary sector, industry sector, construction sector and service sector).
- World_map_plot_of_correlations.ipynb: plots a world heat map to show the Pearson coefficent value for each nationality and a given sector.

### Income
This folder includes notebooks used to analyze the relationship between average income per person and the proportion of foreign residents. This analysis is segmented by municipality type, categorized by urbanization level and population density.

### Religious_Centers
This folder encompasses the notebooks utilized to explore the relationship between religious diversity and cultural diversity, assessing potential correlations and patterns.

### Study_level
This folder holds the notebooks leveraged to investigate the connection between educational attainment levels and immigrant population distribution, offering insights into how immigration impacts education across the region.
- study_level.ipynb: It combines the dataset of study levels(weighted average of 10 categories) and map(comarcas) and draws a heat map. Additionaly, it also calculates the correlation coefficient between study levels(weighted average).



## About this repository
Repository for the subject A.V._Data subject of the master in Physics of Complex and Biological systems, Universitat de Barcelona.
