# Driver-Alertness-Detection

### Description

People have to be very careful while driving. A moment of distraction may lead to accidents. The main objective of this project is to determine whether the driver is alert or not using the combination of environmental, physiological and vehicular data.


This is a binary classification problem of determining whether a driver is alert (1) or not (0)

### Software and Libraries

This project uses Python and some of its libraries for execution. You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/index.html).

It is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the required packages included with it.

### Getting Started

Using the terminal, navigate to the project directory and run:

`jupyter notebook alertness-detection.ipynb`

This will open the project code in jupyter notebook in your browser

### Data

The dataset is downloaded from: [Kaggle](https://www.kaggle.com/c/stayalert/data)

The data is collected performing a number of trials which has been recorded every 100ms during a driving session on the road or in a driving simulator from around 100 drivers of both genders of different ages.

- `fordTrain.csv` - All the input features and the target "IsAlert" values (a total of 604,329 rows)
- `fordTest.csv` - All the input features without the values of the target (120,840 rows)

The columns P1 to P8 represent the physiological data. Columns E1 to E11 represent the environmental data. Columns V1 to V11 represent the vehicular data. *Actual names and measurement units of the physiological,vehicular and environmental data are not disclosed in the data set.*