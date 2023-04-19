# mod13challenge

This is a python script that compares 3 neural network models with different input values.
The script uses "applicants_data.csv" to compile the data.
---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For access to Pandas series and dataframes.

* [pathlib](https://github.com/budlight/pathlib) - To load csv files.

* [tensor flow](https://www.tensorflow.org/api_docs) - For neural network models.

* [Scikit-learn](https://scikit-learn.org/stable/) - To prepare data for tensorflow models

---

## Installation Guide

Before running the application first install the following dependencies.

```python
import pandas as pd
from pathlib import Path
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder
```

---

## Usage

To use the script simply clone the repository and venture_funding_with_deep_learning.ipynb

```python
venture_funding_with_deep_learning.ipynb
```



---

## Contributors

Mike Blanchette

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.
