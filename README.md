# **Taxi Demand Prediction New York City**
### Business Problem
For a given location in New York City, our goal is to predict the number of pickups in that given location. Some location require more taxis at a particular time than other locations owing to the presence schools, hospitals, offices etc. The prediction result can be transferred to the taxi drivers via Smartphone app, and they can subsequently move to the locations where predicted pickups are high.
### Objectives & Constraints
**Objectives**: Our objective is to predict the number of pickups as accurately as possible for each region in a 10min interval. We will break up the whole New York City into regions. Now, the 10min interval is chosen because in NYC one can commute 1 mile in approximately 10 minutes given the traffic is normal at that particular time.

**Constraints**:
- **Latency**: There is a medium latency requirement, because as a taxi driver he/she wants to know how many pickups in his/her region in few seconds or minute.
- **Interpretability**: There is a no interpretability required. As taxi driver gets good prediction result, he/she is not be much interested in the interpretability of the result.
- **Relative Errors**: Mean Absolute Percentage Error will be the relative error we will consider. The taxi driver will be more interested in the percentage error than the absolute error. Let say in some region the predicted pickups are 250, and if taxi driver knows that the relative error is 10% then he/she will consider the predicted result to be in the range of 225 to 275, which is considerable.
Our goal is to reduce the percentage error is low as possible.
### Source of Data
**Data can be downloaded from here:**
http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml

Here, we have used Jan- 2015 and Jan- 2016 data.
### Authors
• Hemant Tailor
### Acknowledgments
• Applied AI Course
