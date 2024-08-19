## **Project Name**
**Natural Disasters Analytics**

# **Natural Disasters Analytics: Wildfires and Earthquakes Data Visualization**

## **Project Overview**

This project focuses on analyzing and visualizing natural disasters, specifically wildfires in California (2013-2020) and global earthquake events. By leveraging these datasets, the project aims to provide insightful visualizations that highlight the frequency, magnitude, and geographical distribution of these natural disasters. The visualizations will help identify patterns and regions that are particularly prone to such events, aiding in understanding and potentially mitigating future impacts.

## **Project Goals**

### **Wildfires in California (2013-2020)**
- **Dataset:** [California Wildfire Incidents (2013-2020)](https://www.kaggle.com/datasets/ananthu017/california-wildfire-incidents-20132020/data)
- **Data Size:** 1636 rows × 40 columns
- **Important Columns:** Incident Name, Start Date, End Date, County, Acres Burned, Latitude, Longitude
- **Visualization Plan:**
  - **Dot Plot:** Visualize each wildfire incident as a dot on a map of California. The size of the dot represents the acres burned, providing insights into the spatial distribution and severity of wildfires across different counties.
  - **Density Plot:** Create a density plot using geographical coordinates to highlight areas with higher concentrations of wildfire incidents.

### **Global Earthquake Events**
- **Dataset:** [Earthquake Dataset](https://www.kaggle.com/datasets/warcoder/earthquake-dataset)
- **Data Size:** 1000 rows × 19 columns
- **Important Columns:** Date, Time, Latitude, Longitude, Depth, Magnitude, Location Description
- **Visualization Plan:**
  - **Dot Plot:** Represent each earthquake event as a dot on a world map. The size or color of the dot indicates the earthquake's magnitude, offering an overview of the distribution of earthquakes globally.
  - **Density Plot:** Use geographical coordinates to create a density plot that visualizes regions with higher seismic activity, identifying areas more prone to significant earthquake events.

## **Tools and Technologies**
- **Data Processing & Analysis:** Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Visualization:** Flourish Studio, Matplotlib
- **Data Sources:** Kaggle

## **Acknowledgments**
This project was completed as part of the course **IE6600 Computation and Visualization** under the guidance of **Professor Satwik Kamarthi**.

## **License**
This project is licensed under the MIT License. See the LICENSE file for details.

---

This README file provides an organized overview of your project, allowing others to understand its purpose, datasets, and visualizations while making it easy to set up and run.
