# Flight Delay Prediction

##### 1. What is the problem you want to solve?

Predict whether a flight will be delayed or on time.

##### 2. Who is your client and why do they care about this problem? In other words, what will your client do or decide based on your analysis that they wouldn't have otherwise?

Studies found that individual airline incidents took nearly 11 hours to resolve and $1,154 in missed work and extra expenses. Also, delays caused an estimated $245 million in lost work time. If businesses/business travelers (and personal travelers) could choose flights based on the additional dimension of probablity of flight delay, then hopefully a portion of the this loss can gained back.

In addition, in the United States, the Federal Aviation Administration estimates that flight delays cost approx. $20 billion yearly (2010 study). Knowledge of the factors leading to specific flight delays can help aviation authorities and airlines in taking necessary actions to ensure smooth operations.

##### 3. What data are you going to use for this? How will you acquire this data?

As this was a contest held by CrowdAnalytix, a dataset was provided. It consisted of flight time performance data from 2014 and the first half of 2015 with variables such as schedule departure date & time, airline carrier, origin airport, scheduled arrival time etc. with the dependent variable of ARR_DEL_15 (a flight delayed more than 15 minutes is considered delayed).
Weather data was also provided by location and in 15 minute increments, however, this set is not complete with respect to all information in the flight time performance data.

##### 4. In brief, outline your approach to solving this problem (knowing that this might change later).

The flight data will be explored for trends and data manipulation to fix missing values and create new features will be performed. The weather data will be grouped and merged with the flight data based on time and origin.

After the exploration and manipulation, a model will be built and evaluation will be done using area under the curve.

##### 5. What are your deliverables? Typically, this would include code, along with a paper and/or a slide deck.

An iPython notebook with markdown, graphs, and commented code.