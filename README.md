# Shared_Bikes_Demand-_Prediction

- Run the code file 'Bike Sharing Assignment.ipynb' with input file as 'day.csv'

# Problem Statement - 

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

# Methodology

1. Read the file "day.csv"

2. Perform EDA on the data

3. Prepare the datset for training (Dummy variables creation)

4. Splitting the training and test data, use scaler to transform the data

5. Build a linear model

6. Use RFE to select top features, use VIF and P-value to find features having high importance.

7. Predict on test data and compare the results
