# Water Table Depth Forecasting

In this repository, you can find all the implementation codes and data for the article [_"Time Distributed Deep Learning Models for Purely Exogenous Forecasting: Application to Water Table Depth Predictions Using Weather Image Time Series"_](https://doi.org/10.1016/j.envsoft.2025.106568) (Salis et. al, 2025)

We aimed to model the weekly water table depth data of three sensors located in the Grana-Maira catchment (Piedmont, Italy), leveraging only the spatio-temporal weather information structured as a video (i.e., an image time series). To this end, we adopted time-distributed convolutional layers (TDC module) to transform the weather video into a hidden vectorial representation, allowing for autonomous learning of spatial relations directly from the video. The first model, called TDC-LSTM, adopts a sequential module based on the LSTM layer. In contrast, for the second model, we introduced a modified version of WaveNet, termed UnPWaveNet, specifically designed to handle output sequences of different lengths and shifted to the future with respect to the input ones.

For more details, refer to the published article.


