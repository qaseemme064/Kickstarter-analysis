
# KICKSTARTER-ANALYSIS
# Kickstarting with Excel

## **Overview of Project**
Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset I have visualized campaign outcomes based on their launch dates and their funding goals.

### **Purpose**
The purpose of the analysis is to explain to louise through visualization about the outcomes of the theater by launch date and the outcomes based on goals for plays

---


## **Analysis and Challenges**
First of all I have started working on the ***kickstarter sheet*** and extracted ***year*** from  the date creation  and used hidden option to hide all the unneccary data that was not required for this report(e.g  currency, spotlight percentage fund etc) to have a good picture of data that requires for the challenge in front.

Now my kickstarter sheets looks like below in very simplified form:

![Screenshot 2022-01-02 030003](https://user-images.githubusercontent.com/96033163/147889068-a9c8d0e7-4029-4e07-b785-ba4b225cade0.jpg)



Then I have used pivot table to make a desired table that was for theater outcomes based on launch date. 

### **Analysis of Outcomes Based on Launch Date***
So in whole year there was a total of 4064 outcomes and then after selecting only theater from parent category we got a toal of 1369 theaters
So from the below graph we can see that the number of times the theater was successful in mosly in May which is the peak and the lowest failed campaign is in November. 
By looking at the trend the success rate is mostly high than the failed campaign 

![theater outcomes vs launch](https://user-images.githubusercontent.com/96033163/147889077-ca080f01-8596-4a84-863d-00e98e605781.png)


&nbsp;

The second analysis is for outcomes based on goals


### **Analysis of Outcomes Based on Goals**
Based on graph that we got from our detailed data between goals and percentages of successful, failed and canceled we can conclude that 
- around 50% of the time success rate of achieving goals is mostly between $0 to $45000.
- There is no success for $45000 to $49000 
- Less than $1000 campaign has the highest success rate 
- The campaigns that was between 25000 to 29000 has the highest failed rate 

![theater outcomes vs launch](https://user-images.githubusercontent.com/96033163/147887825-435493a5-b9ea-4d2f-ad4e-d424f3b39295.png)


&nbsp;


### **Challenges and Difficulties Encountered**
Pivot table was very easy to make. The only challenge was in making table for outcomes based on goals. Need to be vey focused in using formula of countifs. 

---

## **Results**

1. ***What are two conclusions you can draw about the Outcomes based on Launch Date?***
    - May month has the highest success rate
    - Cancelation rate is very low

&nbsp;

2. ***What can you conclude about the Outcomes based on Goals?***
    - around 50% of the time success rate of achieving goals is mostly between $0 to $45000.   
    - There is no success for $45000 to $49000. 
    - The campaigns that was between 25000 to 29000 has the highest failed rate 

&nbsp; 

3. ***What are some limitations of this dataset?***
   - I don’t see any limitations specifically for this challenge

&nbsp;

4. ***What are some other possible tables and/or graphs that we could create?***
    - In theater outcomes we could create a graph for years to see the previous year trends of campaign, in the same way we could create a quartile graph as well

---
