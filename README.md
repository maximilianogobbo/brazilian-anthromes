# brazilian-anthromes
Repository of the Doctoral Thesis "REGIONALIZATION OF BRAZILIAN ANTHROMES: Tool for Mapping in R® Language".

# Brazilian Anthromes

## Description

This repository includes R Markdown scripts and documents (`.Rmd`) associated with the Doctoral Thesis "REGIONALIZATION OF BRAZILIAN ANTHROMES: Tool for Mapping in the R® Language". The projects available here involve the capture, analysis, mining, treatment, manipulation, plotting and mapping of demographic and land use and cover data.

The data used in this research were produced by the Brazilian Institute of Geography and Statistics (IBGE), to which we are immensely grateful for making this wide range of information available.

## Requirements

To run the scripts from this repository, you will need to have the following software installed:

- [R](https://cran.r-project.org/)
- [RStudio](https://www.rstudio.com/)

Additionally, you will need to install some R packages. The main packages used are:

library(sf)      
library(terra)   
library(dplyr)   
library(spData)
library(raster)
library(ows4R)
library(osmdata)
library(geodata)
library(tigris)
library(tidycensus)
library(GSODR)
library(tidyverse)
library(ggplot2,gapminder, magrittr)
library(pander)
library(rgdal)
library(leaflet)
library(rmapshaper)
library(mapview)
library(tmap)
library(osmdata)
library(ggmap)
library(grid)
library(gridExtra)
library(png)
library(readxl)

## Usage

This repository contains three main R Markdown files (`.Rmd`). Here is a brief description of each and how to use them:

1. **demographic_analysis.Rmd**:
   - **Description**: This file captures and analyzes demographic data.
   - **Usage**: Open `demographic_analysis.Rmd` in RStudio and click the `Knit` button to generate the HTML document. Alternatively, you can render the document from the command line:

     ```r
     rmarkdown::render("C:/ARQUIVOS COMPUTADOR/DOUTORADO/DOUTORADO TESE/03 DADOS GEOESPACIAIS/02.1 DEMOGRAPHIC/demographic_analysis.Rmd")
     ```

2. **ucs_analysis.Rmd**:
   - **Description**: This file deals with mining and manipulation of land use and land cover data.
   - **Usage**: Open `ucs_analysis.Rmd` in RStudio and click the `Knit` button to generate the HTML document. Alternatively, you can render the document from the command line:

     ```r
     rmarkdown::render("C:/ARQUIVOS COMPUTADOR/DOUTORADO/DOUTORADO TESE/03 DADOS GEOESPACIAIS/03.1 LAND USE AND COVER/ucs_analysis.Rmd")
     ```

3. **land_planning.Rmd**:
   - **Description**: This file is used for plotting and mapping geospatial data.
   - **Usage**: Open `land_planning.Rmd` in RStudio and click the `Knit` button to generate the HTML document. Alternatively, you can render the document from the command line:

     ```r
     rmarkdown::render("C:/ARQUIVOS COMPUTADOR/DOUTORADO/DOUTORADO TESE/03 DADOS GEOESPACIAIS/04.1 LAND PLAN/land_planning.Rmd")
     ```

Replace the file paths (`"C:/ARQUIVOS COMPUTADOR/DOUTORADO/DOUTORADO TESE/..."`) with the actual paths to the `.Rmd` files on your system. Make sure to correct any typos or extra spaces in the file names.

## Contribution

You are welcome to contribute to this project in several ways:

- Open issues reporting bugs or suggesting new features.
- Send pull requests with bug fixes or improvements.
- Provide feedback on how we can make this project even better.

If you want to contribute code, please follow these guidelines:
- Create a separate branch for your changes.
- Clearly describe your changes in the pull request.
- Make sure your code is adequately tested.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the [LICENSE](LICENSE) file for more details.
