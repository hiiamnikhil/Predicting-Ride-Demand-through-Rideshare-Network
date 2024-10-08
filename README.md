# IE434_Project
Predicting Demand through Ride share network. 
Hi this is the readme for a project which was done as a part of IE 434 Project for Fall 2023.   

The following are the team memebers:  

Name           
Nikhil Arora: [LinkedIn](http://www.linkedin.com/in/nikhil-arora-uiuc)  
Gaurav Bhandari: [LinkedIn](http://www.linkedin.com/in/gaurav-bhandari-52417411b)  
Sarath Saroj: [LinkedIn](https://www.linkedin.com/in/sarathsaroj/)  
Srushti Manjunath: [LinkedIn](https://www.linkedin.com/in/srushti-manjunath/)





The primary objective of this project is to develop a predictive model that accurately forecasts the destination stations of CITI Bike rentals in New York based on historical data. By understanding where a user is likely to dock their bike after renting, we intend to optimize bike allocation, ensuring that stations neither run out nor overflow with bikes. Also, commnent on location of nodes (Biking Stops/Biking Stations)

The data set discusses the  following parameters parameters: 
  - Date
  - Month
  - Day of the week
  - Start time
  - End time
  - Trip Duration (in seconds)
  - Start latitude/longitude
  - End latitude/longitude
  - Weather (daily summaries)
  - User Type (customer or member)
  - Year of Birth
  - Gender
    
We intend to run a GNN ( Graphical Neural Network ) for the New York, CITI bike, looking at the parametrers such as weathear, ridership at a paritucular time of the day, type of user and trip duration, and identify the suitbale locations for placement of bike. We might indetify any possible seasonality, trend and cyclic patterns on the data avaliable by performing time series analysis. If time permits we will also, run other models like RNN, LSTM.   

The stations can be represented as nodes in a spatial graph, with edges indicating a ride between two stations. The weight of these edges could be determined by the frequency of rides between two nodes (stations). A Graph Neural Network (GNN) could be utilized to model this problem, as it's designed to work with graph-structured data.








