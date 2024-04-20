# The Fundamental of Python Part 2

## Function
  - In Python, a function is a block of code that performs a specific task and can be reused multiple times throughout your program. Functions can take inputs (arguments), perform operations on them, and return outputs. They help in making the code more organized, modular, and reusable.
  - Components of a Function
      - Function Definition: This is where you define the function using the def keyword, followed by the function name and parentheses containing any arguments.
      - Function Body: This is the block of code inside the function where the actual task is performed.
         Return Statement: If the function needs to send back a result, it uses the return statement to return the value.
  - Example of a Function
    - Let's define a simple function that calculates the square of a number.

      ![Example of Function](https://github.com/laksmiariyani9/Python-2/assets/166054815/58a3fc17-feac-47fe-b305-4b9e1880035b)

      - def square(number): This line defines a function named square that takes one argument number.
      - """This function calculates the square of a number.""": This is a docstring (documentation string) that provides a brief description of what the function does.
      - result = number * number: This line calculates the square of the number passed to the function and stores it in the result variable.
      - return result: This line returns the calculated square value.

  - Calling the Function
    - After defining the function, you can call it by its name and pass an argument to it.

      ![After Defining](https://github.com/laksmiariyani9/Python-2/assets/166054815/5f3f278d-0c8e-4467-8ce4-966368c7d3b4)

  - Here's the complete code:

    ![Here is the complete code](https://github.com/laksmiariyani9/Python-2/assets/166054815/264855de-b1b7-4741-babd-ec79d146b404)

    - In this example:
      - We defined a function named square that calculates the square of a number.
      - We called the square function with an argument 5, which returned the square of 5, and then printed the result.
          
  - Return
    - It returns a value from the function.
    - Example:

      ![Return](https://github.com/laksmiariyani9/Python-2/assets/166054815/c4778de9-b283-4f61-af0d-9d574adea3de)


  - Call
    - Invoking the function by its name.
    - Example:

      ![Call](https://github.com/laksmiariyani9/Python-2/assets/166054815/8f9fe835-90fb-4928-85f6-3f4c25a9c6ac)


  - Pass
    - Placeholder for future implementation.
    - Example:

      ![Pass](https://github.com/laksmiariyani9/Python-2/assets/166054815/2e3731af-87f2-4ef0-8b1d-dde71b240b99)


## NumPy (Numerical Python)
  - NumPy Array
    - A multi-dimensional array used for numerical computations.
    - Example:

      ![NumPy Array](https://github.com/laksmiariyani9/Python-2/assets/166054815/0f1c88a5-5d3e-4bbb-b077-73770bee5457)


## Pandas
  #### Pandas Series
  - A one-dimensional labeled array.
    - Implicit: Index starts from 0.
    - Explicit: Custom index is assigned.
    - Example:

      ![Implicit   Ekspicit](https://github.com/laksmiariyani9/Python-2/assets/166054815/9f0f52e2-ef12-4ab6-81cd-31a4e0698340)


  #### Data Slicing
  - Selecting a subset of data.
    - Example:

      ![Data Slicing](https://github.com/laksmiariyani9/Python-2/assets/166054815/880be457-e8cf-4e54-ab27-cefa23e42725)


  #### .loc and .iloc
  - loc: Label-based indexing.
  - iloc: Position-based indexing.
  - Example:

    ![Loc   iloc](https://github.com/laksmiariyani9/Python-2/assets/166054815/3ee39c93-f400-4478-8592-71667e034b51)


  #### Dictionary to Series
  - Creating a Series from a dictionary.
  - Example:

    ![Dictionary to series](https://github.com/laksmiariyani9/Python-2/assets/166054815/d01c4a37-8d91-40a0-9d6e-3b26cd7a8e52)


  #### Pandas DataFrame
  - Convert Data Series to DataFrame
    - Combining multiple Series into a DataFrame.
    - Example:

      ![Convert Data Series to Data Frame](https://github.com/laksmiariyani9/Python-2/assets/166054815/71fc6bb3-6e73-45e1-9e9b-777e6ca11f08)

  - Load Data from CSV
    - Reading data from a CSV file.
    - Example:

      ![Load Data from CSV](https://github.com/laksmiariyani9/Python-2/assets/166054815/15e7b68a-84b0-4d83-9b89-4a077ff8bdc8)

  - DataFrame Methods and Attributes
    - head(): First n rows.

      ![Head()](https://github.com/laksmiariyani9/Python-2/assets/166054815/624d1f25-b6cc-48a0-9e4a-2b60a2e4cf77)

    - info(): Information about DataFrame.

      ![Info()](https://github.com/laksmiariyani9/Python-2/assets/166054815/3c58b289-8648-4204-b51d-7ff85da5612c)

    - notnull() and isnull(): Check for missing values.

      ![Notnull()   isnull()](https://github.com/laksmiariyani9/Python-2/assets/166054815/14d9ecf6-ffa2-4973-a77e-cfe67c93dcbd)

    - tail(): Last n rows.

      ![Tail()](https://github.com/laksmiariyani9/Python-2/assets/166054815/31ec5721-31cf-4da7-bb5e-6a6183631b65)

    - shape: Dimensions of DataFrame.

      ![Shape](https://github.com/laksmiariyani9/Python-2/assets/166054815/d7997497-676a-4373-b966-3fc11d274942)

    - column and index: Names of columns and index.

      ![Column   Index](https://github.com/laksmiariyani9/Python-2/assets/166054815/d6c1e2f9-d857-4eea-b149-f8afbea15e52)

    - describe(): Summary statistics.

      ![Describe()](https://github.com/laksmiariyani9/Python-2/assets/166054815/33da16ea-62f9-4ede-8496-cc414b6b1d7c)

    - mean()

      ![Mean()](https://github.com/laksmiariyani9/Python-2/assets/166054815/9cc79a8c-42d6-4ef1-bd13-eac0689d9e8e)

    - median()

      ![Median()](https://github.com/laksmiariyani9/Python-2/assets/166054815/a5c84768-ed25-44e5-9abe-7b81ed48daba)

    - mode()

      ![Mode()](https://github.com/laksmiariyani9/Python-2/assets/166054815/19a4ecb3-42ee-4873-b691-bf2bc132e384)

    - max()

      ![Max()](https://github.com/laksmiariyani9/Python-2/assets/166054815/edd8ee4d-b0ac-457c-b0ba-40297f556a47)

    - min()

      ![Min()](https://github.com/laksmiariyani9/Python-2/assets/166054815/c8c388cc-173e-4125-96f3-1562ed1b2875)

    - unique()

      ![Unique()](https://github.com/laksmiariyani9/Python-2/assets/166054815/22dfb8bc-5a15-4a04-adaf-aead13a0ec0c)

    - value_counts()

      ![Value_counts()](https://github.com/laksmiariyani9/Python-2/assets/166054815/fe8a66b8-6ac4-4e0f-a2d8-c7ac1fe64a88)


## DateTime
  - Handling date and time in Python.
  - Example:

    ![Datetime](https://github.com/laksmiariyani9/Python-2/assets/166054815/bf4b2967-08a6-4982-9c92-00347578ae7a)


## Random Library
  - Generating random numbers and sequences.
  - Example:

    ![Random Library](https://github.com/laksmiariyani9/Python-2/assets/166054815/d3c5d534-1202-4019-a528-c02b082fa94c)


## Text File Operations
  #### Open
  - Syntax:

    ![Open](https://github.com/laksmiariyani9/Python-2/assets/166054815/b299771c-df51-4a1a-8f12-4e8a005f7d32)

  #### Read
  - Syntax:

    ![Read](https://github.com/laksmiariyani9/Python-2/assets/166054815/b3e532f0-e20b-4414-afc2-fcdd639534eb)

  #### Close
  - Syntax:

    ![Close](https://github.com/laksmiariyani9/Python-2/assets/166054815/920c01b5-8471-4e53-a0ba-db7b8b098e35)
