# CNN-stock-prediction
This research seems weird, we used to believe that CNN is used in picture recognition, but after we know what CNN is and how it works, we can use it in the stock market. Especially in the Chinese stock market
The theory base for it is in China, people predict the stock by using Technical analysis, which relies on lots of diagrams and trends, and also some physical concepts like momentum to analyze stock market trends. 
This means that if you find characteristics and correlate with what will happen in the future with these characteristics, it can be a good prediction method.

Here we are going to separate the research into several steps:
1. get data
2. design the CNN network, and give them weight and result. Finally, combine them with the result as training data
3. try to do Backtesting.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
First, when selecting the data, we chose several  characteristics of stock we saw via eyes: from the report from Everbright securities
Thinking about using the Fourier transform method to separate different parts of the stock function can also be used as characteristics.
Also, we try to use the theory from Joseph E.Granville, which consist of  
