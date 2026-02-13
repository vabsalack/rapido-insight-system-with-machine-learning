### project objective
1. predict ride outcomes before trip start
2. estimate accurate fares dynamically
3. identify high rist customers and drivers
4. enable data-driven operational interventions

## business use cases
1. use case 1: reduce cancellations by 20%
   1. customer cancels ride because of 
      1. before booking
         1. time of travel
         2. cost of travel
      2. after booking
         1. rapido side
            1. captain allocation
            2. captain behaviour
            3. vehicle maintaince
            4. changes in time of travel
            5. changes in cost of travel
         2. customer side
            1. change in plans
            2. found cheap ride in other platforms

2. use case 2: improve ETA accuracy
   1. tune a model to predict correct ETA
3. use case 3: dynamic pricing
   1. tune a model to predict correct fare for ride
4. use case 4: driver reliability scoring
   1. does past records of driver shows, will he/she make it on time?
   2. does past records of driver shows, good behaviour towards users?

## models to build and it's objective

### model 1
1. obj: ride outcome prediction
2. type: multi class classification
3. 3 labels: completed, cancelled and Incomplete
4. independent variables:

### model 2
1. obj: fare prediction
2. type: regression
3. target: predict the expected booking fare prior to trip confirmation
4. independent variables:
   1. distance
   2. traffic & weather
   3. time of day
   4. vehicale type
   5. surge dynamics

### model 3
1. customer cancellation risk
2. type: binary classification
3. target: cancel or continue
4. independent variables:
   1. historical cancellation rate
   2. past ratings
   3. peak-time behaviour
   4. pricing sensitivity

### model 4
1. driver delay prediction
2. type: binary classification
3. target: delayed or on time
4. independing variables
   1. past delay history
   2. traffic exposure
   3. acceptance behaviour