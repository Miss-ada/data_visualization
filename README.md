## data_visualization


#Summary

This data visualization is a map of the distribution of prosper loan data(Debt to Income Ratio, and Credit Score) across the United States. The color density in the map tells the median of debt to income ratio in different states. People living in east and west coast have lower debt to income ratio while people living in some states in midwest and south have higher debt to income ratio. Specifically, people in California and New York have the lowest Debt to Income Ratio, while people in Wyoming have the highest Debt to Income Ratio. In the interaction part, when you put your mouse over, you will see the median credit score in the selected state.The selected state is also highlighted. You can find that states with lower debt to income ratio do not necessarily have good credit score. 


#Design

The original data set contains over 80 variables and almost 100,000 instances. The variables include numerial and categorical data. I selected the two factors that I am interested in: the debt to income ratio and the range of the credit score. I am interested in looking at people in which state tend to use more money than their income and their credit score. Therefore, the way I am looking at these two factors is to group them by state. I transformed the data a little bit and find the median of debt to income ratio and the median of average credit score in each state. Then I used a us-state map to fit the data in. 
Since the color density can represent numerical degree and color red is usally used to represent "deficit financing"， I use red color to represent the high debt to income ratio and white to represent low debt to income ratio. 
I also designed an interaction so that my audience can find the median of credit score of the state to their interest after they find the debt to income ratio is extremely high or low. 


#Feedbacks

Feedback 1 - Ricky LU
Feedback point 1.Map is clear and fancy. The middle part is extremely red.
Feedback point 2. The visualization only contains Debt to Income Ratio. The information is not very rich,
Follow-up: I added a second variable, i.e. the median of credit scores of people in the state. 

Feedback 2 - Zhongliang Huang

Feedback point 1.Color red is really catching eyeball. 
Feedback point 2. The display is not accurate compared with the original data. Colorado looks lighter than California but actually most people in colorado have higher debt to income ratio than people in California. 
Follow-up: I aggregated the data by states and calculated the median of debt to income ratio and the median of credit score in R and use the new transformed data in the data visualization. 

Feedback 3 - Jialu Peng

Feedback point 1. The title is not clear enough to tell others what the map is about. 
Feedback point 2. It is easy to find information in California but not as much obvious in other states that I am unfamiliar with.

Follow-up: I changed the title to a clear one: Lower Debt to Income Ratio DOES NOT Guarantee Higher Credit Score in U.S.In addition, I added the names of states to the map.


#Resources
1. I consulted a Udacity mentor in regarding to find a us states geomap. He taught me to treansform a topojson file to the geojson file that I can use. 
2. I refered to this following github regarding the general structure of a html file and the way of binding data to json file. 
https://gist.github.com/michellechandra/0b2ce4923dc9b5809922
3. I refer to the following regarding setting color gradient in a map:
https://gist.github.com/wboykinm/dbbe50d1023f90d4e241712395c27fb3
4. I looked at Udacity forum when I met a problem or bug. 

Thank you for sharing and helping others to learn! 
