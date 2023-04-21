# Compiling Data of Aviations with the Least Amount of Risk 
![alt text](https://www.airpics.net/UserFiles/pics/large/PH-BFH-Boeing-747-400M-KLM-Royal-Dutch-Airlines/15650/15622l.jpg)

### Link to the Presentation:
[Google Slides](https://docs.google.com/presentation/d/1enJwfd8tEOVktCor2oLFIEsfJo3zUZKYbw-Betb_ivA/edit?usp=sharing)

### Link to shared Google document
[Google Document](https://docs.google.com/document/d/1E14m0Rzj6lvLjL-SPDnxHwR3FHaAxe7cRZ2fNWmaQ-M/edit)

### Link to the Notebook:
https://github.com/Kaewin/phase1_project_group2/blob/main/eda_file_fixed.ipynb

### Link to Interactive Dashboard:
[Tableau](https://public.tableau.com/app/profile/jonnie.brown/viz/LowRiskAviation/LowRiskAviation?publish=yes)

# Overview

We were hired by a company that is looking to expand into the aircraft industry, with an interest in private and commercial enterprises. 


# Key Business Problem and Question

The end goal of our data analysis, is to answer the question of which aircraft is going to be the lowest risk for the company's endeavour's, as well as provide three concrete business recommendations explaining which aircraft the company should invest in.


# Data Analysis And Understanding


### Source of Original Data

The source of the data is Kaggle's Aviation Accident Database & Synopses dataset.
https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses


### Description of Our Data

This data contains plane crash information from as early as 1948 to 2021 consisting our various components explaining each crash like the make and model of the plane that crashed, the damage done to the plane from the accident, the number of enines on the plane tha crashes, how many were injured or uninjured throghout the crashes, etc.


### Filtering Data

What business are we operating with i.e -20 plane or - 300 plane? 

For example, A SeaPlane is a commercial plane that has 1 engine and can only hold a max of 20 people, this can help us filter out other columns like 

For an even more narrow list i.e the ‘make’ determines what kind of plane you are using meaning which means that certain makes won't be relevant for the comparison needed.

![alt text](https://github.com/Kaewin/phase1_project_group2/blob/main/Images/engnum.png)

The Number of engines determine how large the plane is i.e the smaller the engine number the smaller the plane, 

This brings us back to determining the size capacity of the aircraft so we will need to choose what kind of commercial or private plane is our company interested in,

once we determine what of plane we are interested in we can analyze the crashes based on our specific plane type… because we can actually take the “engine_type” and see which engine type has the most fatalities 

![alt text](https://github.com/Kaewin/phase1_project_group2/blob/main/Images/engtype.png)

Potentially deciding to cross off a value that will not be used for our specific aircraft for a business - for example the Reciprocating engine type is a single engine and has the most crashes compared to other engine types it is also rarely used today so we probably wouldn't be recommending an aircraft with that engine type.




### Researching our Findings Regarding the Engines

The Reciprocating engine was developed in the 18th century and stopped being as largely used in 1994. 

A reciprocating engine is only one combustion engine hence they can only power small planes. (i.e 20 people)

We decided to exclude the reciprocating engine and any makes with only 1 engine from our data to determine what to recommend for planes. 

There are also crashes with 6 and 8 engines. Those are not common and its unusual for a commercial passenger plane to have more than 4 engines. We also decided to exclude these engines.

Planes with three engines have the LEAST amount crashes compared to other planes, 
And the LEAST amount of accidents and total injured out of all categorized crashes,
The percentage of three engine plane crashes in the total airplane crash data set is 2.4%.

Planes with four engines crashed LESS than planes with two engines,
But crashed MORE than the planes with three engines
The percentage of four engine plane crashes in the total airplane crash data set is 4.5%.

When further looking into the 16 Boeing 727 (3 Engines) crashes we can see that only 3 of those 16 crashes had injuries, none of them including fatal injuries.
Number DCA09FA048: 11 Serious Injuries, 1 Minor Injury
Number DCA82IA031: 1 Serious Injury, 1 Minor Injury
Number DFW06LA024: 1 Serious Injury


### Three Visualizations

- Visualization one is a comparison of the all crashes for any make with with three engines. The color of each make's bar represents how many were Injured in the total number of crashes, while the text represens how many were uninjured for the total amount of crahses.
![alt text](https://github.com/Kaewin/phase1_project_group2/blob/main/Images/alex_vis.png)

- Visualization two is comparing the aircraft damage between the three planes. 

![2rd viz](https://github.com/Kaewin/phase1_project_group2/blob/main/Images/kaelyn_vis.png)

- Visualization three shows which helicopter model holds the highest average of uninjured passengers during a helicopter accident.
![3rd viz](https://github.com/Kaewin/phase1_project_group2/blob/main/Images/jonathan_vis.png)


# Conclusion

After analysing the data and forming our visualizations we are able to come to the conclusion of recommending the following for passenger and cargo transportation via plane, and the (testing) helicopter;

- The Boeing 727 make is the only Boeing make with three engines, and since three engine makes are the safest we will therfore reccommend that for passenger commercial planes.

- The Boeing 747 for cargo transportation becuase the Boeing 747 has a balance of both safety and space, a nose that opens, and also has the ability to carry passengers.

- And the Sikorsky S-92A helicopter for private enterprises since it holds the highest average of uninjured passengers during crashes. 


# References

“198e2ca2ac95198d0f1e4562e14119fb.Jpg (JPEG Image, 236 × 259 Pixels).” Accessed April 20, 2023. https://i.pinimg.com/236x/19/8e/2c/198e2ca2ac95198d0f1e4562e14119fb.jpg?nii=t.

“15622l.Jpg (JPEG Image, 1024 × 703 Pixels).” Accessed April 20, 2023. https://www.airpics.net/UserFiles/pics/large/PH-BFH-Boeing-747-400M-KLM-Royal-Dutch-Airlines/15650/15622l.jpg.admin. 

“Types of Aircraft Shipping Cargo and Types of Loads.” International Forwarding Association Blog (blog), October 24, 2019. https://ifa-forwarding.net/blog/air-freight-in-europe/types-of-aircraft-shipping-cargo-and-types-of-loads/. 

Bailey, Joanna. “The Global Cargo Workhorse: Why The Boeing 747F Is Winning.” Simple Flying, February 5, 2021. https://simpleflying.com/global-cargo-workhorse-747f/.

“Boeing 747.” In Wikipedia, April 15, 2023. https://en.wikipedia.org/w/index.php?title=Boeing_747&oldid=1149987448.

Business Jet Traveler. “Boeing BBJ 747-8i,” October 27, 2021. https://bjtonline.com/business-jet-news/boeing-bbj-747-8i.

“Reciprocating Engine.” In Wikipedia, March 14, 2023. https://en.wikipedia.org/w/index.php?title=Reciprocating_engine&oldid=1144567996.

“Sikorsky S-92.” In Wikipedia, March 28, 2023. https://en.wikipedia.org/wiki/Sikorsky_S-92.

Boeing 747 articles:
https://thefearofflying.com/articles/what-is-the-safest-commercial-airplane/
https://www.cliffordlaw.com/aviation-accidents-and-incidents/
https://www.reuters.com/business/aerospace-defense/boeing-deliver-last-747-saying-goodbye-queen-skies-2023-01-31/
https://www.businessinsider.com/50th-anniversary-boeing-747-queen-of-the-skies-passenger-flight-2020-1
https://www.afr.com/companies/transport/are-smaller-planes-more-dangerous-than-larger-planes-20190207-h1ayaf
https://en.wikipedia.org/wiki/Boeing_747_hull_losses

Boeing 727 article: https://aviatorinsider.com/airplane-brands/boeing-727/

