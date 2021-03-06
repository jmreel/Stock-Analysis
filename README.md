# Stock-Analysis

## Overview of Project:
The purpose of this project was to help Steve perform an analysis on stock data from 2017 and 2018 with VBA. Using VBA will automate the process by helping Steve not have to manually analyze the data. The goal was to edit, or refactor, the existing code to loop through all the data one time.  Refactoring code helps makes it more efficient, maintainable and easier to debug. 
In order to analyze the data a program flow was created that looped through the tickers. After the tickers have been assigned a value between 0-11, the data will be looped, while also using nested loops. When looping through, the code is finding the total volume, starting price, and ending price for each ticker. Steve will then be able to click “Run Analysis for All Stock” and the “Total Daily Volume” and “Return” from 2017 or 2018 will be automatically imputed into the cells. 
## Results: 
The analysis shows that the stock performance of 2017 had a higher return when compared to 2018. To be able to analyze the data quickly, an if-then else statement was created. This analyzes the “return” columns and determines whether the conditions were met. In this case, if the cell is greater than zero, the cell changes to green and if the cell is less than zero, it changes to red. This was another way for Steve to quickly get the information that was needed. Then a loop was created to conditionally format all the cells. The execution times of the refactored script was significantly faster than the original script. 
### Advantage and Disadvantage: 
The advantage of refactoring code is making it more efficient without changing the functionality. It is made more efficient by taking fewer steps, using less memory, and improving the readability of the code. Another advantage is that refracting will make it easier to maintain the code, which will be beneficial when working with a team. However, refactoring is not always the answer. The disadvantage of refactoring is introducing a new bug to working code. This could lead to more time refactoring and cause the project to be late. If this code would only be used for one time, it would not make sense to refractor this code. 
### Application:
The advantage of refactoring “The All Stocks” code was the efficiency of the run time.  The original run time for 2018 was .278 seconds and the new run time is .082 seconds. Refactoring this code increased the run time by 300% and had no issues. With larger amounts of data, this has the potential to analyze data at a much faster rate than the original code. 

All Stocks 2017
![All Stocks 2017](https://user-images.githubusercontent.com/99099706/159132972-8f992099-0228-4ca2-9554-150b0d89e0a2.png)

All Stocks 2018
![All Stocks 2018](https://user-images.githubusercontent.com/99099706/159133011-2cb0d7e4-aee0-4212-82bf-535b0c0b985c.png)

All Stocks 2018 Slow
![All Stocks 2018 Slow](https://user-images.githubusercontent.com/99099706/159133040-4087b814-aacd-4048-b193-2915667db0d6.png)
