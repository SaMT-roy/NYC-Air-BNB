# NYC-Air-BNB

Context :-
Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present more unique, personalized way of experiencing the world. This dataset describes the listing activity and metrics in NYC, NY for 2019.

Content :-
This data file includes all needed information to find out more about hosts, geographical availability, necessary metrics to make predictions and draw conclusions.

Acknowledgements :-
This public dataset is part of Airbnb, and the original source can be found on this website. https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data


Inspiration :-

1) What can we learn about overall data and how do we visualize them?
2) What can we learn from predictions? (ex: prices and reviews)
3) How does the acccuracies varies across different classification models for availablity of airbnb's?

# STEPS
Data Analysis and Visualization

 Room Type :-
 
 ![image](https://user-images.githubusercontent.com/82521644/152035968-8575321f-f472-43d0-9da9-4ee7b1c07260.png)
 
  ![image](https://user-images.githubusercontent.com/82521644/152037567-29927694-4afb-49c7-9f52-bf7e8f6ffb02.png)


Price :- 

![image](https://user-images.githubusercontent.com/82521644/152036186-a8b23000-0035-4680-974d-eff73be4ef00.png)


Neighbourhood Location :- 

![image](https://user-images.githubusercontent.com/82521644/152037665-36d932f5-d44e-41f5-9d2a-46beb71dd1dd.png)



![image](https://user-images.githubusercontent.com/82521644/152037615-f43fba42-4669-4034-b514-93eba7fa54c8.png)





Availability :- 

![image](https://user-images.githubusercontent.com/82521644/152036475-de783cbf-2e70-4f4e-8bdd-7106c1484677.png)


Hypothesis Testing :


T-Test (Students T-Test)

Here, i performed t-test to check wheather the availablity of airbnb when taken a sample would change majorly with that of the overall average avaialblity of all airbnbs for airbnb's which are available for atleast more than a month.

Null hypothsis : Average availablity of Airbnbs would be same even if we take a sample of availablity data.

Alternate : Average availablity of Airbnbs would be different if we take a sample of availablity data.

   Statistics = -0.436, p = 0.663

Same distributions hence we fail to reject H0(Null Hypothesis)

Here we fail to reject H0 and hence we accept the null hypothesis itself that the average availablity of Airbnbs would be same even if we take a sample of availablity data.

.


Correlation :-

![image](https://user-images.githubusercontent.com/82521644/152037787-9e3fd78a-b113-4afc-a10c-4a0518186c93.png)



Classification of Room availability

![image](https://user-images.githubusercontent.com/82521644/152035436-5e363bf5-b481-4f2f-82ce-7650dbb0eb5a.png)
