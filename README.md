# MIST-4610-Group-Project-2
Team Name: 29704 1

# Team Members
1. Jillian Bolgla [@jillianbolgla](https://github.com/jillianbolgla)
2. Conor Dillon [@cjdillon11](https://github.com/cjdillon11)
3. Brandon Hopper [@bhop19](https://github.com/bhop19)
4. Neha Panchal [@nehapanchal2001](https://github.com/nehapanchal2001)
5. Shrija Ramachandran Ganesh Mohan - [@shrija-27](https://github.com/shrija-27)
6. Alvin Vasanthakumar - [@alvinvasanth](https://github.com/alvinvasanth)

# Description of dataset:
Our group’s dataset provides data regarding car accidents in Montgomery Country within the state of Maryland. We found the dataset with the website provided (https://data.gov/) for our chosen topic. While the dataset contains numerous rows and columns with dimensions of various types, we are only interested in a select portion of information needed for our questions. Some of the specific information we are generally interested in is regarding the driver distractions, collision type, weather conditions, vehicle type, and the hour of the day. The dimensions mentioned are all bound to a string type except for hour of day which is of a numerical value data type. The data set also contains dimensions such as the date of the crash represented in a date/time data type, and other information such as where the accident occurred, possible injuries to the people in the vehicle, and the damage extent to the vehicle which are all represented by string types. By utilizing the multiple dimensions and combining them in different ways, we can gain more insight regarding the factors that surround many accidents occurring in Montgomery County. 

# Question 1:
### Q1: When conditions are clear, what time of day do most vehicle accidents occur when a cell phone was the reason behind the distracted driver? For those times, what percentage of total crashes reported were caused by a cell phone related distracted driver?
### Importance: 
This question delves into cell phone related accidents when the weather conditions are ‘clear.’ We felt this question was important because we classify these accidents as avoidable. If the driver had not been distracted by their phone, it’s safe to say the accidents would not have happened due to perfect weather.  We chose to represent this data as a bar graph, with the x axis displaying the percentage of total number of crashes reported and the y axis representing the time of day (military time). Within the bar graph, there are several different ways in which drivers can be distracted by their phones which are color-coded. These differing cell phone distractions include distraction by dialing, texting, talking/listening, and other cellular related disturbances. A bar graph can allow the viewer to identify patterns at a quick glance and build solutions around the results. It is important to note that our bar graph is represented with the highest percentage of cell phone related accidents at the top and descending from there. Depending on the intended analysis of the viewer, he can change the y axis to ascending or descending time. 

<img width="1051" alt="Screenshot 2023-12-05 at 4 17 38 PM" src="https://github.com/nehapanchal2001/MIST-4610-Project-2/assets/148079624/0ff1a34d-1801-45e6-b1ed-dcbdc18c03ae">

### Analysis: 
To answer the proposed question, we draw our attention to the longest bar graph, which is the number 18. This translates to 6 PM with 10.5% of all accidents being phone related. The breakdown is as follows: 3.68% of accidents were caused by talking/listening to the phone, 0.92% were caused by texting, 1.1% caused by dialing, and 4.48% caused by other cell phone distractions. The evening is primarily when the workforce is on their way home from work; people may be communicating with their spouses, parents, children, etc. Marketers could use this information to raise more awareness for driving safety, especially at busy traffic times. In addition, a company could call for more in depth research about the ‘other cell phone distractions.’

# Question 2:
### Q2: The dataset displays the driver and car information for the person at fault. Which types of cars are correlated with which types of accidents? How many of each accident type are there, and what is the average speed limit for each type?

### Importance:
This question is interesting because it provides insight into the correlation between the vehicle type and the relation between the types of accidents it was involved in. Different trends can be explored such as, “Correlations between specific cars and the type of accident” or “The effect of the age of a car on the likelihood of an accident.” This can assist automakers in determining which vehicles are safer and which ones require improvement. It can also provide valuable insight to individuals looking to purchase a car. They are able to investigate whether a particular safety feature should be implemented in a car that experiences a specific type of accident more frequently. For example, if a car is prone to an accident labeled “Same Direction Left Turn” automakers could incorporate blind spot detectors to prevent this from occurring as frequently. Some trends that can stem from this question revolve around specific cars linked to more severe accidents or cars that are more reliable opposed to cars that may pose a higher danger. This relates to the data because the dataset contains information amongst all cars regardless make, model, or year. 

<img width="1012" alt="Screenshot 2023-12-05 at 4 18 06 PM" src="https://github.com/nehapanchal2001/MIST-4610-Project-2/assets/148079624/dd362a0d-9e84-4d6e-8b98-b3271081a8f5">

### Analysis:
In our data analysis, we discovered that passenger cars experienced the highest number of collisions. Using a heat map was helpful to quickly identify the frequency of accidents occurring and interpret the patterns shown. Among passenger cars, the most frequent type of collision was same direction read ending, followed by collisions with a straight movement angle as the second most common. This information is valuable for individuals purchasing cars, as it highlights the importance of considering safety features offered by different brands of passenger cars. For families traveling together, this awareness is essential. It pushes passenger car owners to adjust their driving habits, emphasizing the need for increased attentiveness and maintaining a safe distance between vehicles. Additionally, drivers can make informed decisions about their insurance policies based on the collision frequency data, providing further incentives for safer driving practices.

# Manipulation applied to the data set for analysis:
There were two manipulations we decided to perform on the data set to allow easier access to the information that was critical for our analysis. In the exported data set, the date and time of the accident were listed in one column. We decided it would be best to separate the date and time column, essentially making each their own individual columns. Additionally, we had to alter the time column. The time column was changed to display time by the hour. With this manipulation, we were able to analyze crashes that occurred at different hours. We also had to filter the data to only display clear conditions and distractions related to a cell phone only to analyze the first question. Without this manipulation we would have a much larger dataset and unnecessary information would be displayed.  

# Tableau packaged workbook
The packaged workbook containing the visualizations shown above is attached to this repository. 
Attached in ELC due as we were unable to upload it in Github.
