# Module_14_Challenge: Machine Learning Trading Bot
Submission Date: June 01, 2023 @ 11:59pm

![image](https://github.com/AthuraThava/Module_14_Challenge/assets/125240804/78645594-d1d5-45f7-83b2-8167f8002e81)

### Background
For this Challenge, you’ll assume the role of a financial advisor at one of the top five financial advisory firms in the world. Your firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, your firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.

The speed of these transactions gave your firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. You’re thus planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, you’ll enhance the existing trading signals with machine learning algorithms that can adapt to new data.

### What Was Created
The steps for this Challenge are divided into the following sections:
* Establish a Baseline Performance
* Tune the Baseline Trading Algorithm
* Evaluate a New Machine Learning Classifier
* Create an Evaluation Report

## Base Model
![image](https://github.com/AthuraThava/Module_14_Challenge/assets/125240804/88bcb196-f1bd-458d-a6b4-e976290abff6)

Over the 6 year period from 2016 - 2021, the base model of the strategy returns at 1.5 performs better then the actual return of 1.4.

## Step 1: Tune the training algorithm by adjusting the size of the training dataset.
The training dataset size was altered to 6 month from 3 month. While all other parameters remained the same. 
![image](https://github.com/AthuraThava/Module_14_Challenge/assets/125240804/db1eba50-f3c0-423b-9f17-ce95716a526c)

Over the 6 year period, the strategy returns at 1.8 performs better then the actual return of 1.6, when the training dataset was doubled.

## Step 2: Tune the trading algorithm by adjusting the SMA input features.
The short window was chaged from 4 to 5, while the long window was changed to 125 from 100. The training dataset size remained at 3 months and all the other parameters remained the same.
![image](https://github.com/AthuraThava/Module_14_Challenge/assets/125240804/5aee46ae-8fab-4156-b266-4df1837a3763)

The strategy returns at 1.6 performs better then the actual return of 1.5. These changes are reflected in the close correlation patterns of the stragety and actual return outputs. 

## Step 3: Choose the set of parameters that best improved the trading algorithm returns.
Adjusting both the training dataset and SMA inputs improved the performance, but the changes to the SMA input feature performed better. Changing the SMA input features window can affect how well the trading method performs. The SMA window controls how long the moving average computation takes and may have an impact on how sensitive the strategy is to the actual return. Hence it is not recommended to influence SMA input features.

## Evaluate a New Machine Learning Classifier
