# 59CRAWL

Theme 1: Towards a highly resilient Port Ecosystem

Demand-supply management within the container port ecosystem is crucial for its efficiency. Firstly, forecasting demand is essential, considering factors like shipping schedules, trade fluctuations, and seasonal variations. Secondly, managing the supply of available berths and terminal facilities is vital to handle incoming vessels and cargo. Thirdly, optimizing the allocation of resources, such as cranes and handling equipment, ensures smooth operations. Effective demand-supply management helps reduce congestion, minimize vessel waiting times, maximize asset utilization and enhance the overall throughput of the port. Striking the right balance between supply and demand is pivotal in maintaining the productivity and competitiveness of container ports.
​
How can digital solutions powered by data and AI optimize demand and supply to increase resilience of the port amidst global disruptions and risks?

## Our Solution

In the face of increasing global disruptions and risks, leveraging machine learning and advanced algorithms presents a transformative opportunity to enhance the resilience of our port operations. By harnessing the power of data and AI, we can optimize demand and supply dynamics, ensuring efficient resource allocation, minimizing disruptions, and fortifying our ability to adapt in an ever-changing environment. This strategic approach promises to bolster the port's competitiveness, reliability, and sustainability, ultimately safeguarding its vital role in global trade.

## Challenge: 
Delayed ships that may interfere with the routes of other ships and berths.

## Value: 
Improves efficiency of the port by optimizing allocation of resources such as berths and sea routes.

## Frontend

This frontend creates a GUI for the user to interact with the app.

The frontend provides multiple features namely:
1. Ingestor
  - Allows user to input data, or alternatively use initial dummy data
2. Simulator
  - Creates an interactive map for the user to visualize which ship should dock at which berth
3. Dashboard
  - A table for easy understanding of the entire data
4. ChatAI
  - LLaMa API to analyze and dissect the data using LLM models

- Ensure nodejs is installed

```
npm i # To install all necessary packages
npm run dev # To run server
```

## Backend

The backend handles multiple components of the app namely:
1. Machine Learning
  - Intakes data and spits out a predicted departure time based on past trends and delays
2. Ship docking algorithm
  - Arranges the data for to check if there are any overbooking of berths after expected delays and schedule ships as accordingly
3. ChatAI
  - Langchain CSV Agent to dissect information using pandas

- Ensure python is installed

```
pip install -r requirements.txt # To install required packages
cd app
python app.py # To run the program
```
