# timeseries_notes
Notes, links, ideas on analyzing time series

This is not a replacement for [awesome time_series_python](https://github.com/MaxBenChrist/awesome_time_series_in_python)

## Unsupervised
The key lies in finding a **similarity matrix**. [Review](https://www.intechopen.com/chapters/39030).

Options:
 - STOMP ([python](https://github.com/TDAmeritrade/stumpy)): Computes a matrix profile. Once you have the matrix profile, you can answer [100 questions](https://www.cs.ucr.edu/~eamonn/100_Time_Series_Data_Mining_Questions__with_Answers.pdf). Number 2 about repitions is interesting. [Multivariate](https://towardsdatascience.com/part-10-discovering-multidimensional-time-series-motifs-45da53b594bb) tutorial.
 - Dynamic Time Warping (DTW, [python](https://github.com/blue-yonder/tsfresh)): Creates Euclidean distance between points to compute a matrix. [Tutorial](https://github.com/kamperh/lecture_dtw_notebook/blob/main/dtw.ipynb) from scratch. [Differentiable](https://rtavenar.github.io/blog/softdtw.html) DTW.
 - Multivariate representation learning: [code@tsai](https://github.com/timeseriesAI/tsai/blob/main/tutorial_nbs/08_Self_Supervised_TSBERT.ipynb), [TNC](https://github.com/sanatonek/TNC_representation_learning)
 - **Change point detection**: 
[Kats](https://github.com/facebookresearch/Kats/blob/main/tutorials/kats_202_detection.ipynb)
[Benchmark](https://github.com/alan-turing-institute/TCPD)
 - **Periodicity**: https://github.com/dioph/periodicity

## Supervised
 - Classical time series: [Kats](https://github.com/facebookresearch/Kats), [DARTS](https://github.com/unit8co/darts)
 - Deep learning: 
   - [DARTS](https://github.com/unit8co/darts) 
   - [Gluon-TS](https://github.com/awslabs/gluon-ts) 
   - [tsai](https://github.com/timeseriesAI/tsai/tree/main/) 
   - [pytorch-forecasting](https://github.com/jdb78/pytorch-forecasting) 
   - [flow-forecast](https://github.com/AIStream-Peelout/flow-forecast)
   - [Neural Prophet](https://github.com/ourownstory/neural_prophet)

 - **Time Series Classification Benchmark and Datasets**: https://timeseriesclassification.com/

