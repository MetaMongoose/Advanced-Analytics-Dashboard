# Advanced-Analytics-Dashboard
Analytical tasks are performed in Python using Supervised &amp; Unsupervised Machine Learning

## Objective
To build an interactive dashboard visually showcasing well-curated results of
an advanced exploratory analysis conducted in Python.

## Life Expectancy Data
## Datasets:
1. World Bank Life Expectancy Data
   
Data Source:
The data is open source. It is an external dataset
to the project author. The dataset was compiled from separate datasets available from the Worldbank
open-source database. It can be considered as moderately reliable because although the dataset was
not compiled by myself, it has as its underlying source the Worldbank database. This is something I
was able to confirm, by accessing some of the relevant information directly from the Worldbank
webpage.

I chose this data source because it has many numeric variables whose correlation can be plotted, to reveal insights.
The relationship between the variables and their impact on life expectancy is interesting and relevant.

## Data Characteristics:
The dataset in question from an external data source. It is a dataset containing over 2,469 rows and
contains 17 columns. Excluding ‘Year’, there are 13 numerical columns, and the rest are categorical
[Country, Continent, Least Developed]. The dataset is timely as it was released in December 2023.
The data provides variables such as life expectancy, beer consumption per capita, forest area, income
and more, for 119 countries.

## Data Owner: World Bank

## Data Limitations & Ethics:
The dataset is from 2000 to 2020, which excludes the recent COVID pandemic. Although it is good to
exclude the period from analysis (because it will skew the analysis), it would e nice to see whether the
post-COVID data will have changed significantly since the pandemic.
The dataset being worked with was compiled using various datasets at the Worldbank. The Worldbank
itself, had to gather the data from various sources in different countries. Of course, this means we
cannot be 100% certain of every aspect of this dataset, but we can trust that the Worldbank will have
the best chance of retrieving reliable data.
There is no sensitive personal data in the dataset. Care should be taken to not exert bias in the analysis,
which could happen. Especially when looking at income, or similar variables which seem to favour one
set of countries over another.

## Note: The Tableau dashboard does not include the full analysis, which can be seen in the 'scripts' folder.

## Links
Data: https://www.kaggle.com/datasets/raminrzayev/life-expectancy-2000-2020/data

Dashboard: https://public.tableau.com/shared/DTKYZQRGG?:display_count=n&:origin=viz_share_link

