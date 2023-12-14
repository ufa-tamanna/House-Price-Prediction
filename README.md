# House-Price-Prediction
This project focuses on predicting house prices for a specific region in a city, employing the Linear Regression Model.
We collected the dataset from the link given below: 

https://www.kaggle.com/datasets/tanyachawla412/house-prices 

** Instruction **:

The writer used Jupyter Lab to run the code file. To get started, download both the .csv file and the code file. 

The dataset used in this project were prepared on a MacBook. Because of this, .DS_Store files also occupy the project folder. 
While these files don't impact the functionality of the code, they might cause errors during execution.
We recommend removing these files before running the code to ensure a smooth execution process. 
You can do so by running a command like find . -name ".DS_Store" -delete in the dataset directory.


1.	** Dataset **:

The columns of the “House_price.csv” dataset are described below:
•	‘Avg. Area Income’: This column represents the average income of the householder where the house is located at.

•	‘House Age’: This column contains the average age of houses in that region.

•	‘Number of Rooms’: This column contains the average number of rooms for houses in that region.

•	‘Number of Bedrooms’: This column contains the average number of bedrooms for houses in that region.

•	‘Area Population’: This column represents the population of the area.

•	‘Price’: This column represents the price that the house is sold at.

•	‘Address’: This column contains the addresses of the houses.


While creating the heat map, we didn’t take the variable ‘Address’, as it is of String data type. 
Based on the heat map, as ‘Price’ increases, so do other variables. That’s why we chose ‘Price’ as the dependent variable, and the rest of the 5 variables as the independent variables.



2. ** Model Details **:

The features are the input variables, and the label is what we are trying to predict. 

•	Features: 'Avg. Area Income', 'House Age', 'Number of Rooms', 'Number of Bedrooms', and 'Area Population'.

•	Label: 'Price'.



3.	** Dataset Splitting **:
   
We split the dataset into 70% train and 30% test set. We fit the train dataset with known inputs or ‘features’. 
The test dataset takes the known inputs and makes prediction and compares the prediction with ‘label’, in our case which is ‘Price’. 

4. ** Evaluation **:
   
Model performance was evaluated on both the training and test sets, and metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Squared Error (MSE) were reported.

Additionally, scatter plots were generated to assess the accuracy of predictions and identify potential outliers. Histograms were employed to visualize the distribution of the data.

