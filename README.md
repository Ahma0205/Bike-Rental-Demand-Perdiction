# Bike-Rental-Demand-Perdiction
Data cleaning &amp; feature engineering &amp; different prediction models &amp; model evaluation
Project Proposal
 
Description:
Prediction of the number of bicycles rented in an hour of a day in the Seoul Bike Sharing System based on different weather conditions and holiday information in Seoul
Group members:
Mohammad Ahmadi, Zachary Huntley, Anurag Singh
Dataset Description:
The dataset is downloaded from https://archive-beta.ics.uci.edu/ website that provides dataset for education goals. The data set contains the number of bicycles rented in an hour for each day from 1.12.2017 to 31.11.2018. the weather condition also for each hour are specified in terms of Temperature(°C), Humidity(%), Wind speed (m/s), Visibility (10m), Dew point temperature(°C), Solar Radiation (MJ/m2), Rainfall(mm), Snowfall (cm) and Seasons. Holidays are specified for each day. As there were some days that the Seoul Bike Sharing System  was unable to provide service and no vehicle was rented during these days, they are shown in the column of Functioning days.
Project Summary:
Ddareungi (Korean: 따릉이) is Seoul's bike sharing system, which was set up in 2015. It is also named Seoul Bike in English. After a few months, the number of stations reached 150 and 1500 bikes were made available. In 2016, the number of stations has increased steadily to cover new districts. As of July 2016, there were about 300 stations and 3000 bikes available (Wikipedia).
A major problem that always acts as a building block for expansion of these systems is the cost. High cost of maintenance and renewal of the bicycles directly result in high rent cost from the customer or high budget from municipalities that prevent popularity of such an environment-friendly system in cities.  Besides, inaccessibility is another problem that people face in cities that have such a system. It means that stations do not have enough bicycles in a specific hour to cover the demand. It directly affects the popularity of systems and forces people to have their own bicycle or another alternative to make their everyday journey.
Bicycle system provides users to rent a bike from one station, where users can ride and then return to another station or in the newer form of renting, people can rent a bicycle from anywhere they found these bicycles and leave them wherever they want.  In both systems, providers should facilitate relocating of abandoned bicycles into the stations. This relocation includes collecting, transporting and placement of bicycles in the specific station. This cycle obviously needs infrastructure and human resources that are two major sources of the cost. So, predicting the number of bicycles needed every day can minimize the cost of relocations.
Also, minimizing the number bicycles in the stations can protect these vehicles from different weather situations and result in the decrease in maintenance cost as well as increase in the life span of them that result in direct revenue for the systems.
Eventually, predicting the number of bicycles needed on an hourly basis each day can help the system balance supply and demand to better serve the customers.
As the weather condition is a very important factor in the use of bicycles, we try to forecast the number of bicycles needed each day based on it. Also 
 
Methodology:
Label variable: rented bike count
Features: Temperature(°C), Humidity(%), Wind speed (m/s), Visibility (10m), Dew point temperature(°C), Solar Radiation (MJ/m2), Rainfall(mm), Snowfall (cm), Seasons, Holidays and Functioning days. 
Libraries: Panda, Numpy
Step to follow:
Data preparation (cleaning, transformation, reduction)
Feature engineering (Normalization)
Splitting Data to Training and test dataset
Modeling
Training the model
Tuning and optimizing the model
Library from Python:
Pandas
NumPy
Matplotlib
TensorFlow
Scikit Learn
