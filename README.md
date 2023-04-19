#  A comprehensive investigation on Car Price Prediction dataset (Tensorflow-keras)

This dataset contains information on various characteristics of cars such as mileage, automatic or manual, engine fuel, etc., and the goal is to predict the price column using these features. The dataset has been analyzed using appropriate visualizations and exploratory data analysis (EDA) techniques to gain insights into the data, such as by creating a histogram of engine fuel type.

To train and validate the model, 85% of the data has been used for training and validation, with the remaining 15% used for testing. The dataset has been used to design and optimize a neural network for car price prediction, with RMSE and MAE indices displayed over 100 epochs.

To further evaluate the performance of the network, experiments have been conducted to analyze the effect of increasing the number of neurons and layers. A network with one layer and between 50 and 500 neurons has been designed and trained, and the minimum MAE obtained for each number of neurons has been plotted in a graph to analyze the impact of increasing the number of neurons. Similarly, a network with 100 neurons in each layer and the number of layers ranging from 1 to 7 has been implemented, and the minimum MAE obtained for each number of layers has been plotted to check the effect of increasing the number of layers.

Finally, a wide and deep network has been implemented to solve this problem, and the results are compared with those of the previous approaches. This dataset and the corresponding code provide a comprehensive solution for car price prediction and can be used as a reference for similar projects.
