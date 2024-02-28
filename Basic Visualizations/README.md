# Basic Data Visualization Notebooks
This repository contains a series of Jupyter notebooks that demonstrate a broad range of my data visualization coursework. These notebooks showcase my ability to create custom designs for visualizing various datasets, effectively extracting insights.

# Overview
The notebooks included in this collection are:

**1. Discrete Visualization**
Explore international tourism visitation data to the U.S. and uncover trends for enhancing tourism strategies.

**2. Continuous Visualization**
Investigate the distribution of student grades across various courses to identify educational trends and strategies.

**3. Heatmap with Folium**
Created Folium heatmaps to visualize air quality in Los Angeles for 2022 using EPA data and mapping U.S. car accident hotspots in 2018.

**4. Exercise Data Visualization**
Analyze exercise data from a wearable device to understand personal fitness trends and routines.

Technologies: Python, Pandas, Matplotlib, Plotly, Folium, Seaborn


## Summary insights and Techniques Used
**1. Discrete Visualization**

Bar Charts for Comparative Analysis: This technique involves plotting both the original metrics and their logarithmic transformations using bar charts. It compares visitation numbers across states with varying tourist volumes with different metrics to help ranking cities by their visitation number

**2. Continuous Visualization**

Histogram with T-Distribution Overlay: To assess the distribution of grades, histograms are used alongside a t-distribution line. This approach aids in visualizing the central tendency and variability of the data.

Quantile-Quantile (QQ) Plots: QQ plots compare the distribution of student grades against a normal distribution. This visualization helps visually identify deviations from normality as well as examines the normal distribution assumptions required for statistical modeling, 

**3. Heatmap with Folium**

Dynamic Heatmaps Using Folium: By utilizing Folium, dynamic heatmaps are created that incorporate latitude, longitude, and temporal data. This technique is applied to visualize spatial distributions of phenomena such as air quality and accident frequencies.

**4. Exercise Data Visualization**

Cadence vs. Ground Time: By using a scatterplot, I was able to identify a negative correlation between Cadence and Ground Time. This means that when cadence increases, ground contact time decreases, which is indicative of efficient running form. However, there were some outliers that suggest areas for improvement, potentially due to muscle imbalances or fatigue.

Form Power Distribution: I analyzed the data using a histogram and found that the form power values were most concentrated around 75 to 120 watts, with a peak of 98.875 watts. This distribution suggests that Mike's power output during runs was consistent, with lower-end outliers potentially indicating warm-up periods or periods of efficient running. 

Heart Rate Variability in Running and Cycling: I compared the heart rate distributions between running and cycling using a violin plot. The results showed that the median heart rates were similar, but there was greater variability during running, indicating fluctuating exertion levels. On the other hand, cycling demonstrated a more consistent heart rate, suggesting it may help maintain a steadier cardiovascular effort.

Time-lapse Heart Rate Intensity: I used a Folium time-lapse heatmap to visualize exercise locations alongside heart rate intensity over time. This allowed med to gain insights into physical activity levels at various locations, with color intensity variations indicating periods of higher or lower exertion.

# Environment and Libraries
To use these notebooks, you will need:

Python 3.x
Jupyter Notebook or JupyterLab
Libraries: Pandas, Matplotlib, Seaborn, Folium, Plotly
Installation of libraries can be done via pip:

`pip install pandas matplotlib seaborn folium plotly`