# NEDL_Portfolio_Optimizer

Credit: NEDL (https://www.youtube.com/c/NEDLeducation)

Efficient portfolio frontier in Python function base on NEDL example 

The function returns optimal portfolio weights based on timeseries ticker data. 

 + Positive values are BUY positions
 - Negative values are SELL positions.

# 1. Input

The function requireses timeseries stock data with the date in index. Example using yfinance:

![image](https://user-images.githubusercontent.com/49153959/148683775-99761d40-bc8b-4218-a816-7c6eca4cc1cd.png)

Additionally you can set an optional argument "expected_return". Default value is 10% (0.10).

# 2. Output

The function outputs the following tuple:

1. Stock names as an array
2. Position weights as an array
3. Optimal calculated return
4. Optimal calculated return

![image](https://user-images.githubusercontent.com/49153959/148683839-10f7677e-4a13-4c48-a00c-4f6971b48d72.png)

# 3. Optional - def Backtest

Returns a list containing the first and last day of the year of the times series in increments of 1 year. (first instance to last same year instance that is before xxxx-12-31)

Full Output -> list of DFs incremented with an additional year.

## First Output:

![image](https://user-images.githubusercontent.com/49153959/148684141-1cbf12bd-270e-4a94-ac19-b77e92c8c4b5.png)

## Last Output:

![image](https://user-images.githubusercontent.com/49153959/148684163-e5e2034f-f4ee-4ee6-98d6-9c5970ea7499.png)

