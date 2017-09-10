## data_visualization


#Summary
This data visualization is a map of the distribution of prosper loan data across the United States. The color density in the map tells the median of debt to income ratio in different states. In the interaction part, when you put your mouse over, you will see the median credit score in the selected state.The selected state is also highlighted.  


#Design
The original data set contains over 80 variables and almost 100,000 instances. The variables include numerial and categorical data. I selected the two factors that I am interested in: the debt to income ratio and the range of the credit score. I am interested in looking at people in which state tend to use more money than their income and their credit score. Therefore, the way I am looking at these two factors is to group them by state. I transformed the data a little bit and find the median of debt to income ratio and the median of average credit score in each state. Then I used a us-state map to fit the data in. 
Since the color density can represent numerical degree and color red is usally used to represent "deficit financing"， I use red color to represent the high debt to income ratio and white to represent low debt to income ratio. 
I also designed an interaction so that my audience can find the median of credit score of the state to their interest after they find the debt to income ratio is extremely high or low. 


#Feedback
1. What do you notice in the visualization?
My audiences show positive attitude when they first saw my map. They found it a good strategy to tell a story about the differences between states. They say The color I selected is a good choice. 

2. What questions do you have about the data?
One reader points out that the data I am using is not accurate because I did not aggregate the data and use the original data instead. So the map actually shows the debt to income ratio of the first matched person in a state instead of the median of all people in that state. In addition, they feel confused because I did not add a title to the map or a title to the legend. 
I did not represent the credit score in the first draft as well.

3. What relationships do you notice?
The states with more red density (or debt to income ratio) often have higher credit score. That is quite surprising to me as well because I thought people should have higher credit score if they have lower debt to income ratio. However, I checked the data and confirmed states with higher credit score actually have high debt to income ratio. Probably it is because people who have higher credit score are guaranteed to have more debt.   

4. What do you think is the main takeaway from this visualization?
One audience lives in California and he finds the debt to income ratio there is quite low, even though their living expense is high. Other audiences find the map a good way to tell a story because it is very clear and fancy. 

5. Is there something you don’t understand in the graphic?
When reading the first data visualization without legend, they do not understand what the density means. I corrected it and also add a text to the map.  


#Resources
1. I consulted a Udacity mentor in regarding to find a us states geomap. He taught me to treansform a topojson file to the geojson file that I can use. 
2. I refered to this following github regarding the general structure of a html file and the way of binding data to json file. 
https://gist.github.com/michellechandra/0b2ce4923dc9b5809922
3. I refer to the following regarding setting color gradient in a map:
https://gist.github.com/wboykinm/dbbe50d1023f90d4e241712395c27fb3
4. I looked at Udacity forum when I met a problem or bug. 

Thank you for sharing and helping others to learn! 
