![](www/eddie_banner_2020_test.png)<!-- -->

# [Macrosystems EDDIE](https://serc.carleton.edu/eddie/macrosystems/index.html)

## Module 9: Using High-Frequency Data to Manage Water Quality
[![](https://img.shields.io/badge/Shiny-shinyapps.io-blue?style=flat&labelColor=white&logo=RStudio&logoColor=blue)](https://macrosystemseddie.shinyapps.io/module9/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13835236.svg
)](https://doi.org/10.5281/zenodo.13835236)
<a href="url"><img src="www/mod9_conceptual_figure.png" align="right" height="220" width="293" ></a>

### Summary
Here are the code and instructor materials for running the Macrosystems EDDIE Module 9: _Using High-Frequency Data to Manage Water Quality_. Below are instructions on how to access the Shiny app *via* a web browser and also a detailed guide below for launching the R Shiny App locally on your own computer. Open-source versions of all instructor materials are available in the instructor_materials.zip file. For more details about teaching this module, including editable versions of instructor materials which can be downloaded and modified for teaching purposes, please visit our [website](https://serc.carleton.edu/eddie/teaching_materials/modules/module9.html).

## Accessing the Shiny App _via_ a web browser
The Shiny app for this module can be accessed through any internet browser on [shinyapps.io](https://macrosystemseddie.shinyapps.io/module9/).
When first launching it will take a while for the Shiny app to boot up. 

##  Running the Shiny App locally on your computer
### Pre-requisites
1. Latest version of [R](https://cran.r-project.org/) installed.  
2. Latest version of [RStudio](https://rstudio.com/products/rstudio/download/).  

### Step 1: Download this repository
There are two options:  
1. Download the repository as a .zip file. (Easiest option).  
    a.  Click the green "Code" button on this page and select "Download ZIP".  
    b.  Unzip this file on your computer.  
2. Clone this repository into RStudio.  
		a.  Open RStudio.  
		b.  Click "File > New Project...".  
		c.  In the "Create Project dialog select "Version Control: Checkout a project from a version control repository".  
		d. Select "Git: Clone a project from a Git repository.  
		e. In the "Repository URL:" option input the URL to this repository, select where to save the project directory.  
		f. Click "Create Project".  
		g. You will then have a project with all the files from this repository.  
		
### Step 2: Install required R packages
1. The list of required of packages is detailed in the `install.R` script in this repository. Open and run this script to install the necessary packages.  
  Watch out for errors in package installation. Most can be avoided using the most up-to-date version of R (4.0.3 as of 2021-01-22).  
  Updating of current R packages on your system is recommended.

### Step 3: Launch Shiny App
1. Open the script `app.R` in your console.  
2. Click the "Run App" button in the Script (indicated below).  
3. This will launch the Shiny App in your default web browser or in a new RStudio window. The Shiny App is run from RStudio so you will need to keep RStudio running in the background.  
![](www/launch_app.png)<!-- -->	

## Quickstart option
Here is an alternative way to quickly launch the Shiny app in less than a minute, but can be prone to package installation errors if your packages have not been updated recently.
```
# Step 1. Install required R packages
source("https://raw.githubusercontent.com/MacrosystemsEDDIE/module7/main/install.R")

# Step 2. Launch Shiny app
shiny::runGitHub("module7", "MacrosystemsEDDIE", ref = "main", subdir = "app")
```

## Questions & Feedback
If you have any questions, comments or feedback related to these materials you can send an email to [macrosystemseddie@gmail.com]().
 
