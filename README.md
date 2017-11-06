# Flight Delay Prediction

[Flight Delay Presentation.pdf](https://github.com/yaskyj/predict-flight-delays/blob/master/Flight%20Delay%20Presentation.pdf) - high level presentation of findings

[Flight Delays.ipynb](https://github.com/yaskyj/predict-flight-delays/blob/master/Flight%20Delays.ipynb) - An iPython notebook with markdown, graphs, and commented code.

Studies found that individual airline incidents took nearly 11 hours to resolve and $1,154 in missed work and extra expenses. Also, delays caused an estimated $245 million in lost work time. If businesses/business travelers (and personal travelers) could choose flights based on the additional dimension of probablity of flight delay, then hopefully a portion of the this loss can gained back.

In addition, in the United States, the Federal Aviation Administration estimates that flight delays cost approx. $20 billion yearly (2010 study). Knowledge of the factors leading to specific flight delays can help aviation authorities and airlines in taking necessary actions to ensure smooth operations.

As this was a contest held by CrowdAnalytix, a dataset was provided. It consisted of flight time performance data from 2014 and the first half of 2015 with variables such as schedule departure date & time, airline carrier, origin airport, scheduled arrival time etc. with the dependent variable of ARR_DEL_15 (a flight delayed more than 15 minutes is considered delayed).
Weather data was also provided by location and in 15 minute increments, however, this set is not complete with respect to all information in the flight time performance data.