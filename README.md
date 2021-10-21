# timeseries_notes
Notes, links, ideas on analyzing time series

This is not a replacement for [awesome time_series_python](https://github.com/MaxBenChrist/awesome_time_series_in_python)

## Unsupervised
The key lies in finding a **similarity matrix**. [Review](https://www.intechopen.com/chapters/39030).

Options:
 - STOMP ([python](https://github.com/TDAmeritrade/stumpy)): Computes a matrix profile. Once you have the matrix profile, you can answer [100 questions](https://www.cs.ucr.edu/~eamonn/100_Time_Series_Data_Mining_Questions__with_Answers.pdf). Number 2 about repitions is interesting. [Multivariate](https://towardsdatascience.com/part-10-discovering-multidimensional-time-series-motifs-45da53b594bb) tutorial.
 - Dynamic Time Warping (DTW, [python](https://github.com/blue-yonder/tsfresh)): Creates Euclidean distance between points to compute a matrix. [Tutorial](https://github.com/kamperh/lecture_dtw_notebook/blob/main/dtw.ipynb) from scratch. [Differentiable](https://rtavenar.github.io/blog/softdtw.html) DTW.
 - Multivariate representation learning: [code@tsai](https://github.com/timeseriesAI/tsai/blob/main/tutorial_nbs/08_Self_Supervised_TSBERT.ipynb), [TNC](https://github.com/sanatonek/TNC_representation_learning)
