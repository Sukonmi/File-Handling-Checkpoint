# 🎯OVERVIEW.
A checkpoint that visualises the use of the File Handling Python skill set.

# 📢DESCRIPTION.
In this checkpoint I used the numpy function and manipulate the CSV Dataset.

# ℹ️INSTRUCTIONS.
- Begin by importing the necessary libraries, numpy.
- Use the open() function to open csv file and assign the result to a variable.
- Use the numpy array to perform some basic statistical analysis on the data, such as finding the mean, median, and standard deviation of the loan amounts.
# Note:
- Be sure to close the file after you have finished reading it in with the open() function.
- Use the delimiter parameter in the genfromtxt() function to specify that the values in the file are separated by commas.
- You can use the numpy functions mean(), median(), and std() to find the mean, median, and standard deviation of the loan amounts.

# 🛠️TOOLS USED.
- Anaconda.
- VSCode.
- GitHub.
- Git.
- Google Drive

```
import numpy as np
np.array
with open("text.txt", "a") as file_object:
    loans = file_object.readlines()
```
