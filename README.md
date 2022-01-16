# Integer Programming for Portfolio Construction
Guidance of creating an index fund to mirror the NASDAQ-100 index with Integer Programming


# Introduction
We will show you how to use integer programming with the Gurobi Python API to create an index fund that tracks the NASDAQ-100 as closely as possible while also keeping the number of component stocks in the fund to a minimum.

Please kindly note that this blog is designed to be used for informational and educational purposes only and does not constitute investment or financial advice.

We hope you enjoy this learning journey! Feel free to fork and play with the code for this article in this Github repo.


# Approach
This task will be mathematically formulated as an integer optimization problem. To demonstrate our method, we will use daily prices of the index and the component stocks of the NASDAQ-100 in 2019 and 2020, calculate the returns of the component stocks and the index in 2019 and 2020, as well as correlation matrix of stock returns, then obtain optimal solutions using 2019 price data, and evaluate the solutions using 2020 price data.


# Blog
For a detailed explanation and report of this module, please refer to our blog: https://medium.com/@pingzhang0108/how-to-construct-portfolio-to-track-broad-market-with-python-8900fcb6541a
