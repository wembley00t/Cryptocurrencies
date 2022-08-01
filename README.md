# Cryptocurrencies


The purpose of this project is to create an analysis of data for the cryptocurrency market.  This data will be used to understand what cryptocurrencies are currently trading and how they can be grouped to create a classification system for a new investment.  The data will be evaluated using an unsupervised machine learning model.

The analysis consisted of preparing a dataframe from a CSV file that can be used for clustering.  The StandardScaler was used to create the dataframe for use in PCA or Principal Component Analysis.  PCA was used to reduce the dimensions of the scaled dataframe to three principal components.  An elbow curve using hvPlot to find the best value for K was created.  Predictions were made on the K clusters of the cryptocurrencies' data.

![elbow curve](https://user-images.githubusercontent.com/100876517/182058867-a41c1b39-37da-41d5-b623-12e8b08f081f.png)


The final output was visualizing the crypotcurrencies results.  This was accomplished through the use of a 3D scatter plot using Plotly Express and a scatter plot using hvplot.  Examples of the visualizations are below.

  
![newplot (1)](https://user-images.githubusercontent.com/100876517/182057483-3f0a010a-0203-4f80-8378-32dc15bd8b99.png)

![bokeh_plot (1)](https://user-images.githubusercontent.com/100876517/182057487-1d133a4c-ee3a-4f0d-9041-91ef7d60dfed.png)
