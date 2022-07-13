# Stock Analysis Refactored #

## Overview of the Project ##
### Background ###
Steve wants an easy way to find the total daily volume and yearly return for each stock. The original code devised to analyze the initial set of stocks Steve provided in the green_stocks file probably wont scale well to analyze the entire stock market - it may take a long time to execute.   

### Purpose ###
The goal now is to refactor the code and make it run faster: through fewer steps, less memory used, or improved logic. The challenge includes stock data from 2017 and 2018. The output should be the same - ticker symbol, toal daily volume, and return. 


## Results and Analysis ##
The refactored code starts by setting the tickerindex equal to zero, defining the arrays, and initallizing the ticervolumes.
![Code steps 1 & 2](/resources/code-step-1-2.png)

The next step is to calculate the total ticker volume by finding the start and closing price for each ticker symbol.
![Code Step 3](/resources/code-step-3.png)

Last, a `for` loop is used to output the three values - ticker symbol, toal daily volume, and return
![Code Step 4](/resources/code-step-4.png)

## Summary ##

### 1. Advantages and Disadvantages of Refactoring Code ###
Refactoring is intended to improve internal performance while retaining the same functionality.
- The Advantages
  - Refactoring code is a good way to maintain it and keep it relevant. 
  - Make it easier to understand
  - Improves code design by reducing scope, simplifiying complex instructions, and combining multiple statements into one.
  - Speed up execution
  - identify bugs  

- The Disadvantages
  - Refactoring code is time consuming and has the potential of introducing mistakes.
  - The benefit of refactored code is not self-evident since the functionality does not change. 
  - Refactoring without understanding the original code is risky.

### 2. Advantages and Disadvantages of Refactoring the Stock Analysis Code ###

The biggest benefit of refactoring the stock analysis code is a shorter runtime. the orignal runtime took almost one second to run.  The refactored code cut the runtime in half. Images for 2017 and 2018 included below: 

**2017 Results and Runtime**
![2017 results and runtime](/resources/vba_challenge_2017.png)

**2018 Results and Runtime**
![2018 results and runtime](/resources/vba_challenge_2018.png)
