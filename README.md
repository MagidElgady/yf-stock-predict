# yf-stock-predict
Using yfinance Python library to predict stock prices

# Installing packages
There are two ways of installing the necessary Python packages for this code to work:

# Main Python library
Download the packages to your main Python install by entering the following command in your terminal: pip install -r requirements.txt

# Virtual environment
Create a separate virtual environment where you can install of the necessary libraries that will only exist in that directory. It cannot be accessed outside of that folder. 
This allows you to organise all of your Python libraries for specific projects.

# How to create a virtual enviornment:
1) Open VSCode in the directory you want to use. 
2) Open the terminal with Ctrl + '.
3) Type the following in the terminal: py -m venv name.
4) Wait for the venv to be created.
5) Type the following to change into that environment directory: cd name.
6) Once created, you'll see VSCode prompting you to change to that environment. Click confirm.
7) Activate the environment by entering the following terminal commands in the virtual environment directory: Scripts\activate
8) To install the necessary libraries: activate the environment and then pip install.
9) To select the venv's Python interpreter, press Ctrl+Shift+P and then type "Select Interpreter".
10) Select the interpreter that you want to use with the necessary packages and you're done.
Note: To deactivate the environment, type: deactivate.

To install the necessary packages, enter the virtual enviroment and then enter the same command as before: pip install -r requirements.txt

# Running the code
1. Enter the parameters.py file and edit the following: ticker for the stock you want to predict, and EPOCHS for the number of simulations you want to run 
(more is better but takes longer to run). Then, run parameters.py.

2. Run stock_predcition.py

3. Run train.py

4. Run test.py

5. You will see a graph that compares actual stock price vs predicted stock price when running test.py

Have fun!

Link to original code: https://www.thepythoncode.com/article/stock-price-prediction-in-python-using-tensorflow-2-and-keras
    
