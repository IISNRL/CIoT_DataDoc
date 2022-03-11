---
title: 3. 時間維度資料分析
weight: 3
pre: ""
chapter: true
---


1. 時間序列處理
    - 週期性分析
    - Filtering (Gaussian Processes, Kalman Filter, Moving Average)
        - [Filtering Models — darts documentation](https://unit8co.github.io/darts/generated_api/darts.models.filtering.html)
    - Change Point Detection
        - [Kats: a Generalizable Framework to Analyze Time Series Data in Python | by Khuyen Tran | Towards Data Science](https://towardsdatascience.com/kats-a-generalizable-framework-to-analyze-time-series-data-in-python-3c8d21efe057)
    - Outlier Detection
        - [Kats: a Generalizable Framework to Analyze Time Series Data in Python | by Khuyen Tran | Towards Data Science](https://towardsdatascience.com/kats-a-generalizable-framework-to-analyze-time-series-data-in-python-3c8d21efe057)
2. 資料預測 (data forecast)
    - scikit-learn
    - Kats (Prophet, Holt-Winters, SARIMA, Quadratic, ...)
        - [Kats: a Generalizable Framework to Analyze Time Series Data in Python | by Khuyen Tran | Towards Data Science](https://towardsdatascience.com/kats-a-generalizable-framework-to-analyze-time-series-data-in-python-3c8d21efe057)
        - [Kats - Time Series Forecasting By Facebook | by Himanshu Sharma | MLearning.ai | Medium](https://medium.com/mlearning-ai/kats-time-series-forecasting-by-facebook-a2741794d814)
    - statsforecast:statsforecast
        - [Fast time series forecasting with StatsForecast | Towards Data Science](https://towardsdatascience.com/fast-time-series-forecasting-with-statsforecast-694d1670a2f3)
    - TBATS:TBATS
        - [End-to-End Time Series Forecasting Project with TBATS and Pandas in Python | by James Ralph | Medium](https://medium.com/@james.ralph8555/end-to-end-time-series-forecasting-project-with-tbats-and-pandas-in-python-4c56a2771023)
    - Darts (BlockRNNModel, RNNModel, RegressionModel)
        - [Time Series Made Easy in Python — darts documentation](https://unit8co.github.io/darts/)
        - [Time Series Forecasting Using Past and Future External Data with Darts | Unit8 - Big Data & AI](https://medium.com/unit8-machine-learning-publication/time-series-forecasting-using-past-and-future-external-data-with-darts-1f0539585993)
3. 測站屬性分群 (clustering, DWT, FFT, Wavelet)
    - [Time Series Clustering — Deriving Trends and Archetypes from Sequential Data | by Denyse | Towards Data Science](https://towardsdatascience.com/time-series-clustering-deriving-trends-and-archetypes-from-sequential-data-bb87783312b4)
    - [How to Apply K-means Clustering to Time Series Data | by Alexandra Amidon | Towards Data Science](https://towardsdatascience.com/how-to-apply-k-means-clustering-to-time-series-data-28d04a8f7da3)
    - [Fast Fourier Transform. How to implement the Fast Fourier… | by Cory Maklin | Towards Data Science](https://towardsdatascience.com/fast-fourier-transform-937926e591cb)
    - [PyWavelets/pywt: PyWavelets - Wavelet Transforms in Python](https://github.com/PyWavelets/pywt)

{{% children description="true" %}}
