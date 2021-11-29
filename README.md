# surfs_up
UMN Bootcamp Module 9

## Overview of the Analysis
Using the sqlalchemy library and flask, I was able to analyse the weather data contained in 
the hawaii.sqlite database.  The analysis needed was to determine the temperature patterns
for W. Avy, a surf shop, to assess the sustainability of having the surf shop open year round.

## Results
In looking at the temperature differences between June and December, we see the following sum-
mary statistics:

### June

![image](https://user-images.githubusercontent.com/91292960/143792180-5b34418d-5605-4d86-ac4c-51d33f7b822e.png)

### December

![image](https://user-images.githubusercontent.com/91292960/143792231-011008d6-ffa9-4827-834b-9efa601e3620.png)

From this we can see that:
- June is averages nearly 4°F warmer than December.
- June's maximum temperature is 2°F warmer than December.
- June's minimum temperature is 8°F warmer than December.

## Summary
Given the data listed above we can see that temperature, while consistantly warmer in June,
is not appreciably different than in December.  The feasibilty based solely on this data
looks promising for a being open year round.  

That said, temperature alone should not be the determining factor.  Further analysis on 
weather data, specifically precipitation and wind speed, should be completed to cement
the analysis and recommend if being open year round is sustainable.
