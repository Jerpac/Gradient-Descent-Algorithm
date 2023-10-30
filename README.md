# Gradient-Descent-Algorithm
An algorithm made by scratch to find the best weights for a linear regression model, by getting the lowest error possible.

Running The Code-----------------------------------------------------------------------

Run the code on google colab assignment1part1.py as well as assignment1part2.py
The dataset is available on my github, which is being accessed in the code.

If you want to view the log of different weights trialed, simply open the 
weights_tested_results.txt that should have been created within the same directory
as where you are using assignment1part1.py

Same thing follows for assignment1part2.py, except the file name will be called
linear_regression_data.txt, and the data stored will be weights, bias, MSE,
and R2 value.

IMPORTS---------------------------------------------------------------------------------
Imports should already be in the code that I submitted, but just in case you want
reference for the imports used, they will be listed below for each part.

Imports used in part 1:

import pandas as pd
import numpy as np
import random
import math

Imports used in part 2:

import pandas as pd
import numpy as np
import random
import math

from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error
from sklearn.model_selection import train_test_split
from matplotlib import pyplot as plt
from sklearn.metrics import r2_score
