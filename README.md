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

- The Boeing 727 make is the only Boeing make with three engines, and since three engine makes are the safest we will therfore reccommend that for passenger commercial planes.

- And the Sikorsky S76 helicopter for private enterprises since it has reliably held a high number of average uninjured passengers over time and because the Bell 214ST ceased production in 1993.


# References

“198e2ca2ac95198d0f1e4562e14119fb.Jpg (JPEG Image, 236 × 259 Pixels).” Accessed April 20, 2023. https://i.pinimg.com/236x/19/8e/2c/198e2ca2ac95198d0f1e4562e14119fb.jpg?nii=t.

“15622l.Jpg (JPEG Image, 1024 × 703 Pixels).” Accessed April 20, 2023. https://www.airpics.net/UserFiles/pics/large/PH-BFH-Boeing-747-400M-KLM-Royal-Dutch-Airlines/15650/15622l.jpg.admin. 

“Types of Aircraft Shipping Cargo and Types of Loads.” International Forwarding Association Blog (blog), October 24, 2019. https://ifa-forwarding.net/blog/air-freight-in-europe/types-of-aircraft-shipping-cargo-and-types-of-loads/. 

Bailey, Joanna. “The Global Cargo Workhorse: Why The Boeing 747F Is Winning.” Simple Flying, February 5, 2021. https://simpleflying.com/global-cargo-workhorse-747f/.

“Boeing 747.” In Wikipedia, April 15, 2023. https://en.wikipedia.org/w/index.php?title=Boeing_747&oldid=1149987448.

Business Jet Traveler. “Boeing BBJ 747-8i,” October 27, 2021. https://bjtonline.com/business-jet-news/boeing-bbj-747-8i.

“Reciprocating Engine.” In Wikipedia, March 14, 2023. https://en.wikipedia.org/w/index.php?title=Reciprocating_engine&oldid=1144567996.

“Sikorsky S-76.” In Wikipedia, March 28, 2023. https://en.wikipedia.org/w/index.php?title=Sikorsky_S-76&oldid=1147115454.
