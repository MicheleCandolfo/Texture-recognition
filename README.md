# Texture recognition

The project deals with the analysis of a data set for the recognition of materials based on the surface (texture recognition).
The data in this project is private as well as the code, if you want to have a look do not hesitate to contact me.

Information about the data used:
The data set consists of measurements with 21 different materials. The individual materials form the classes. The experimental set-up for data collection was represented by a sensor attached to a robotic arm that traverses a predetermined path. The differently performed measurements were then divided into 2,267 CSV files, which in turn were divided every 2,000ms with 2,000 entries per file.

During the measurement, the sensor perceives the force (F) and the torsion (T) in the coordinate system in X, Y and Z direction. Since a given path is always traversed, these values can be positive and negative. A positive Fx value stands for a movement in the direction of the X axis, a negative Fx value for a movement in the opposite direction. The situation is similar with torsion. The torsion occurs depending on the force acting on the sensor. The interrelationships of the individual parameters are examined in more detail in chapter 3 Data Preparation.

Material in the data set: 

['aluminium', 'blackboard-cloth', 'book-cover', 'cardboard', 'cardboard-fine', 'cleaning-cloth', 'computer-paper', 'cork', 'cotton-bag', 'cutting-board', 'cutting-mat', 'glass', 'jeans', 'marble-tile', 'newspaper', 'osb', 'plastic-bag', 'polymer-tile', 'stone-tile', 'towel', 'wood']

## Project Stack

**Programming Language:** Python

**Modules and packages used:** Pandas, Numpy, yfinance, Matplotlib, Plotly, Seaborn, Sklearn, Xgboost, Tensorflow and Keras

**Data:** Private data set

**Machine Learning Algorithm:** Random Forest, Neural Network (MLP)

**Methodology used:** CRISP-DM




