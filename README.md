
# Data Visualization.

# Overview:

This project is divided into two major parts. In the first part, you will conduct an exploratory data analysis on a dataset of your choosing. You will use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part should be structured, going from simple univariate relationships up through multivariate relationships, but it does not need to be clean or perfect. There is no one single answer that needs to come out of a given dataset. This part of the project is your opportunity to ask questions of the data and make your own discoveries. It’s important to keep in mind that sometimes exploration can lead to dead ends, and that it can take multiple steps to dig down to what you’re truly looking for. Be patient with your steps, document your work carefully, and be thorough in the perspective that you choose to take with your dataset.

In the second part, you will take your main findings from your exploration and convey them to others through an explanatory analysis. To this end, you will create a slide deck that leverages polished, explanatory visualizations to communicate your results. This part of the project should make heavy use of the first part of the project. Select one or two major paths in your exploration, choose relevant visualizations along that path, and then polish them to construct a story for your readers to understand what you found.

## Step 1.1: Choose your Dataset:

- Ford GoBike System Data

due to the large amount in the data of each month I couldn't upload them. It can be reached in the link below it's all 2019 files. Please Download the files and save them in 'Data' folder in order to run this code.
https://s3.amazonaws.com/baywheels-data/index.html

# File names are as follows:
- 201901-fordgobike-tripdata.csv.zip
- 201902-fordgobike-tripdata.csv.zip
- 201903-fordgobike-tripdata.csv.zip
- 201904-fordgobike-tripdata.csv.zip
- 201905-baywheels-tripdata.csv.zip
- 201906-baywheels-tripdata.csv.zip
- 201907-baywheels-tripdata.csv.zip
- 201908-baywheels-tripdata.csv.zip
- 201909-baywheels-tripdata.csv.zip
- 201910-baywheels-tripdata.csv.zip
- 201911-baywheels-tripdata.csv.zip
- 201912-baywheels-tripdata.csv.zip

# The Data
## Each trip is anonymized and includes:
- **Trip Duration**
- **Start Time and Date**
- **End Time and Date**
- **Start Station ID**
- **Start Station Name**
- **Start Station Latitude**
- **Start Station Longitude**
- **End Station ID**
- **End Station Name**
- **End Station Latitude**
- **End Station Longitude**
- **Bike ID**
- **Distance_km**
- **day**
- **Bike Share for All Trip** 
>which tracks members who are enrolled in the <a herf=https://www.lyft.com/bikes/bay-wheels/bike-share-for-all >Bike Share for All</a> program for low-income residents.
- **User Type**
>(Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)


# Step 1.2: Explore Your Data
It’s time to get to the interesting bits. Explore your data and document your findings in a report. The report should briefly introduce the dataset, then systematically walk through the points of exploration that you conducted. You should have headers and text that organize your thoughts and findings. Visualizations in this part of the project need not be completely polished: this is just your own exploration at this point. However, you should still make sure that you adhere to principles of using appropriate plot types and encodings so that accurate conclusions can be drawn, and that you have enough comments and labeling so that when you return to your work, you can quickly grasp your analysis steps.

If you use a Jupyter Notebook for this step of the project, don’t forget to export the notebook as an html file for the project submission.

Step 2.1: Document your Story
At the end of your exploration, you probably have a bunch of things that you’ve discovered. Now it’s time to organize your findings and select a story that you will convey to others. In your readme document, you should summarize your main findings and reflect on the steps you took in your data exploration. You should also lay out the key insights that you want to convey in your explanatory report as well as any changes to visualizations, or note new visualizations that will be created to bridge between your insights.

# Step 2.2: Create your Slide Deck
Follow the plans you laid out in the previous step and create a slide deck with explanatory data visualizations to tell a story about the data you explored. You can start with code that you used in your exploration, but you should make sure that the code is revised so that your plots are polished. Make sure that you also pay attention to aspects of design integrity in your revisions.

# Summary Of Findings

-  Univariate Exploration: 

1. the majority in the dataset are not enrolled in "Bike Share for All Program" and the user_type majority are subscriber.
2. The majority of bike ride are in the weekdays mostly Thursday 17.3% whereas on Saturday 9% and Sunday 8.1% as we can see a major drop of bike ride users and in terms of duration they fall between 3-7 min. Most distance are  between 0.6-1.5 km.


- Bivariate Exploration:

 1. The higher the station id_name the more consistence the bikers will ride their bikes in terms of distance from slightly below 1 km up to 3.5 km.
 2. We noticed that the distance of bike users is higher if the user started in San Francisco Building (Harry Brings Plazza).


Multivariate Exploration :

1. Trip Duration in different months taking into account the user type, now we can see the Customer have much higher trip duration in average.
2. There is not a single user who's a customer and enrolled in bike for all program in 2019.


#  Key Insights.

Many visualizations on (Ford GoBike System Data characteristics will be created to study their relationship on duration_min The main characteristics are duration_min,distance_km,day,bike_share_for_all_trip,start_time, start_station_name, start_station_name , user_type  ,start_station_latitude , start_station_longitude , end_station_latitude , end_station_longitude  to help my go through the investigation part in our dataset
