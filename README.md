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
