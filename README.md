# EDA on Kickstarter Projects

This project is part of Udacity Data Analyst Nanodegree.

Data Source - https://www.kaggle.com/kemical/kickstarter-projects

## Overview
Crowdfunding has become one of the main sources of initial capital for small businesses and start-up companies
that are looking to launch their first products. Websites like Kickstarter and Indiegogo provide a platform for 
millions of creators to present their innovative ideas to the public. This is a win-win situation where creators
could accumulate initial fund while the public get access to cutting-edge prototypical products that are not available in the market yet.

The dataset contain data on 379K projects started on Kickstarter between 2009-2018.

## Steps.

### 1 Data Wrangling:
* Removed a dubplicte column usd_pledge. 
* Removed unnecessary columns.

### 2 Analysis
* Found the categories and sub categoris with most projects.
* Found Average Goal, Pledge Amount.
* Found Relation between Backers and USD Goal.
* Number of projects by year.
* Number of projects by country.
* State of projects.
* Total amount pledged by category.
* Number of Successful project by main category.
* Success rate of projects by year.
* Top projects with highest set goals.
* Top Successful projects.
* Distribution of USD Goal and USD Pledged.
* Average amount Pledged per Backer on each Category.
* Number of  Backers per category and their success ratio.
* Project Success Ratio by country and category.


### Requirements
* R
* ggplot2
* dplyr
* ggthemes
* rworldmap
* knitr
* tidyr
* gridExtra
* grid

### References
* Missing values - https://discuss.analyticsvidhya.com/t/how-to-count-the-missing-value-in-r/2949/13
* Removing columns - https://discuss.analyticsvidhya.com/t/how-to-delete-a-column-from-a-data-frame-in-r/1311
* Extracting Year - https://stackoverflow.com/questions/36568070/extract-year-from-date
* Maps - https://www.rdocumentation.org/packages/rworldmap/versions/1.3-6
* Labels - https://stackoverflow.com/questions/14726078/changing-title-in-multiplot-ggplot2-using-grid-arrange
* Tidyr - https://tidyr.tidyverse.org/
* Kable - https://stackoverflow.com/questions/33396650/how-do-you-print-table-in-knitr
* Roataing text - https://stackoverflow.com/questions/1330989/rotating-and-spacing-axis-labels-in-ggplot2
* Colors - https://stackoverflow.com/questions/26387670/how-to-specify-low-and-high-and-get-two-scales-on-two-ends-using-scale-fill





