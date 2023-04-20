# Compiling Data of Aviations with the Least Amount of Risk 
![alt text](https://www.airpics.net/UserFiles/pics/large/PH-BFH-Boeing-747-400M-KLM-Royal-Dutch-Airlines/15650/15622l.jpg)

### Link to the Presentation:
[file:///C:/Users/16047/Desktop/Presentaion.pdf
](https://docs.google.com/presentation/d/1enJwfd8tEOVktCor2oLFIEsfJo3zUZKYbw-Betb_ivA/edit?usp=sharing)

### Link to the Notebook:
https://github.com/Kaewin/phase1_project_group2/blob/main/eda_file_fixed.ipynb



# Overview

We were hired by a company that is looking to expand into the aircraft industry, with an interest in private and commercial enterprises. 


# Key Business Problem and Question

The end goal of our data analysis, is to answer the question of which aircraft is going to be the lowest risk for the company's endeavour's, as well as provide three concrete business recommendations explaining which aircraft the company should invest in.


# Data Analysis And Understanding


### Source of Original Data

The source of the data is Kaggle's Aviation Accident Database & Synopses dataset.
https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses


### Description of Our Data

This data contains plane crash information from as early as 1948 to 2021 consisting our various components explaining each crash like the make and model of the plane that crashed and the damage done to the plane from the accident, etc.

### Researching our Findings Regarding the Engines
The Reciprocating engine was developed in the 18th century and stopped being as largely used in 1994. 

A reciprocating engine is only one combustion engine hence they can only power small planes. (i.e 20 people)

We decided to exclude the reciprocating engine and any makes with only 1 engine from our data to  determine what to recommend for planes. 

There are also crashes with 6 and 8 engines… those are not common and its unusual for a commercial passenger plane to have more than 4 engines. We also decided to exclude these engines.


### Three Visualizations

- Visualization one is a comparison of the all crashes for any make with with three engines. The color of each make's bar represents how many were Injured in the total number of crashes, while the text represens how many were uninjured for the total amount of crahses.
![alt text](https://github.com/Kaewin/phase1_project_group2/blob/main/Plane%20makes%20with%20three%20engines%20displaying%20how%20many%20injured%20or%20uninjured%20in%20all%20crashes.png)

- Visualization two is comparing the aircraft damage between the three planes. 

![2rd viz](https://github.com/Kaewin/phase1_project_group2/blob/main/visualization_carrier_damage2.png)

- Visualization three shows which helicopter model holds the highest average of uninjured passengers during an accident.
![3rd viz](https://user-images.githubusercontent.com/116228715/233461232-6b1408a0-df16-4c88-9f62-3da7fe28af36.png)


# Conclusion

After analysing the data and forming our visualizations we are able to come to the conclusion of recommending the following for passenger and cargo transportation via plane, and the (testing) helicopter;

- The Boeing 747 becuase the Boeing 747 has a balance of both safety and space, a nose that opens, and also has the ability to carry passengers. 

- To use a boeing make with three engine makes for passenger commercial planes because of its low accident to injury ratio.

- And the Sikorsky S76 helicopter for private enterprises since it has reliably held a high number of average uninjured passengers over time and because the Bell 214ST ceased production in 1993.



