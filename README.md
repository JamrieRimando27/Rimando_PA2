# Programming Assignment 2
#### Deadline: September 3, 2025
## I. Intended Learning Outcomes:
  1. To identify the codes and functions incorporated in the Numpy library
  2. To be able to apply and use the different codes and functions in creating a Python program using a Numpy library
  
## II. Instructions:
  Write a Python script/code in the Jupyter Notebook to do the given problems. You may submit your Jupyter notebook in the dedicated submission bin.
## III. Problems:
  #### 1.) NORMALIZATION PROBLEM: 
  In this problem, create a random 5 x 5 ndarray and store it to variable X. Normalize X. Save your normalized ndarray as X_normalized.npy
  #### 2.) DIVISIBLE BY 3 PROBLEM: 
  Create the following 10 x 10 ndarray, which are the squares of the first 100 positive integers. From this ndarray, determine all the elements that are divisible by 3. Save the result as div_by_3.npy
  ## IV. Answers and Explanation:
### NORMALIZATION PROBLEM
<img width="619" height="653" alt="Image" src="https://github.com/user-attachments/assets/d8317a65-615a-4ca6-8ea5-5237a3d119bc" />

First, import the NumPy library, which helps when working with numbers and arrays. Then, create a 5x5 matrix filled with random numbers between 0 and 1 and print it. After that, calculate the mean of all the values in the matrix and also calculate the standard deviation. Using these two values, normalize the matrix. This means subtracting the mean from each number and then dividing the result by the standard deviation. This will result in a new matrix where the numbers have a mean of 0 and a standard deviation of 1. Then save this normalized matrix to “div_by_3.npy” for later use, and finally, print the normalized matrix to see the result.
### DIVISIBLE BY 3 PROBLEM
<img width="663" height="353" alt="Image" src="https://github.com/user-attachments/assets/d826e7e4-34b0-4c47-b43e-4b9e7432eea7" />

Start by making the square of the first 100 positive integers. This is done by creating a list of numbers from 1 to 100 and then squaring each one. The resulting 1 dimensional array is stored in a variable called “squares”. Then reshape this array into a 10x10 matrix and store it in a variable called “A”. Next, identify all elements in the matrix A that are divisible by 3. To do this, check which elements leave a remainder of 0 when divided by 3 using modulo. Modulo’s function is to divide the values and then output the remainder, if it’s zero then in this case the number is divisible by 3 . All such values are extracted and stored in a new array called "div_by_3". Finally, save this new array to a file named "div_by_3.npy" to access the results later.
