# Lab 3 Redesign

In Lab 3 (https://github.com/eharada/Data_Viz_Lab_3), I created a visualization that shows the aggregate data breaches per year and the corresponding stock prices. In the visuals, it is visible that financial markets do not punish security breaches. 

![image](https://user-images.githubusercontent.com/32119820/32188901-1727a346-bd77-11e7-9c63-5dcfd25ebfe9.png)
![image](https://user-images.githubusercontent.com/32119820/32188934-31e42286-bd77-11e7-8382-5245f31221c8.png)

The advantage of this graph is that the audience is able to see when the data breaches occurred and the overall trend of the stock prices. However, it is confusing to see two graphs and the audience may not know how the graphs are related if it's not explained to them. 

<br/>

For the redesign, I'm planning on having one graph that supports the claim that financial markets do not punish companies after security breaches. Additionally I'm going to exclude outliers for data breaches as those skew the data. 
<br/>
Below are the outliers that will be excluded.

![image](https://user-images.githubusercontent.com/32119820/32310030-c32154d6-bf4c-11e7-872a-7d05cfbf67ca.png)

After removing the outliers, we can see that 2014 actually had the highest number of security breaches rather than 2016 (what we previously believed). Because 2014 is vastly greater, we will focus on that and the surrounding years to see if we can still support our claim.

![image](https://user-images.githubusercontent.com/32119820/32310388-1d528e5a-bf4f-11e7-9d08-4aeb21102430.png)

## 1st Iteration:

![image](https://user-images.githubusercontent.com/32119820/32310653-280c0b08-bf51-11e7-93b3-d290caff6f27.png)

In the above graph, the gray area shows the year that had the highest average for security breaches. During that time, closing prices kept increasing and was much higher than the previous year. This shows us that the financial markets do not punish companies for security breaches.

## 2nd Iteration:

![image](https://user-images.githubusercontent.com/32119820/32360362-51abb938-c012-11e7-97f4-36565c398a95.png)

This graph is similar to the 1st iteration except this one has updated data. Since we are excluding security breaches for Anthem, Equifax and Heartland, it will be a good idea to also exclude their corresponding stock prices. After the filter was added to exclude those 3 companies, there was a slightly steeper decrease in stock prices. In Q2 of 2014, we see this decrease in closing prices.


## 3rd Iteration:

In the third iteration, I want to focus on 2014 as that was the year that had the most security breaches. This way we could see more granular details to see if stock prices plummeted around those security breaches. In the graph below, we could see that Home Depot, Community Health Systems and Staples had security breaches in 2014. 

![image](https://user-images.githubusercontent.com/32119820/32402457-b124b73c-c0e1-11e7-8dde-f0470725c3b2.png)

In the following links we could see that the security breaches occurred in April, June and September.

http://money.cnn.com/2014/09/18/technology/security/home-depot-hack/index.html

https://securityintelligence.com/4-5-million-patient-records-stolen-in-chs-data-breach-whats-next/

http://fortune.com/2014/12/19/staples-cards-affected-breach/

In the graph below, the months with the security breaches are in light gray. During those months of security breaches, the stock prices mainly increased or remained relatively stable. 

![image](https://user-images.githubusercontent.com/32119820/32402446-88c8a456-c0e1-11e7-9967-e16f4ec9f334.png)

In the above visual, I included stock prices for all companies (except the outliers) which included too much data. This made the data more flatlined so we couldn't really see the shifts in closing prices. In the final version I am only going to include stock prices for the three companies with the security breaches in 2014 and am going to shorten the number of months that are visible.

-----------
## Final Version:

![image](https://user-images.githubusercontent.com/32119820/32407913-ff3b271a-c14c-11e7-90c0-93fbdc402465.png)

In the final version, I only included the stock prices for the affected companies (Community Health Systems,Home Depot and Staples). In addition I am looking at the closing stock prices per week rather than per month. This allows us to see the peaks and troughs more clearly. The gray bars indicate the security breaches for the 3 companies. During this time we could see that the stock prices do significantly decrease but it starts to increase after a few weeks. 

This confirms our previous beliefs that the financial markets do not punish the financial markets. Although stock prices may dip temporarily, it will always bounce back fairly quickly.

<br/>
This redesign improved the original data visualization as it proves more clarity. The original visual was confusing to the audience because there were two graphs that needed to be explained. However now we are able to view one graph that tells a better story of market security despite security breaches.

## Tableau Public Link:
https://public.tableau.com/profile/elena.harada#!/vizhome/Lab_7_0/Sheet13?publish=yes

