# Park-Usage-Exploration

## Data 

The data is obtained through AWS S3 and contains:

* Activity data of park users, granularity in minutes, GBs in size
* The layout of the system of public parks of the city of Roanoke, as shape files

## What I did

* I devised and evaluated two ways to count the number of visits to public parks, using the tracking data of park users
* I created graphs to visualize park usage over time in day, over day in week, and over the length of time recorded in the data set
* I ranked the parks and related facilities by attractiveness, and found that park attractiveness varied throughout the day, and that some parks were good at drawing people in, but bad at keeping people in their facilities

## What I found

1. Parks share a common pattern in traffic: There is a peak in traffic right before work, at 8AM, and another peak during lunchtime, at 12PM *(Chart 1)*.

2. There is a seasonal trend in park traffic: Parks tend to be more crowded during the weekend, and empty during holidays *(Chart 2)*.

3. Mill Mountain Park is the most popular park by far, as each visitor tends to spend 2 hours in the park. Bennington Park takes second place, with each visitor spending an average of 1.5 hours in the park. *(Chart 3)*.

4. The top most frequent park visitors tend to spend their time at very specific places, at the centor of the park *(Chart 4)*.

## Visualizations

**Chart 1: Park Visit by Hour**

<img src="https://user-images.githubusercontent.com/20875827/107004523-43a09800-6743-11eb-9740-73306502d8f8.PNG" width="1200" height="600">

**Chart 2: Park Traffic by Date**

<img src="https://user-images.githubusercontent.com/20875827/107003947-6aaa9a00-6742-11eb-9c99-cddb11787106.PNG" width="400" height="300">

**Chart 3: Park Average Visit Length in Minutes**

<img src="https://user-images.githubusercontent.com/20875827/107004117-ae050880-6742-11eb-9200-781d02dcbf57.PNG" width="600" height="600">

**Chart 4: Average trajectories of the most frequent visitors**

<img src="https://user-images.githubusercontent.com/20875827/107003379-86617080-6741-11eb-9002-b0dff02477e0.PNG" width="400" height="400">
