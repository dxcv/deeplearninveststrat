# Deep Learning Investment Strategy - In Progress

A factor-based quantitative investing strategy that employs deep neural networks to forecast company fundamentals, based on John Alberg and Zachary Lipton's paper "Improving Factor-Based Quantitative Investing by Forecasting Company Fundamentals".


# SignelAssetAndIndicator

In this notebook, we replicate the GRU structure, which was mentioned in the paper of "Chung, J., Gulcehre, C., Cho, K., & Bengio, Y. (2014). Empirical evaluation of gated recurrent neural networks on sequence modeling. arXiv preprint arXiv:1412.3555."

We use the signal stock and it's relative fundamental and pricing data as input features to predict the indicator 'EBITV/EV'. and the results showed we overfitted a little bit, therefore, the next step is to optimized the parameters and utilize more data
