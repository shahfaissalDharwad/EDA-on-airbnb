# Airbnb Data Analysis
![203228331-cddcebaa-8566-434a-80a6-6681514a55b7](https://user-images.githubusercontent.com/96904369/203539899-c7f629c3-f91c-4b65-85a1-ab119589b9d0.png)

# Business Problem
- The objective of this capstone is to do EDA on the given dataset and find out the insights from it.
# Understanding the problem statement
- This is the most important part of any analysis as we must understand the needs of a customer/business owner for what task they require analysis on and work as per their requirements. The main motive was to analyze the given dataset to provide the company with the information that will help to analyze their business and take strategically important decisions to further grow their business to new heights.
# Know your Data
Dealing with a huge data set is a time-consuming part. In this dataset, we are provided with 16 features and around 49k data instances. To understand the dataset we are working on, initially, we find the important columns and the data using “head()” and “info()”. To minimize the workload and efforts we must have to distribute data and analyze the content first.
# Handling missing values
- Removing the unnecessary part while handling missing values and data cleaning. During the analysis, we found that there are four columns with null values. To minimize the errors, we replaced the numeric columns having null values with 0 using the “fillna()” function.
# Univariate and Multivariate analysis
- To find out the most frequently searched words, we first removed all the stop-words using the nltk dictionary and then using wordcloud we tried to display frequently searched words in an image view. Then we analyzed the hosts based on the number of properties owned by them and based on the area and Airbnb listings. Then we analyzed room types based on area, and the price of the room using price categorization as well.

- Based on the price categorization, we tried to find out the sentiment of the people across the different neighborhood groups, where we found that most of the people preferred affordable rooms over cheap and expensive in Manhattan and Brooklyn whereas, for the bookings in Queens and Bronx, the relation was reversed.
- We used longitude and latitude to demonstrate the geographical distribution of properties across the places.
- We tried to get the correlation between different variables for which we plotted a correlation plot as well. All the analysis was accompanied by graphical representation.
- We tried to plot a distribution plot for different neighborhood groups in terms of prices. This distribution and density of prices were in line with the predictions. Manhattan proved to be the costliest as compared to other groups. Moreover, it proved to be the place with the highest number of bookings.

# Conclusion
After the analysis, we concluded that this analysis will help the company to decide in which areas they are leading or lagging, where they need improvisation, and what necessary changes they need for better functionality of their business. As the analysis was done based on price category, different locations, hosts, and room types, the company will be able to decide which type of room is preferred in what area and strategize accordingly for the betterment of their customer satisfaction and business growth.

# Execution Instruction
The order of execution of the program files is as follows:

1) spam_detector.py

First, the spam_detector.py file must be executed to define all the functions and variables required for classification operations.

2) train.py

Then, the train.py file must be executed, which leads to the production of the model.txt file. At the beginning of this file, the spam_detector has been imported so that the functions defined in it can be used.

3) test.py

Finally, the test.py file must be executed to create the result.txt and evaluation.txt files. Just like the train.py file, at the beginning of this file, the spam_detector has been imported so that the functions defined in it can be used.
