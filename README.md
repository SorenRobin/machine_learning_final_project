# machine_learning_final_project
Final Project for Machine Learning module exploring bike rental data from Seoul

Dataset source: Seoul Bike Sharing Demand [Dataset]. (2020). UCI Machine Learning Repository. https://doi.org/10.24432/C5F62R.

From first observations, the strongest correlation is the relationship of Temperature with Bike Rentals. I did also notice that Temperature has a strong correlation with Humidity and Dew Point Temperature. However, I discovered that Temperature's relationship with Humidity was a mild negative correlation while the relationship between Temperature and Dew Point Temperature was a moderate positive.

From there, I chose to run a Multiple Linear Regression model on my data due to the multiple contributors of my target, in which I seek to measure the effect weather has on the number of bikes rented from the bikeshare program. After preprocessing and model implementation, I ran the RMSE and R-2 scores to measure how well the model performed. To my satisfaction, it holds a Root Mean Square Error of 466.68. Using an Exploratory Data Analysis HTML file (which includes visualizations of the initial EDA), I found that the highest amount of bike rentals is at 3556, so that means my RMSE is within acceptable parameters for my goal. The R2 score, though, is less-than-ideal, reading in at 0.48 indicating a moderate fitness. Though considering that its purpose is estimation rather than exactness, this is a more than sufficient fitness for my needs.
