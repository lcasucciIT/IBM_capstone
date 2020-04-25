Capstone Project - Battle Of Neighborhoods

This is the capstone project for the IBM Data Science Professional Certificate


Summary

Now that you have been equipped with the skills and the tools to use location data to explore a geographical location, over the course of two weeks, you will have the opportunity to be as creative as you want and come up with an idea to leverage the Foursquare location data to explore or compare neighborhoods or cities of your choice or to come up with a problem that you can use the Foursquare location data to solve. If you cannot think of an idea or a problem, here are some ideas to get you started:

In Module 3, we explored New York City and the city of Toronto and segmented and clustered their neighborhoods. Both cities are very diverse and are the financial capitals of their respective countries. One interesting idea would be to compare the neighborhoods of the two cities and determine how similar or dissimilar they are. Is New York City more like Toronto or Paris or some other multicultural city? I will leave it to you to refine this idea.

In a city of your choice, if someone is looking to open a restaurant, where would you recommend that they open it? Similarly, if a contractor is trying to start their own business, where would you recommend that they setup their office? These are just a couple of many ideas and problems that can be solved using location data in addition to other datasets. No matter what you decide to do, make sure to provide sufficient justification of why you think what you want to do or solve is important and why would a client or a group of people be interested in your project.



Review criteria

This capstone project will be graded by your peers. This capstone project is worth 70% of your total grade. The project will be completed over the course of 2 weeks. Week 1 submissions will be worth 30% whereas week 2 submissions will be worth 40% of your total grade.

For week 1

A description of the problem and a discussion of the background.
A description of the data and how it will be used to solve the problem.

For week 2

A full report consisting of all of the following components:
Introduction where you discuss the business problem and who would be interested in this project.
Data where you describe the data that will be used to solve the problem and the source of the data.
Methodology section which represents the main component of the report where you discuss and describe any exploratory data analysis that you did, any inferential statistical testing that you performed, and what machine learnings were used and why.
Results section where you discuss the results.
Discussion section where you discuss any observations you noted and any recommendations you can make based on the results.
Conclusion section where you conclude the report.
A link to your Notebook on your Github repository pushed showing your code.
Your choice of a presentation or blogpost.



In this assignment, I will explore, segment, and cluster the neighborhoods in the city of Rome. I am interested in finding out what is the best location to open a modern wine bar.

For the Rome neighborhood data, a Wikipedia page exists that has all the information we need to explore and cluster the neighborhoods (Municipi) in Rome, the capital of Italy - see link 'https://it.wikipedia.org/wiki/Municipi_di_Roma'.

I will scrape the Wikipedia page and wrangle the data, clean it, and then read it into a pandas dataframe so that it is in a structured format.

I will convert addresses into their equivalent latitude and longitude values using the geocoder library. Also, I will use the Foursquare API to explore neighborhoods in Rome. I will use the explore function to get the most common venue categories in each neighborhood,check out their ratings,and the overall count of venues to understand the traffic.

I will then use this feature to group the neighborhoods into clusters.I will use the k-means clustering algorithm to complete this task.

Finally, I will use the Folium library to visualize the neighborhoods in Rome and their emerging clusters, and identify the best one to open a modern wine bar.
