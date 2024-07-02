# Data Analysis using R

This repository contains the documentation, exercises and datasets of a three day workshop on ['Data Analysis using R'](https://github.com/BB1464/Data-Analysis-using-R) for African Fellows, at Mississippi State University, 2024

## Workshop description

R is a powerful programming language for data handling, data visualization, and statistics. In this training, we aim to give you the tools to start exploring R and all it has to offer by yourself.

The training will take you from the very basics in R syntax, to data handling and visualization using a set of packages designed for data science, known as the 'tidyverse'. We will also take some time to understand datasets and their architecture, preparing you to handle your own data in a clean, robust, and reproducible manner. We will work in RStudio and introduce R scripts as well as the R Markdown format along side with quarto: the latter is a great way to combine code and its output with text, allowing you to code in a narrative and intuitive way. Moreover, this way you produce a human-readable document with which you can easily share and showcase your work.

# Pre-Requisite for Attending this Training

-   You need to have a laptop with a minimum of 4 Gig RAM

-   You need to have internet connection to Install R, R Studio and all the required packages.


**Learning objectives**:

-   Installation of R and R Studio

-   Introduction to R and R Studio.

-   Data Import and Export

-   Descriptive statistics

-   Data wrangling

- Analysis of Variance (CRD,RCBD, Split Plot)

- Correlation

- Data Visualization


The African fellows do not need to have any previous knowledge in R before attending the training.

## Schedule

### Rice Hall, Conference Room, Mississippi State University, 2024

by **Oluwafemi Oyedele**

------------------------------------------------------------------------

:spiral_calendar: 17, 18,  and 19th of July, 2024

:alarm_clock: 08:30 AM - 04:30 PM

:hotel: Mississippi State University

:writing_hand: <https://github.com/BB1464/Data-Analysis-using-R/>

------------------------------------------------------------------------

## Installation requirements

This course requires three things to be installed:

-   The language **R**

-   The IDE **Rstudio**

-   The packages in **tidyverse**

Information on how to install these (and troubleshoot the installation) is on our [installation guide](installation.md).

R and R Studio can be installed through this link [**here**](https://posit.co/download/rstudio-desktop/)

# To Download the Workshop Materials from Github

install.packages("devtools")

library(usethis) # This line loads the usethis package into R memory

use_course("https://github.com/BB1464/Data-Analysis-using-R/archive/refs/heads/master.zip") # this line will pull all the source code from my github repo into your system.


# Day 1

| Date       | Time                | Activities                                 |
|----------------|------------------|--------------------------------------|
| 2024-07-17 | 08:30 AM to 11:30 AM | Installation of R and R Studio             |
| 2024-07-17 | 08:30 AM to 11:30 PM | Introduction to R and RStudio              |
| 2024-07-17 | 08:30 AM to 11:30 PM | Data Import and Export                     |
| 2024-07-17 | 08:30 AM to 11:30 PM | Data summary (Descriptive statistics) |
| 2024-07-17 | 08:30 AM to 11:30 PM | Data Wrangling                             |

# Day 2

| Date       | Time                | Activities                                                                                       |
|-------------|-------------|-----------------------------------------------|
| 2024-07-18 | 08:30 AM to 11:30 PM | Recap and Questions                                                                              |
| 2024-07-18 | 08:30 AM to 11:30 PM | Analysis of Variance (CRD, RCBD, Split Plot Design) |
| 2024-07-18 | 08:30 AM to 11:30 PM | Data Visualization                                                                                |
| 2024-07-18 | 08:30 AM to 11:30 PM | Correlation                                                                                      |


# Day 3

| Date       | Time                | Activities             |
|------------|---------------------|------------------------|
| 2024-07-19 | 08:30 AM to 11:30 PM | Recap and Questions     |
| 2024-07-19 | 08:30 AM to 11:30 PM | Linear regression       |
| 2024-07-19 | 08:30 AM to 11:30 PM | PCA                     |

## Instructors

- **Michael J. Mulvaney, PhD, CCA**
**Hartwig Endowed Chair for Soybean Agronomy**
Department of Plant and Soil Sciences 
544 Rice Hall

- **Oluwafemi Oyedele**
PhD Student
Department of Plant and Soil Sciences 
543 Rice Hall
Mississippi State University

## Presenter

**Oluwafemi Oyedele** holds a master Degree in Agronomy from the University of Ibadan, Nigeria, and he is currently a PhD Student at the Department of Plant and Soil Science, Mississippi State University.


The slides can be found [**here**](https://bb1464.github.io/Data-Analysis-using-R/)



## Packages

my_packages <- c("tidyverse","readxl","factoextra","agricolae","agridat","lmerTest","lme4","sjPlot","skimr","ggtext","exrafont","correlation","metan","fontawesome","emoji","devtools","multcomp","writexl","pastecs","rsthemes","esquisse","here","gridExtra","psych")

install.packages(my_packages, repos ="http://cran.rstudio.com")


<h1 align="center">

African Fellows, Mississippi State University, 2024!!!

</h1>

<p align="center">

<img src="https://github.com/BB1464/Data-Analysis-using-R/blob/master/slides/images/msstate.svg" width="50%"/>

</p>

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
