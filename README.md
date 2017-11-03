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

After removing the outliers, we can see that 2014 actually had the highest number of security breaches rather than 2016 (what we previously believed). Because 2014 is vastly greater, we will focus on 2014 and the surrounding years to see if we can still support our claim.

![image](https://user-images.githubusercontent.com/32119820/32310388-1d528e5a-bf4f-11e7-9d08-4aeb21102430.png)

## 1st Iteration:

![image](https://user-images.githubusercontent.com/32119820/32310653-280c0b08-bf51-11e7-93b3-d290caff6f27.png)

In the above graph, the gray area shows the year that had the most average security breaches. During that time, closing prices kept increasing and was much higher than the previous year. This shows us that the financial markets do not punish companies for security breaches.

## 2nd Iteration:

![image](https://user-images.githubusercontent.com/32119820/32360362-51abb938-c012-11e7-97f4-36565c398a95.png)

This graph is similar to the 1st iteration except this one has updated data. Since we are excluding outlier security breaches for Anthem, Equifax and Heartland, it will be a good idea to also exclude their corresponding stock prices. After the filter was added to exclude those 3 companies, there was a slightly steeper decrease in stock prices. In Q2 of 2014, we see this decrease in closing prices.


--------------


Context
This is a redesign of lab session 3. 

Objectives
Redesign YOUR result of lab session 3. 

Steps
Critique your visualization
Develop a roadmap for improvement
Improve your visualization
Explain how you have improved your visualization

Caution
Please ensure the reproducibility of your results.
You may add new data as you see fit.
Be creative!

