Priority Calculation


About


To calculate priority between different patients in case they want the same unit of stem cells.


Getting Started


1. Install all the dependencies.
     pip install numpy
     pip install pandas
     pip install -U scikit-learn
     pip install matplotlib


2. Import all the Dependencies
     import numpy as np
     import pandas as pd
     import matplotlib.pyplot as plt
     from sklearn import metrics


3. Loading the data from csv file to a Pandas DataFrame
4. Add the mixed column with random points using random function
5. Calculate rank for various patients w.r.t waiting time
6. Take input from users for all the variables used in the equation
7. Define points for each age and distance category
8. Calculate score on the basis of age, waiting time, distance and all the other factors.
9. Now, calculate the total score of all the patients.
10.  Rank all the patients on the basis of their score.