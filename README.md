# Smart-city-traffic-flow-Simulator

 Smart City Traffic Flow Simulator

 Project Overview

The Smart City Traffic Flow Simulator is a Python-based project that simulates vehicle traffic across 10 city junctions over 30 days.

It uses NumPy to generate hourly vehicle counts using a Poisson distribution, models morning and evening rush-hour traffic, identifies peak congestion periods, and visualizes traffic patterns using heatmaps.

 Project Objectives

* Simulate traffic for 30 days across 10 junctions.
* Generate hourly vehicle counts (24 hours per day).
* Model morning and evening rush-hour patterns.
* Identify peak traffic hours and busiest junctions.
* Visualize traffic patterns using heatmaps.
* Compare loop-based and vectorized NumPy performance.

 Technologies Used

* Python
* NumPy
* Matplotlib
* Google Colab

 Project Features

1. Traffic Simulation: Generates 7,200 junction-hour records using NumPy’s Poisson distribution.
2. Rush-Hour Analysis: Models morning and evening traffic peaks.
3. Data Aggregation: Uses NumPy sum() and mean() functions.
4. Peak Traffic Detection: Uses argmax() to identify peak hours and busiest junctions.
5. Data Visualization: Displays traffic patterns using a heatmap.
6. Performance Analysis: Compares loop-based and vectorized implementations.

 Project Structure

Smart-City-Traffic-Simulator/
│
├── Smart_City_Traffic_Flow_Simulator.ipynb
│
└── README.md

 How to Run the Project

1. Clone or download this repository.
2. Open Google Colab.
3. Upload the .ipynb notebook.
4. Run all cells.
5. View the traffic analysis, peak-hour results, and heatmap.

 Expected Output

The project generates:

* Hourly traffic demand curves.
* Vehicle count statistics for 10 junctions.
* Peak congestion hour identification.
* Top 3 busiest junctions.
* Traffic heatmap visualization.
* Loop vs. vectorized execution-time comparison.

 Future Improvements

* Integrate real-world traffic datasets.
* Add weekday and holiday traffic analysis.
* Develop an interactive traffic monitoring dashboard.
* Explore machine learning for traffic prediction.

 
