Question
1) The random forest machine learnign method to predict what value globally?

- The learning mehtod examins the different covariates that are important to different LMIC and determines the similarities in their settlement as well as their differences. Used WIR to value the most important reason.

2) Describe in detail how random forest works

- The census data was applied first and then ontop of the newly segmented cesnus data different covariates are then tested. - - Each covariate would have its own trait such as protected natural areas, industrial, farms, roads, etc.
- Each covariate then produces a branch to a new covariate to be tested until a main cause is found
- Bagging method and out of bag method
- All the datasets used are bagged while the ones unuses ar out of bag
- These out of bag are tested for accuracy
- The bagged data is then tested. If trees are not grown they are considered OOB (out of bag data) and that data is held. Used as a training set to learn something new from this data\
- Data is taken from all over and testing and analysing multiple covariates. 

3) What is a adasymetric population allocation?

- The dasymetric population allocation has compiled census data into regions or administrative boundaries and gridding this data while layering on new data sets has allowed for more accurate compilation and analysis of the data. 
- Obseving specific values (geospatial data) then applying it to administrative borundires and applying pop density to these areas creating mores accurate grids. 
- All the values (densities added up to 1)

4) Which geospatial covariates proved to be the most important when predicting global cause of where humans reside?

- The WIR (weighted importance rank) allowed for the importnace of each covariate to be noted. 
- The most important notesd was the urban suburban extents, built env. And ubran/suburban proxies followed by climate/ecology/ topography
- Then 5th was transporation networks
- Urban/subruban and their proxies were predicted to be most importnat and ultimatley they were
