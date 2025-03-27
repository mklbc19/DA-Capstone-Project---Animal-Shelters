# Capstone Project - Animal Shelters
Data Analysis Project
## Overview
Welcome! Thank you for taking an interest in my project.  This analysis will compare the animal shelter intakes/outtakes between Louisville, KY and Dallas, TX.  After that, I am going to see how that compares to the nationwide numbers. I want to see if Louisville or Dallas was far off from each other in regards to the number of intakes and outtakes an animal shelter processes in one year.  I also want to see if there is a common trend with the type of intakes.  I assume that the larger intake/outtake numbers will be with cats and dogs, but is there one or the other that is consistent with another location? I then want to compare that to the nationwide numbers, cleaning that data to exhibit their respective states, Kentucky and Texas.   

## Data
I used three datasets in this project. Each lists numbers/incidences of intake and outakes.  I have one for Louisville, Dallas, and Nationwide.

CSV's:
1. Louisville Animal Shelter Data: https://data.louisvilleky.gov/datasets/louisville-metro-ky-animal-service-intake-and-outcome/about

2. Dallas Animal Shelter Data: https://www.dallasopendata.com/Services/Dallas-Animal-Shelter-Data-Fiscal-Year-2022-2023/f77p-sgrc/about_data

XLSX: 

3. Nationwide Animal Shelter Data: https://www.shelteranimalscount.org/data-request-free-download/

## Project Structure
After reading in the data, I wanted to narrow each dataset to one particular year that all had in common, the 2022 year.  I cleaned each set to filter that out, and then based my graphs on some questions.

The questions: 
1. Are Louisville and Dallas, while not truly similar in size, similar in their amount of intakes?
2. Between Louisville and Dallas, what do these shelter see the most of, in regards to animal types?
3. How much of the Louisville and Dallas figures relate to the overall number within their respective states in a given year?

By answering these initial questions, I believe it would provide an outlet to begin discussions on what can be done to lower these numbers, and how to better prevent a certain animal type from being the top animal type in every state.


## Getting Started
Ensure that you have the following installed:
-Python (version used 3.11.9)
-GitHub
-Jupyter Notebook
-Packages needed to run the file:
    -matplotlib.pyplot
    -seaborn
    -pandas
    -numpy

## Installation/Dependencies:
Follow the following steps to run the project on your computer:
1. Clone the repository: https://github.com/mklbc19/DA-Capstone-Project---Animal-Shelters.git to a directory for this project in your terminal.
2. Within the DA-Capstone-Project---Animal-Shelters folder, run this command in the terminal: python -m venv venv
3. Next, activate the environment by entering: source venv/Scripts/activate
4. Next install the required dependencies:  pip install -r requirements.txt

_Now, let's run the project!_

5.  Run the file: CapstoneProjectCode.ipynb (_Note: If you would like to view the Data Dictionary, run the file: DataDictionary.ipynb_)

6. Lastly, once you are complete:  In order to get out of the environment, type the word "deactivate" into the terminal.
Great job! 


## Capstone Features List utilized

***1. Loading data.*** 

Feature: Read TWO data files (JSON, CSV, Excel, etc.).  - I used 2 CSV files and 1 XLSX

***2. Clean and operate on the data while combining them.*** 

Feature: Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set.  

***3. Visualize / Present your data.***

Feature: Make 3 matplotlib or seaborn (or another plotting library) visualizations to display your data.

-Created a pie chart showing the different animal types each city took into their shelters.

-Created a bar graph showing the different outcomes for the animals brought into their shelters.

-Created a bar graph showing the different intake numbers between Louisville and KY, Dallas and TX, and combined KY/TX numbers

***4. Best practices: Enhance your project to a higher tier that will impress employers and help other programmers understand your project.***

Feature: Utilize a virtual environment and include instructions in your README on how the user should set one up

Feature: Build a custom data dictionary and include it either in your README or as a separate document.

***5. Interpretation of your data.*** 

Feature: Annotate your code with markdown cells in Jupyter Notebook, write clear code comments, and have a well-written README.md. Tidy up your notebook, and make sure you don’t have any empty cells or incomplete cells that don’t do anything. Make sure it’s all functional before your final github commit.

Feature: Build a custom data dictionary and include it either in your README or as a separate document. This will only apply if your data set does not already have a data dictionary or if you’re building a custom data set. For an example, see the resources to the right.
