---
layout: page
title: Stock Price Prediction
description: Predict the trend of stock price with multiple resources and generate effective portfolios.
img: /assets/img/stock_cover.jpeg
importance: 3
category: explore
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <a href="https://arxiv.org/abs/2112.13593">
        <img class="img-fluid rounded z-depth-0" src="{{ '/assets/img/stockPrediction.png' | relative_url }}" alt="" title="stock_prediction"/>
    </div>
</div>
<div class="caption">
    Schematics of Multi-modal Attention Network for Stock Movements Prediction (He et. al., 2022)
</div>

Stock prices move as piece-wise trending fluctuation rather than a purely random walk. Traditionally, the prediction of future stock movements is based on the historical trading
record. Nowadays, with the development of social media, many active participants in the market choose to publicize their strategies, which provides a window to glimpse over the whole market’s attitude towards future movements by extracting the semantics behind social media. However, social media contains conflicting information and cannot replace historical records completely. In this work, we propose a multi-modality attention network to reduce conflicts and integrate semantic and numeric features to predict future
stock movements comprehensively. Specifically, we first extract semantic information from social media and estimate their credibility based on posters’ identity and public reputation. Then we incorporate the semantic from online posts and numeric features from historical records to make the trading strategy. Experimental results show that our approach outperforms previous methods by a significant margin in both prediction accuracy (61.20%) and trading profits (9.13%). It demonstrates that our method improves the performance of stock movements prediction and informs future research on multi-modality fusion towards stock prediction.
