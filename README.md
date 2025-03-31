# cs345-project

----------- Bitcoin Price Analysis and Predictions ----------
# Topic
We decided to explore a dataset on Bitcoin created by Mark Zielinski on kaggle.com.

# What makes this interesting/challenging?
The most interesting part of a dataset centered around the price of Bitcoin is the volatile nature of the cryptocurrency. The main challenge that we will encounter comes from the different trends that have affected the price of Bitcoin over time, as well as the speculative value of cryptocurrencies. This topic grabbed our interest due to the current influx of investors and national publicity brought to cryptocurrencies within the past few months from President Trump's political campaigning and policies since his reelection.

# Approaches
In order to predict what Bitcoin will do in the near future, we can use a recurrent neural network (RNN). RNNs can be built with either long short-term memory (LSTM) or gated recurrent units (GRU). We can use an LSTM-style RNN to do time-series forecasting since it retains sequential history and it can handle long-term trends better than other models. Since our dataset is updated daily and has been almost since the release of Bitcoin, we have a lot of data that we can put into our LSTM. Alternatively, we can use a GRU, which is simpler than an LSTM, offering similar performance with the benefit that it can be trained faster.

# Steps for the project
Download the data
Read PyTorch documentation
Determine which specific model we will use on the dataset
Plot data to find accuracy points in the training phase for our model.
Write code that will create and train our model on this data
Create a visual representation of trends in the price of Bitcoin

# Timeline
------- FINAL REPORT DUE MAY 6 --------
- March 24 (earlier if possible) - download the data either using the Bitcoin scraper or straight from Kaggle
- March 24-28 - read documentation on PyTorch and figure out how to create and train our RNN against this data
- March 29-30 - determine which specific model we want to use
- March 31-April 4 - figure out how to plot data for our model
- April 5-21 - write code that will create model and train it on data, then have that model draw up some graphs depicting the price of Bitcoin

# Team responsibilities
We will both be writing the report as we continue the project. Here is what we think the task breakdown will look like on an individual basis:
Habit
- Read PyTorch, scraper, and Poetry documentation
- Write code to train model and display graphs
- Test code
Justin
- Preprocessing for data
- Decide which specific model we are to use

# References
Bitcoin Historical Data
PyTorch website and docs
Mark Zielinski's Bitcoin scraper for Kaggle
Python Poetry (package manager for Bitcoin scraper that we may use)
